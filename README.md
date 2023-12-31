# Machine_Learning_Case_Study

This case study is on Student Performance Predictor

#### <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="30px">&nbsp;***Language and Libraries*** 

<p>
<a><img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen" alt="Seaborn"/></a>
 <a><img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" alt="Seaborn"width="110"/></a>
  <code> <img height="50" src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Spyder_logo.svg"> </code>
  <code> <img height="50" src="https://www.vectorlogo.zone/logos/jupyter/jupyter-ar21.svg"> </code>
  <code> <img height="50" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/768px-Pandas_logo.svg.png"> </code>
  <code> <img height="50" src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-ar21.svg"> </code>
  <code> <img height="50" src="https://www.vectorlogo.zone/logos/numpy/numpy-ar21.svg"> </code>
  <code> <img height="50" src="https://raw.githubusercontent.com/valohai/ml-logos/master/scipy.svg"> </code>
  <code> <img height="50" src="https://seeklogo.com/images/S/scikit-learn-logo-8766D07E2E-seeklogo.com.png"> </code>
</p>


## Data
The dataset is collected from <a href="https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977">Kaggle</a> or direct link
(https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977)

* This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch, and Test preparation course.

## Data Understanding
The dataset used to predict stroke is a dataset from Kaggle. This dataset has been used to predict student performance with  different model algorithms. This dataset has:
- 1000 samples or rows
- 8 features or columns 
- 1 target column (average).



## Features in Datasets:
1. Gender: Student's gender ('Male', 'Female') [str]
2. race/ethnicity: Ethnicity of students -> (Group A, B, C, D, E) [str]
3. parental level of education:  parents' final education ->(bachelor's degree, some college, master's degree, associate's degree, high school)[str]
4. lunch: having lunch before the test (standard or free/reduced). [str]
5. test preparation course: complete or not complete before the test [str]
6. math score [int]
7. reading score[int]
8. writing score[int]

Target:
average: Prediction target column [int]

## Type of Machine Learning task : 
It is a regression problem where given a set of features we need to predict whether that person is prone to heart diseases or not.

## Performace Metric
Since it is a classification problem we will use r2 score, rmse, and mse

## Files
1. <a href="https://github.com/RishavMishraRM/Machine_Learning_Case_Study/tree/main/data">data : Data folder</a>
2. <a href="url">EDA student performance.ipynb</a>
3. <a href="url">Stats based analysis.ipynb</a>
4. <a href="https://github.com/RishavMishraRM/Machine_Learning_Case_Study/blob/main/3.%20OUTLIER%20DETECTION%20AND%20REMOVAL.ipynb"> Outlier detection & Removal.ipynb</a>
4. <a href="url">Model training.ipynb</a>

