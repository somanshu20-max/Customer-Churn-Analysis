# 📊 Telecom Customer Churn Analysis

This is my first data analytics project where I explored a telecom dataset to understand customer churn patterns using Python. The goal was to identify key features that influence a customer's decision to leave the service and provide actionable insights based on the data.

---

## 📁 Dataset

The dataset contains 7,043 customer records and 21 features, including:
- Demographics (e.g., gender, senior citizen)
- Services signed up for (e.g., phone, internet, security)
- Account details (e.g., contract type, billing method)
- Churn status (Yes/No)

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔍 Key Analyses Performed

- **Data Cleaning**: Handled missing and incorrect values (e.g., empty `TotalCharges`)
- **Feature Engineering**: Converted binary columns like `SeniorCitizen` to meaningful labels
- **Exploratory Data Analysis**: 
  - Countplots and histograms for visual insight
  - Pie charts for churn rate distribution
  - Stacked bar charts for churn by service type and customer profile
- **Insights Extraction**: 
  - Customers with month-to-month contracts and electronic check payments were more likely to churn
  - Users with long tenures or added services (like tech support) tended to stay
  - Senior citizens had a higher churn rate

---

## 📌 Insights Summary

- 🔁 **Churn Rate**: ~26.5% of customers left
- 📉 **High Risk Factors**: Month-to-month contracts, no online security, electronic check payments
- 📈 **Loyalty Indicators**: Long tenure, annual/bi-annual contracts, bundled services

---

## 📎 Visualizations

The project includes multiple visualizations like:
- Churn distribution pie chart
- Bar plots for each service feature against churn
- Stacked bar chart showing percentage churn by senior citizen status
- Histograms for tenure vs churn behavior

---

## 🚀 What's Next?

This project was a great starting point to strengthen my data analysis skills. Next steps might include:
- Building a churn prediction model
- Automating the report generation
- Creating dashboards using Power BI or Tableau

---

## 📂 Repository Structure

|-- telecom-churn-analysis/ |-- data/ |-- customer_churn.csv |-- notebooks/ |-- churn_analysis.ipynb |-- images/ |-- charts and visualizations |-- README.md


