# -Telco-Customer-Churn-Prediction
# Telco Customer Churn Prediction

## Project Overview
This project aims to predict customer churn for a telecommunications company using a real-world dataset with over 7,000 customer records. By identifying which customers are likely to leave, businesses can target retention efforts effectively.

## Data Preparation
- Loaded and cleaned the Telco customer dataset  
- Converted categorical variables using one-hot encoding  
- Handled missing values and converted data types as needed  

## Models Trained
- Logistic Regression: Achieved 82% accuracy with balanced precision and recall  
- Random Forest Classifier: Provided feature importance insights to understand key churn drivers  

## Key Findings
- **Tenure** (how long a customer has been with the company) is the strongest predictor of churn  
- Customers with **higher monthly charges** are more likely to churn  
- Payment method “Electronic check” is associated with higher churn risk  
- Customers with **Fiber optic internet service** show different churn patterns  
- Availability of **Online Security** service reduces churn likelihood  

## Business Recommendations
- Focus retention programs on **new customers** to reduce early churn  
- Review pricing strategies, especially for high monthly charges  
- Promote online security features to increase customer loyalty  
- Investigate and improve payment processes related to electronic checks  

## How to Use This Repository
- Explore the Jupyter Notebook `telco_churn_prediction.ipynb` for detailed code and analysis  
- Models are trained using Python's scikit-learn library  
- Visualizations created with seaborn and matplotlib  

---

Feel free to reach out for any questions or collaboration opportunities!

