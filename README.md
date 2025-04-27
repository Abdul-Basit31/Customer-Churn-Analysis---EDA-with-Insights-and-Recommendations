# Customer Churn Analysis - Exploratory Data Analysis (EDA)

## Overview

This project performs an **Exploratory Data Analysis (EDA)** on customer churn data to identify key factors influencing customer retention. The main objective is to determine which factors are most strongly associated with higher churn rates, such as **payment methods**, **contract types**, and **customer tenure**, and provide actionable recommendations for improving customer retention.

## Key Insights

### 1. **Contract Type and Churn**
   - Customers on **month-to-month contracts** have a significantly higher churn rate of **42%**.
   - Customers on **yearly contracts** show a churn rate of **11%**, and those on **two-year contracts** exhibit the lowest churn rate of **3%**.
   - **Recommendation**: Encourage customers to opt for longer contract periods to reduce churn.

### 2. **Payment Methods and Churn**
   - Customers using **electronic checks** have the highest churn rate of **45%**, while those using **credit cards** and **bank transfers** have churn rates ranging from **15% to 18%**.
   - **Recommendation**: Promote more reliable and secure payment methods to reduce churn.

### 3. **Customer Tenure and Churn**
   - Customers with **less than one year** of tenure have a churn rate of **50%**.
   - Churn rates decrease as tenure increases: **35%** for **1-3 years**, and **15%** for customers with **more than three years**.
   - **Recommendation**: Focus on engaging new customers in their first year to prevent churn.

### 4. **Senior Citizens and Churn**
   - **Senior citizens (65+)** exhibit a churn rate of **41%**, which is higher compared to **26%** for non-senior citizens.
   - **Recommendation**: Create personalized retention programs for senior customers to reduce churn.

## Visualizations

The project includes various **visualizations** to help understand churn patterns:

- **Churn Rate by Payment Method**
- **Churn Rate by Contract Type**
- **Churn Rate by Customer Tenure**
- **Churn Rate for Senior Citizens vs Non-Senior Citizens**

These visualizations provide a clear understanding of the relationships between customer behavior and churn.

## Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

customer-churn-analysis/
│
├── data/
│   └── churn_data.csv      # Dataset used for analysis
│
├── notebooks/
│   └── Exploratory_Data_Analysis.ipynb  # Main Jupyter notebook containing the analysis
│
├── visualizations/
│   ├── churn_by_payment_method.png   # Bar chart visualizing churn by payment method
│   ├── churn_by_contract_type.png    # Bar chart visualizing churn by contract type
│   └── churn_by_tenure.png           # Line graph visualizing churn by customer tenure
│
├── requirements.txt          # Python dependencies
└── README.md                 # This file

## Conclusion
This analysis provides insights into the key factors influencing customer churn, and offers actionable recommendations for improving customer retention. By focusing on contract types, payment methods, customer tenure, and special programs for senior citizens, businesses can develop more effective retention strategies.

**For any questions or suggestions, feel free to reach out via bassitb50@gmail.com.**
