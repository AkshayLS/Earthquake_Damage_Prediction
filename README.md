
# Earthquake Damage Prediction
In April of 2015 the 7.8 magnitude Gorkha earthquake occured near the Gorkha district of Gandaki Pradesh, Nepal. Almost 9,000 lives were lost, millions of people were instantly made homeless, and $10 billion in damages––about half of Nepal's nominal GDP––were incurred. In the years since, the Nepalese government has worked intensely to help rebuild the affected districts' infrastructures. Throughout this process, the National Planning Commission, along with Kathmandu Living Labs and the Central Bureau of Statistics, has generated one of the largest post-disaster datasets ever collected, containing valuable information on earthquake impacts, household conditions, and socio-economic-demographic statistics.

# Data
The data comes from the 2015 Nepal Earthquake Open Data Portal, and mainly consists of information on the buildings' structure and their legal ownership. Each row in the dataset represents a specific building in the region that was hit by Gorkha earthquake.
Data was collected from a competition hosted by [DrivenData](https://www.drivendata.org/competitions/57/nepal-earthquake/).

# Goal
The goal of this project is to predict the level of damage to buildings caused by the 2015 Gorkha earthquake in Nepal.

# Code 
Please refer the ipynb notebooks for a detailed walkthrough of the entire project.

# Workflow
1.  Exploratory Data Analysis   
    - Basic Checks
    - Missing Values
    - Target Variable
    - Numerical Features
    - Categorical features
    - Skewness and Kurtosis
    - Outliers
    - Correlation
2.  Pre-processing
    - Treating Outliers
    - Encoding
    - New Features
    - Correcting Skewness
    - Train Test Split
    - Scaling
    - Feature Selection
3.  Model Building and Evalation  
    - Models
    - Performance Table
    - Hyper tune Xgboost Parameters
    - Evalation Results
    - Feature Importance
    - Prediction Table

# Evalation Metric
We will be using the Receiver Operating Characteristic Area under the curve (ROC AUC score) Metric. The ROC curve is useful for predicting the probability of outcome being in a certain class. One benefit of the ROC curves is that different models can be compared directly in general using the area under the curve (AUC) measurement. A higher AUC score means a better model.

# Contributers
Akshay Shettigar

# Acknowledgments
1.  For hyperparameter tuning using Optuna :
    - [XGBoost & Catboost Using Optuna](https://www.kaggle.com/code/hamzaghanmi/xgboost-catboost-using-optuna?scriptVersionId=94510532)
    - [Hyperparameter Optimization](https://www.youtube.com/watch?v=5nYqK-HaoKY)
