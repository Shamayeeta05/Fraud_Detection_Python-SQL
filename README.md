# 💳 Credit Card Transaction Fraud Detection using Python and SQL

This project explores and analyzes a real-world credit card transaction dataset to uncover fraud patterns using a combination of **Python** for data analysis & visualization and **MySQL** for querying. The project showcases SQL skills, data storytelling, and insight generation for a data analytics portfolio.

---

## 📂 Dataset Overview

The dataset contains **over 550,000 transactions**, including:
- Customer information (`cc_num`, `first`, `last`, `dob`, `job`, etc.)
- Transaction details (`trans_date_trans_time`, `merchant`, `amt`, `category`, `state`, etc.)
- Fraud label (`is_fraud` — 1 for fraud, 0 for normal)

---

## 🧠 Key Business Questions Explored

✅ Basic:
- What is the total number of transactions?
- What percentage of transactions are fraudulent vs. non-fraudulent?
- What is the distribution of transaction amounts?
- Which customer has the highest number of transactions?

✅ Intermediate:
- What is the average transaction amount for fraud vs. non-fraud?
- Who are the top 10 customers by transaction value?
- Which job categories are more likely involved in fraud?
- Are there specific time periods (hour/day/week) when frauds peak?

✅ Advanced:
- Are there suspicious patterns between the same sender and merchant?
- Are there rapid successive transactions from the same user (possible bots)?
- Which merchants receive the most fraudulent funds?
- What is the average fraud amount by age group?

---

📊 Visualizations Included
Pie chart: Fraud vs. Non-Fraud distribution
Histogram: Transaction amount distribution
Bar charts: Fraud by time (hour, day, week)
Heatmap: Fraud rate by time of day
Top customers, states, merchants involved in fraud

🧰 Tech Stack
Language: Python 3.13
Libraries: pandas, matplotlib, seaborn, mysql-connector-python
Database: MySQL 8.x
Tools: Jupyter Notebook, MySQL Workbench

✅ Insights Summary
Fraud accounts for less than 0.5% of all transactions but is concentrated in high-amount bands (especially ₹750+).
Job titles like "Software Engineer" and "Investment Banker" showed disproportionately high fraud rates.
Certain merchants consistently receive fraud payments in quick succession.
Several users performed rapid transactions within seconds — potential signs of automation/bot behavior.
Fraud is more likely during late-night hours (1–4 AM).

🔗 Project Highlights
Realistic end-to-end data analysis workflow.
Combines SQL querying power with Python data visualization.
Clear, business-relevant fraud analytics use cases.

📌 Author
Shamayeeta Gupta
Data Analytics Portfolio Project
GitHub Profile: https://github.com/Shamayeeta05

⭐ If you liked this project...
Give it a ⭐ on GitHub and connect with me on LinkedIn!
Linkedin Profile: www.linkedin.com/in/shamayeeta-gupta-455336291
