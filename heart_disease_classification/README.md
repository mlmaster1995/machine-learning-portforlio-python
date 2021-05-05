# Heart Disease Classification & Feature Analysis

## About The Project 
- This project is to classify the heart disease via supervised learning based on the data attributes. 


- The project is composed of three parts: data preprocessing & visualization,  data modeling with MLP(multi-layer perceptron) and XGBoost Classifier, 
and data feature importance analysis


## Data Source
- The data could be downloaded from [here](https://www.kaggle.com/ronitf/heart-disease-uci).

## Repo Content
    
    
    .
    ├── Data Proprocessing and Visualizatioin.ipynb             # notebook for data cleaning 
    ├── Feature Analysis With ML Model.ipynb                    # google collab notebook for feature analysis
    ├── heart.csv                                               # original dataset
    ├── Heart Disease Data Modeling.ipynb                       # google collab notebook for data ml modeling
    ├── mlp_params.pkl                                          # binary file of grid search params for multi-layer perceptron model
    ├── target.csv                                              # target data file for training
    ├── train.csv                                               # train data file for training
    └── xgb_best_params.pkl                                     # binary file of grid search params for xgboost

## Analysis Workflow
1. Data Processing and Visualization -> clean the data, visualize the data and generate data and label for training

2. Heart Disease Data Modeling -> grid search on different scaled data for MLP and XGB to get the hyper-params for the best model performance

3. Feature Analysis With ML Model -> Apply Permutation Importance Score, Partial Dependence Plot and SHAP for the feature importance analysis
