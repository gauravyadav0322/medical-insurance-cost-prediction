# Medical Insurance Cost Prediction

This project builds a machine learning model to predict medical insurance charges based on demographic and health-related attributes. The dataset includes features such as age, BMI, smoking status, gender, region, and number of children. The aim is to develop a regression model that accurately estimates insurance premium costs.

## Features  
- Data cleaning and preprocessing  
- Exploratory data analysis (EDA)  
- Feature encoding and scaling  
- Training regression models using algorithms like linear regression, decision trees, etc.  
- Model evaluation using RMSE, MAE and R² metrics  
- Selection of a final optimized model  

## Technologies Used  
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Jupyter Notebook  

## Dataset  
The dataset used in this project contains the following columns:  
- age  
- sex  
- bmi  
- children  
- smoker  
- region  
- charges (target/output variable)  

## Usage / How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/gauravyadav0322/medical-insurance-cost-prediction.git
Install required libraries:

bash
Copy code
pip install -r requirements.txt
Open the notebook:

bash
Copy code
jupyter notebook Predicting_Medical_Insurance.ipynb
Run all cells to reproduce the results & predictions.

Repository Structure
Copy code
├── Predicting_Medical_Insurance.ipynb  
├── medical_insurance.csv  
└── README.md  
Results
The trained model predicts insurance charges with reasonable accuracy. By analyzing factors such as smoking status, BMI, and age, it demonstrates how health- and lifestyle-related attributes influence insurance costs.
