# cloud-kitchen-demand-forecasting
Machine Learning project for Demand Forecasting using Random Forest and XGBoost


##  Problem Statement
Cloud kitchens face difficulty in predicting demand, leading to food waste or shortages.  
This project builds a machine learning model to forecast demand using historical sales data.


##  Dataset
Due to file size limitations, the dataset is not included in this repository.


Download it from:
https://www.kaggle.com/competitions/store-item-demand-forecasting-challenge/data


After downloading, place the file inside:
data/retail_sales.csv


## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- XGBoost


## Models Used
- Random Forest Regressor
- XGBoost Regressor


## Results
- Random Forest MAE: ~2.57  
- XGBoost MAE: ~2.53  


XGBoost performed slightly better.


## How to Run
1. Clone the repository  
2. Download dataset from Kaggle  
3. Place dataset in `data/` folder  
4. Run the notebook  


## Conclusion
The model successfully predicts demand and can help reduce food waste in cloud kitchens.
