# PRODIGY_ML_01 House Price Prediction
This project aims to predict house prices using regression techniques on the dataset provided by the Kaggle competition "House Prices: Advanced Regression Techniques".

## Project Overview
The notebook Task1_House_Price_Prediction.ipynb contains the following steps:

## Dataset
The dataset used in this project is from the Kaggle competition "House Prices: Advanced Regression Techniques". It includes various features related to houses such as LotArea, YearBuilt, 1stFlrSF, 2ndFlrSF, GrLivArea, FullBath, BedroomAbvGr, TotRmsAbvGrd, etc.

## Data Import and Preprocessing:
Importing necessary libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn.
Downloading and loading the dataset.
Displaying the dataset to understand its structure.

## Data Cleaning and Feature Engineering:
Handling missing values.
Encoding categorical features.
Scaling numerical features.

## Model Building and Evaluation:
Splitting the data into training and testing sets.
Building a Linear Regression model.
Evaluating the model using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared score.



## How to Run the Notebook ? Clone the repository:
```bash
git clone https://github.com/jm12312/PRODIGY_ML_01.git
cd PRODIGY_ML_01
```

Open the notebook Task1_House_Price_Prediction.ipynb using Jupyter Notebook or any compatible editor and run the cells sequentially.


## Results
The model's performance can be evaluated using the provided metrics. The initial results show the effectiveness of the Linear Regression model in predicting house prices based on the provided features.

Time taken: 0.441
Training RMSE: 21685.078
Validation RMSE: 27323.325
Training MAE: 14645.242
Validation MAE: 18742.042 
Training R²: 0.927
Validation R²: 0.865

## Conclusion
This project demonstrates the process of building a regression model to predict house prices. Future improvements can include exploring other regression techniques and performing hyperparameter tuning to enhance model performance.

For more details, refer to the notebook.
