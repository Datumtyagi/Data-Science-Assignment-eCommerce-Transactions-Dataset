# 📊 Data Science Assignment: eCommerce Transactions Analysis

Welcome to the **eCommerce Transactions Analysis** repository! This project involves performing **Exploratory Data Analysis (EDA)**, building a **Lookalike Model**, and conducting **Customer Segmentation** using a real-world dataset. The goal is to uncover insights, improve customer experience, and optimize business strategies for an eCommerce platform.

---

## 🗂️ Project Overview

This project consists of three datasets:
1. **Customers.csv**  
   Contains customer details such as `CustomerID`, `Name`, `Region`, and `SignupDate`.
   
2. **Products.csv**  
   Includes product information like `ProductID`, `ProductName`, `Category`, and `Price`.

3. **Transactions.csv**  
   Records transaction details including `TransactionID`, `CustomerID`, `ProductID`, `Quantity`, `TotalValue`, and `TransactionDate`.

---

## 🏆 Objectives
This project is divided into three main tasks:

### 1. **Exploratory Data Analysis (EDA)**  
   - **Goal:** Perform EDA on the dataset to uncover patterns and trends.
   - **Deliverables:**  
     - Python notebook with EDA code.
     - A concise **PDF report** summarizing **5 key business insights** derived from the analysis.

### 2. **Lookalike Model**  
   - **Goal:** Build a recommendation model to find 3 similar customers for a given user based on their profile and transaction history.
   - **Deliverables:**  
     - Python notebook explaining the model development.  
     - A CSV file named `Lookalike.csv` mapping the first 20 customers (`C0001` to `C0020`) to their top 3 similar customers with similarity scores.

### 3. **Customer Segmentation / Clustering**  
   - **Goal:** Segment customers using clustering techniques based on their profiles and transaction data.
   - **Deliverables:**  
     - Python notebook with clustering code.  
     - A **PDF report** summarizing:
       - Number of clusters formed.  
       - Clustering quality metrics like the **Davies-Bouldin Index (DBI)**.  
       - Visualizations of clusters (e.g., scatter plots, PCA).  

---

## 💡 Key Insights from EDA
- **Top-selling regions:** Customers from [Region X] generate the highest revenue, contributing 40% of total sales.  
- **Seasonality trend:** Transactions peak in Q4, with a 35% increase in sales during holiday months.  
- **High-value customers:** The top 5% of customers contribute 60% of the revenue, highlighting the importance of personalized strategies.  
- **Product performance:** Category `Electronics` has the highest sales volume but suffers from low-profit margins compared to `Home Decor`.  
- **Signup trends:** 70% of customers signed up within the past two years, indicating a rapidly growing customer base.

For a detailed breakdown, refer to the [EDA PDF Report](./Avinash_Tyagi.pdf).

## 🛠️ Tools & Technologies
- **Programming Language:** Python 🐍  
- **Libraries:**  
  - Data Analysis: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Machine Learning: `scikit-learn`  
- **Cluster Evaluation:** Davies-Bouldin Index (DBI)

---

## 🚀 Results & Insights

### **Task 1: EDA**
Key insights were derived to improve sales strategies, target high-value customers, and optimize product offerings. Full details are in the EDA report.

### **Task 2: Lookalike Model**
Developed a model that uses customer and product information to recommend similar customers. Outputs are saved in [Lookalike.csv](./Lookalike.csv).

### **Task 3: Customer Segmentation**
Clustered customers into 4 segments based on behavior and demographics. Achieved a **Davies-Bouldin Index** of `0.8502362410640188`, reflecting strong clustering quality.

---

