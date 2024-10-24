# Customer-Churn-Analysis-and-Retention-Strategies

### Project Overview 
In this project, I analyzed customer churn data from a telecommunications company to gain insights into the factors most likely to contribute to customer churn. I explored the churn rate across various customer attributes and segmented customers based on characteristics such as tenure and contract type. This segmentation helped identify churn patterns and calculate churn rates for different customer groups, providing actionable insights for improving customer retention.

### Objective
The objective of this analysis is to identify key factors contributing to customer churn and provide actionable insights to help improve customer retention strategies. 

### Data Source
Kaggle [Download here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

### Methodology
#### 1. Data Loading:
 - Imported necessary libraries such as pandas and matplotlib.
 - Loaded the customer churn dataset into a pandas DataFrame for analysis.
#### 2. Data Inspection:
 - Reviewed the data structure by checking column formats and data types.
 - Identified key columns for analysis and made appropriate data type conversions to ensure consistency.
#### 3. Data Cleaning:
 - Cleaned the TotalCharges column by converting it to a numeric (float) data type.
 - Created a new column, Churn_Mapped, by mapping the string values in the Churn column to numerical values for easier analysis and to facilitate churn rate calculations.
#### 4. Data Analysis:
 - Performed exploratory data analysis (EDA) using statistical methods and visualizations.
 - Analyzed the churn rate in relation to attributes such as internet service type, contract type, tenure, and more.
 - Used boxplots to identify outliers in features like MonthlyCharges and TotalCharges.
 - Generated a heatmap to visualize correlations between customer attributes and churn.

