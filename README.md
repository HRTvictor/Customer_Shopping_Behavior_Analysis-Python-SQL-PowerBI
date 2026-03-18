# Customer Shopping Behavior Analysis

[cite_start]This project provides a comprehensive analysis of customer shopping behavior using a dataset of **3,900 purchases**[cite: 3]. [cite_start]By leveraging **Python** for data cleaning [cite: 10][cite_start], **SQL** for business logic [cite: 24][cite_start], and **Power BI** for visualization [cite: 70][cite_start], the study uncovers critical insights into spending patterns, product preferences, and subscription dynamics to drive strategic business growth[cite: 4].

---

## 🚀 Project Overview
[cite_start]The primary objective is to decode the factors influencing customer decisions—ranging from demographics and seasonal trends to the impact of discounts and shipping choices[cite: 7, 8].

### Key Dataset Statistics
* [cite_start]**Total Transactions:** 3,900[cite: 6].
* [cite_start]**Customer Base:** Predominantly Male (2,652)[cite: 14].
* [cite_start]**Average Age:** Approximately 44 years old[cite: 14].
* [cite_start]**Top Category:** Clothing, with 1,737 purchases[cite: 14].
* [cite_start]**Average Spend:** $59.76 per transaction[cite: 14].

---

## 🛠️ Technical Workflow

### 1. Data Engineering (Python)
* [cite_start]**Cleaning:** Addressed 37 missing values in the `Review Rating` column using category-specific median imputation[cite: 9, 17].
* [cite_start]**Standardization:** Renamed columns to `snake_case` for improved readability and documentation[cite: 18].
* [cite_start]**Feature Engineering:** Generated new metrics including `age_group` bins and `purchase_frequency_days`[cite: 20, 21].
* [cite_start]**Integration:** Established a connection between Python and **MySQL** to load the processed data for structured querying[cite: 23].

### 2. Business Intelligence (SQL)
Structured queries were utilized to answer high-impact business questions:
* [cite_start]**Revenue Analysis:** Male customers contributed **$157,890**, while female customers contributed **$75,191**[cite: 32, 35].
* [cite_start]**Subscription Impact:** Non-subscribers represent the majority of the revenue ($170,436) compared to subscribers ($62,645)[cite: 44].
* [cite_start]**Discount Dependency:** Identified products like **Hats (50.00%)** and **Sneakers (49.66%)** as having the highest percentage of discounted purchases[cite: 46].
* [cite_start]**Customer Segmentation:** Classified the user base into **Loyal (3,116)**, **Returning (701)**, and **New (83)** segments[cite: 49].

### 3. Visualization (Power BI)
[cite_start]An interactive dashboard was developed to monitor real-time KPIs[cite: 71, 72]:
* [cite_start]**Customer KPIs:** Tracking total customer counts, average purchase amounts ($58.46), and average review ratings (3.82)[cite: 81, 86, 92].
* [cite_start]**Demographic Revenue:** Tracking total revenue contribution by age groups: **Young Adult ($62,143)**, **Middle-aged ($59,197)**, **Adult ($55,978)**, and **Senior ($55,763)**[cite: 60, 63, 66, 69].

---

## 📈 Key Insights & Findings
* [cite_start]**Shipping Influence:** Express shipping users have a slightly higher average spend (**$60.48**) compared to Standard shipping users (**$58.46**)[cite: 42].
* [cite_start]**Top Rated Products:** Gloves (3.86), Sandals (3.84), and Boots (3.82) lead the inventory in customer satisfaction[cite: 40].
* [cite_start]**Subscription Rate:** Currently, only **26.76%** of customers are subscribers[cite: 85].

---

## 💡 Strategic Recommendations
* [cite_start]**Incentivize Subscriptions:** Promote exclusive benefits to convert the 73.24% of non-subscribers[cite: 98, 128].
* [cite_start]**Loyalty Rewards:** Implement programs specifically targeting "Returning" customers to move them into the "Loyal" bracket[cite: 129].
* [cite_start]**Targeted Marketing:** Focus high-value campaigns on the **Young Adult** segment, as they are the highest revenue contributors[cite: 59, 60, 133].
* [cite_start]**Optimized Discounting:** Evaluate margins on "Discount-Dependent" items like Hats and Sneakers to balance sales boosts with margin control[cite: 46, 130].

---
*Developed by Harshit Raj.*
