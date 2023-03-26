# Churn_Mdelling

The dataset used here is taken from Kaggle: https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling. The dataset contains 13 features and target variable as 0 (People not leaving the bank) and 1 (People exiting the bank)

-Dataset is quite imbalabced (0: 7963, 1:  2037)
-Class weights were calculated and CatboostRegressor was used to train
-The recall for exiting class for the model is 0.77
