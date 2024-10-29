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

### Tools Used
Python

### Libraries
 - Numpy
 - Pandas
 - Seaborn
 - Matplotlib

### Key insights
#### 1. Overall Churn Rate: The analysis showed an overall churn rate of approximately 26.54%
#### 2. Customer Demographics:
 - Senior Citizens: Senior customers tend to have a higher churn rate than younger customers.
#### 3. Contract Type:
 - Customers on month-to-month contracts are more likely to churn compared to those on longer-term contracts (e.g., 2-year contracts).
#### 4. Service Features:
 - Customers who do not have online security are more prone to churn, though those with online security have a higher churn rate compared to customers without internet services.
 - Among internet service types, customers with fiber optic services show the highest churn rate, while those without internet services have the lowest.
#### 5. Payment Method:
 - Customers who pay via electronic check have a notably higher churn rate, while those using credit cards have the lowest.
#### 6. Tenure:
 - Newer customers, particularly those with tenures under two years, exhibit a much higher churn rate than long-term customers (5+ years).
#### 7. Monthly Charges:
 - Correlation analysis indicates that higher monthly charges are linked to a greater likelihood of customer churn.

### Project Link
Analysis [View the analysis on Jupyter Notebook]()

### Recommendations
#### 1. Promote Long-Term Contracts:
 - Encourage customers to opt for two-year contracts rather than month-to-month plans by offering incentives, such as discounts or additional perks. Long-term contracts tend to reduce churn by creating a sense of commitment and stability.
#### 2. Encourage Online Security Services:
 - Emphasize the benefits of online security features to customers, as those who subscribe to these services show higher retention rates. Offering bundled packages that include security features could make these services more appealing.
#### 3. Promote Credit Card Payment Options:
 - Since customers using credit card payments have the lowest churn rate, incentivize credit card use through small discounts or loyalty points, which may lead to greater retention
#### 4. Implement New Customer Retention Incentives:
 - Offer discounts, loyalty rewards, or special perks to new customers to encourage long-term retention beyond the first two years. This can help retain customers during the critical early stages of their tenure.
#### 5. Promote DSL Services For Internet Subscribers:
 - DSL users show lower churn rates than fiber optic users, emphasize the reliability and affordability of DSL to new customers or to those looking to downgrade, potentially reducing churn for cost-sensitive customers.

### Referenes
 - Geek for geeks: more about boxplot and it's uses [link](https://www.geeksforgeeks.org/box-plot-visualization-with-pandas-and-seaborn/)
 - Khan Academy: more opinions about the use of boxplot [link](https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data/box-whisker-plots/a/box-plot-review#:~:text=A%20box%20and%20whisker%20plot%E2%80%94also%20called%20a%20box%20plot,the%20box%20at%20the%20median.)


