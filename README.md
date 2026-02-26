Retail Customer Behavior Analysis

This project demonstrates end-to-end data analytics including data cleaning, customer segmentation, predictive modeling, and business visualization.

---

Project Overview

This project focuses on analyzing retail customer transaction data to:

- Identify high-value customers
- Understand purchasing behavior
- Predict future customer value
- Improve business decision-making using data analytics

The project covers:
- RFM Customer Segmentation
- Cohort Analysis
- Market Basket Analysis
- Customer Lifetime Value (CLV) Prediction
- Business Intelligence Dashboard

---

Problem Statement

Many retail businesses run generic marketing campaigns without understanding:

- Which customers generate the most revenue
- Which customers are at risk of churn
- What products are frequently purchased together
- What the future customer value of each customer will be

This project solves these problems using data-driven customer segmentation and predictive modeling techniques.

---

Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- SQL (Data Cleaning & Transformation)
- Lifetimes Library (BG/NBD & Gamma-Gamma Models)
- Power BI (Data Visualization & Dashboarding)

---

 Project Workflow

🔹 Step 1 – Data Cleaning
- Removed missing Customer IDs
- Removed negative quantities (returns or invalid transactions)
- Filtered out incorrect or null values
- Ensured accurate revenue calculation

---

🔹 Step 2 – Feature Engineering
- Created a new column **Amount = Quantity × UnitPrice**
- Aggregated customer-level data
- Prepared dataset for RFM calculation

---

🔹 Step 3 – RFM Analysis
Calculated:

- **Recency** – How recently a customer purchased
- **Frequency** – How often they purchase
- **Monetary** – How much revenue they generate

Segmented customers into:
- Champions
- Loyal Customers
- Potential Loyalists
- At-Risk Customers
- Lost Customers

---

🔹 Step 4 – RFM Scoring
- Assigned scores from 1 to 5 for each RFM metric
- Standardized customer comparison
- Created structured customer segments

---

🔹 Step 5 – Cohort Analysis
- Tracked customer retention over time
- Measured repeat purchase behavior
- Analyzed loyalty trends

---

🔹 Step 6 – Market Basket Analysis
- Applied Apriori Algorithm
- Generated association rules
- Used **Lift metric** to measure product relationships
- Identified cross-selling opportunities

---

🔹 Step 7 – Predictive Customer Lifetime Value (CLV)
- Implemented **BG/NBD model**
- Applied **Gamma-Gamma model**
- Predicted future purchase frequency
- Estimated long-term customer revenue

---

 📊 Key Insights

- A small percentage of customers contribute majority of revenue
- Identified high churn-risk customers
- Found strong product combinations for cross-selling
- Estimated future revenue using CLV modeling

---

📈 Business Impact

This project helps businesses:

- Improve targeted marketing campaigns
- Increase revenue through cross-selling
- Reduce customer churn
- Focus on high-value customers
- Make data-driven strategic decisions

---

📷 Dashboard Preview

(Add Power BI Dashboard screenshots here)

---

🚀 How to Run This Project

1. Clone the repository
2. Install required libraries:

   ```
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook
4. Open Power BI dashboard file (.pbix)

---

📂 Project Structure
```
Retail-Customer-Behavior-Analysis/
│
├── data/
├── notebooks/
├── Retail_Customer_Analysis.ipynb
├── retail_cleaned_data.csv
├── PowerBI_Dashboard.pbix
├── requirements.txt
└── README.md
```

---
Author
Somnath Mukherjee  
Aspiring Data Analyst  
Focused on SQL | Python | Power BI | Business Analytics  

---

⭐ If you found this project useful, feel free to give it a star!
