# 🏦 Bank Customer Churn Analysis

This project explores a bank's customer data to uncover insights about **why customers churn** (leave the bank). The goal is to identify key factors that influence churn and help the bank improve its **customer retention strategies**.

---

## 📌 Objective

Identify key drivers of customer churn and provide actionable insights that can help reduce churn and improve customer loyalty.

---

## 📊 Dataset Overview
### [Bank Churn Data](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn)



The dataset includes the following features:

- **Demographics**: Age, Gender, Geography
- **Banking Info**: Credit Score, Balance, Tenure
- **Behavioral Data**: Number of Products, Has Credit Card, Active Member
- **Satisfaction Level**
- **Target Variable**: `Exited` (1 = Churned, 0 = Retained)

---

## 🧾 Bank Churn Analysis – Summary

- The churn analysis reveals that over **20% of customers exited the bank**, with **customer satisfaction** emerging as a significant factor. A large proportion of churned customers reported **low satisfaction**, suggesting experience quality plays a central role in retention.

- **Geographic trends** show that while **France** holds the **largest customer base** and **lowest churn rate**, **Germany** experiences the **highest churn** at 32.4%. **Age also plays a role** — over **50% of churned customers fall in the 50–60 age group**, whereas **younger customers are more likely to stay**.

- Gender-wise, **female customers churn more (25%)** despite being fewer in number, and churn behavior varies by **tenure: female churners typically had longer tenures**, while male **churners tended to leave early**.

- In terms of products, churn was highest among customers with **3 or more products**, especially **100% churn among those with 4 products**, indicating potential dissatisfaction or overcomplexity. **Diamond card holders** showed a slightly higher churn rate and correlated with **lower satisfaction levels**.

- A significant insight is that **inactivity is strongly linked to churn** — **over 60% of churned customers were inactive**. Lastly, while **70% of churned customers had credit cards**, ownership alone was **not a protective factor** against churn.


*These findings emphasize the importance of improving **customer satisfaction**, **engagement**, and **product alignment** to reduce churn and boost long-term retention.*



---

## 🧠 Key Insights

- Over **20% of customers churned**, mostly due to **low satisfaction** and **inactivity**.
- **Germany** had the highest churn rate (**32.4%**).
- Customers aged **50–60** were the most likely to churn.
- **Female customers** had a **higher churn rate (25%)** compared to males (16.5%).
- **Inactive users made up over 60% of churned customers**.
- Customers with **3 or more products** had significantly **higher churn rates**.
- **Diamond card holders** showed a slight correlation with dissatisfaction.

---

## 🛠 Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---
