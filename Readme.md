# Telecom Customer Churn - Data Analysis

## Dataset
Telco Customer Churn Dataset from Kaggle  
7043 rows × 21 columns

## Libraries Used
- Pandas — data manipulation
- NumPy — numerical operations
- Matplotlib — plotting charts
- Seaborn — statistical visualizations

## What I Did
- Loaded and explored the dataset (EDA)
- Fixed TotalCharges column (blank spaces → 0)
- Converted SeniorCitizen from 0/1 to yes/no
- Checked for null values and duplicates
- Created 10 visualizations with insights on customer churn

## Visualizations
1. Customer Count by Churn
2. Customer % by Churn (Pie Chart)
3. Churn by Gender
4. Churn by Internet Service Type
5. Monthly Charges Distribution by Churn
6. Tenure Distribution by Churn
7. Churn by Payment Method
8. Monthly Charges vs Total Charges
9. Churn by Senior Citizen Status
10. Churn by Tech Support & Online Security

## Key Finding
26% of customers churned. Main reasons include high monthly charges,
month-to-month contracts, and lack of support services.

## How to Run
1. Open `ML_Data_Analysis.ipynb` in Google Colab
2. Upload `WA_Fn-UseC_-Telco-Customer-Churn.csv` when prompted
3. Run all cells from top to bottom
