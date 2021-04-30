# Online Shoppers Intention Classification

## About The Project 
- This project is to classify the online shopping intention via supervised learning based on the data attributes. 
The project is composed of two parts - data preprocessing and data modeling.


- The data is processed with different scale techniques including 'standard-scaler', 'max-min-scaler','max-abs-scaler'
'gaussian-scaler', 'uniform-scaler', 'l1-norm-scaler', 'l2-norm-scaler', 'max-norm-scaler'


- Data preprocessing contains data cleaning, data visualization and data feature importance evaluation


- Data modeling contains 5 classifiers including Logistic Regression, SVM, RandomForest, KNN and XGBoost. Grid search
is implemented on each mode for best params under the data processed with different scale techniques. 
All classification metrics are provided to a complete comparison for the model performance. 


## Data Source
- The data could be downloaded from [here](https://www.kaggle.com/henrysue/online-shoppers-intention)

## Repo Content

    .
    ├── Data Info                                   # data introduction
    ├── data_label.csv                              # processed data label for training
    ├── Data Modeling.ipynb                         # data modeling on google collab
    ├── Data Preprocessing and Analysis.ipynb       # data preprocessing on jupyter notebook
    ├── online_shoppers_intention.csv               # orignal data file
    ├── processed_data.csv                          # processed data for training
    ├── lrc_best_params.pkl                         # grid search params for logistic regression model
    ├── svm_best_params.pkl                         # grid search params for support vector machine model
    └── xgb_best_params.pkl                         # grid search params for xgboost model
