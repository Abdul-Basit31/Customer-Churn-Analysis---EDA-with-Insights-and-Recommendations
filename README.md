Customer Churn Analysis - EDA with Insights and Recommendations
Overview
This project performs an Exploratory Data Analysis (EDA) to explore the key factors influencing customer churn in a subscription-based service. By analyzing various factors like payment methods, contract types, customer tenure, and other demographic data, we can identify patterns and propose recommendations to help reduce churn and improve customer retention strategies.

Key Insights
Contract Type and Churn:

Customers on month-to-month contracts show a significantly higher churn rate of 42%.

Customers on yearly contracts have a churn rate of 11%, while those on two-year contracts show the lowest churn rate of 3%.

Recommendation: Encourage customers to switch to longer contract periods for improved retention.

Payment Methods and Churn:

Electronic checks have the highest churn rate at 45%, compared to 15-18% for other payment methods like credit cards and bank transfers.

Recommendation: Offer incentives for customers to switch from electronic checks to more reliable payment methods.

Customer Tenure and Churn:

Customers with less than one year of tenure have a churn rate of 50%, which drops to 35% for customers with 1-3 years of tenure and 15% for those with more than three years.

Recommendation: Focus on engaging customers early in their journey to reduce churn in the first year.

Senior Citizens and Churn:

Senior citizens (65+) have a churn rate of 41%, which is significantly higher than 26% for non-senior citizens.

Recommendation: Create personalized retention programs for senior customers to reduce churn in this demographic.

Visualizations
The project includes a series of visualizations (bar charts, line graphs, etc.) that highlight the following key findings:

Churn Rate by Payment Method

Churn Rate by Contract Type

Churn Rate by Customer Tenure

Churn Rate by Senior Citizens vs Non-Senior Citizens

These visualizations offer clear insights into customer behavior and the factors contributing to churn.

Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

How to Run
To run this project on your local machine, follow these steps:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/customer-churn-analysis.git
Navigate to the project directory:

bash
Copy
Edit
cd customer-churn-analysis
Install the required libraries: Create a virtual environment (optional but recommended) and install dependencies using requirements.txt:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook Exploratory_Data_Analysis.ipynb
Project Structure
bash
Copy
Edit
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
Conclusion
This analysis provides actionable insights into customer churn, identifying key factors like contract type, payment methods, customer tenure, and demographics that significantly impact churn rates. The recommendations made in this analysis can help businesses in the subscription-based service industry to improve customer retention strategies and reduce churn.

Feel free to explore the notebook and visualizations in the repository, and reach out if you have any questions or suggestions!

Contact
If you have any questions or would like to discuss this project further, feel free to reach out to me via email(bassitb50@gmail.com).
