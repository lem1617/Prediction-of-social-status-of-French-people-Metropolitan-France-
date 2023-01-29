# Prediction-of-social-status-of-French-people-Metropolitan-France-
## Introduction
This project aimed at building a predictive model for prediction of citizen social status. Four different models were used including Linear Regression, Support Vector Machine, Random Forest Regressor, XGBoost Regression. Then, applying resampling technique to select the best model before estimate the future performances of the model on new data

## Data
The data sets were provided for a Machine Learning project at University Paris Dauphine. They concern 100000 French persons (from Metropolitan France). The data set has been split into a learning set with 50000 persons and a test set with 50000 persons.
Data sets include:
- `Persons` Age, sex, diploma,...
- `Job` economic sector, type of job, annual salary
- `Sport` club
- `Categorical variables and geography` city, department, regions

**Raw data source:** [French National Institute for Statistics and Economic Studies (INSEE)](https://statistiques-locales.insee.fr/?fbclid=IwAR3h1SgcWlg4H4R-btEWu7dnMjeO0dW9Mv-OfJ0IHf6yRI4ivAV2KNwOhd4#c=indicator&view=map2)

## Results

#### PCA
![image](https://user-images.githubusercontent.com/89247170/215338655-303156ce-80d6-42e1-a561-af34e16ae005.png)

#### Scores
| Model                  |  MS        | R2 Score  |
| ---------------------- |:----------:| ---------:|
| Linear Regression      | 100.72872  | 0.4712305 |
| Support Vector Machine | 79.089247  | 0.5848264 |
| Random Forest          | 62.705493  | 0.6708312 |
| XGBoost                | 41.119488  | 0.7841456 |
