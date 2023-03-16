# Projects: 
Repository for my Data Science related Projects.

1. **Forecasting with SARIMA model** : the goal of this project is to forecast the sales of a chain of stores in Ecuador using the SARIMA (Season AutoRegressive Integrated Moving Average) model. The data comes from the "Store Forecasting" competition in Kaggle. Irnitially, we manually fit the SARIMA model to a store chosen at random then we use the auto.arima package to automatically get the parameters of the SARIMA model. As a next step of this project, I will like to compare the performance of our SARIMA model with other state of the art machine learning models such as : 
  - Prophet
  - LightGBM

2. **Credit Card Default**: with this project, I want to detect fraudulent transactions from a series of transactions that occur between Jan - Apr 2022. I explore a number of machine learning techniques for my predictions. Initially,  I tried artiificially augmenting the fruadulent transactions using the SMOTE technique. However,  we see the techniques perform better without augmentation of the dataset. the Due to the imbalance in the dataset, precision is used as our metric of interest rather than accuracy.The dataset is provided by Kaggle for th e
