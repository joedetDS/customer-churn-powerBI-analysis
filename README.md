# Customer Churn Analysis Dashboard

## Overview

This repository contains a Power BI dashboard designed to analyze customer churn and its underlying factors. The dashboard provides insights into customer demographics, financial attributes, and behavioral trends that contribute to churn, helping organizations strategize to improve retention and reduce revenue loss.

---

## Features

- **Key Metrics (Card Visuals):**
  - Total Customers
  - Churned Customers
  - Active Customers
  - Inactive Customers
  - Average Customer Balance

- **Visual Analyses:**
  - **Churn Analysis by Demographics:** Stacked bar chart showing churn rates across age groups and genders.
  - **Country-Wise Churn Rate:** Bar chart highlighting churn variations by country.
  - **Balance Insights:** Scatter plot illustrating customer balance distribution against credit scores.
  - **Tenure Analysis:** Line chart showing churn trends across customer tenure.
  - **Customer Activity Analysis:** Doughnut chart comparing active and inactive customers.
  - **Churned vs. Retained Customers:** Bar chart for direct comparison.
  - **Revenue Loss Estimation:** Bar chart visualizing potential revenue impact due to churn.

- **Interactive Features:**
  - Drill-through capabilities to explore data further.
  - Filters for dynamic adjustments by region, gender, tenure, etc.

---

## Dataset

The analysis is based on a customer churn dataset with the following key columns:
- **Customer ID:** Unique identifier for each customer.
- **Churn Status:** Binary column indicating churned (1) or retained (0) customers.
- **Active Member:** Indicates whether the customer is currently active.
- **Balance:** Account balance of the customer.
- **Credit Score:** Creditworthiness score of the customer.
- **Tenure:** Number of months the customer has been with the company.

---

## Installation and Usage

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/joedetDS/customer-churn-powerBI-analysis.git
   ```

2. Open the `.pbix` file using Microsoft Power BI Desktop.

3. Ensure the dataset (`customer_churn_data.csv`) is located in the specified directory or update the data source in Power BI.

4. Explore the dashboard visuals and interact with the filters to gain insights.

---

## Insights

- High churn rates are observed in younger age groups and customers with lower account balances.
- Countries with higher churn rates require targeted retention campaigns.
- Customers with low credit scores and short tenure show increased churn likelihood.
- Revenue loss estimation highlights the financial impact of customer churn.

---

## Future Improvements

- Incorporate predictive modeling to forecast churn probabilities.
- Add more visualizations for customer satisfaction trends.
- Integrate real-time data for live tracking of churn metrics.

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to enhance this project.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

Let me know if you'd like to customize this further!
