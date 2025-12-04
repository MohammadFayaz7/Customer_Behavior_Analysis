# 👨🏻‍💻 Customer Shopping Behavior Analysis – Data Analyst Portfolio Project

This project represents a **complete end-to-end industry-grade data analytics workflow**, designed to showcase practical skills used by professional data analysts in real-world business environments.

The project covers everything from:
- Raw data cleaning & preparation  
- SQL business analysis  
- Interactive dashboard building  
- Final reporting & business recommendations  

---

## ✅ This Project is Perfect For

- 📊 **Aspiring Data Analysts** building strong portfolio projects  
- 📚 **Students & learners** mastering Python, SQL & Power BI  
- 💼 **Job applicants** preparing for Data Analyst / Business Analyst roles

---

## 📌 Project Overview

The aim of this project is to simulate a **corporate retail analytics case study** where customer shopping transaction data is used to generate **actionable business insights**:

✅ **Data Cleaning & EDA (Python)**  
- Handled missing values  
- Standardized columns  
- Created new business-useful features  
- Prepared dataset for database storage

✅ **SQL Business Analysis (PostgreSQL)**  
- Executed structured business queries  
- Analyzed customer segments, revenue patterns, loyalty, discounts and shipping behavior

✅ **Dashboarding (Power BI)**  
- Built a fully interactive analytics dashboard
- Visualized customer trends and KPIs for stakeholders

✅ **Reporting & Recommendations**  
- Compiled key findings  
- Generated practical marketing and sales strategies

---

## 🗂 Dataset Overview

- **Records:** 3,900 retail transactions  
- **Attributes:** 18 columns

### Key Data Categories

| Data Type | Features |
|-----------|-----------|
| 👥 Demographics | Age, Gender, Location, Subscription Status |
| 🛒 Purchases | Item, Category, Season, Size, Color, Purchase Amount |
| 📊 Behavior | Discounts, Purchase Frequency, Shipping Type |
| ⭐ Feedback | Review Ratings |

⚠ Missing values in **Review Ratings** were handled using median imputation by product category.

---

## 🔍 Python – Data Preparation & EDA

The notebook includes:

- Data import & exploration  
- Missing value treatment  
- Feature engineering:
  - `age_group`
  - `purchase_frequency_days`
- Column standardization (snake_case convention)
- Redundancy detection & column removal
- Loading cleaned dataset into **PostgreSQL database**

---

## 🗄 SQL – Business Analysis

Business intelligence queries answered:

- 💰 Revenue by **gender**
- ⭐ **Top-rated products**
- 🚚 Express vs Standard shipping comparison
- 👥 Subscribers vs Non-subscribers analysis
- 🎯 **High-value discount customers**
- 🔖 Discount-dependent product identification
- 🧩 Customer segmentation:
  - New
  - Returning
  - Loyal
- 🥇 **Top 3 products per category**
- 🔁 Subscription behavior of repeat buyers
- 👶🧓 Revenue by age group

---

## 📊 Power BI Dashboard

The Power BI dashboard presents key metrics in an easy-to-interpret visual format:

✅ Customer demographics revenue breakdown  
✅ Sales by product category  
✅ Subscription contribution analysis  
✅ Seasonal trends  
✅ Discount and shipping behavior patterns


---

## 🛠️ How to Use This Project

### 1️⃣ Clone Repository
```bash
git clone https://github.com/MohammadFayaz7/Customer-Shopping-Behavior-Analysis.git
cd Customer-Shopping-Behavior-Analysis
```

----
### 2️⃣ Run Python Notebook

### Open and execute:
```bash
Customer_Shopping_Behavior_Analysis.ipynb
```

---

### Notebook includes:

Data loading

Cleaning

EDA

PostgreSQL connection & data insert

### 3️⃣ SQL Analysis

1. Create PostgreSQL database

2. Load dataset via Python notebook

3. Execute SQL queries to answer business questions

### 4️⃣ Power BI Dashboard

1. Open:
```bash
customer_behavior_dashboard.pbix
```

2. Connect to your SQL database

3. Explore the interactive visuals

### 5️⃣ Documentation

1. Review Business insight report

2. Prepare Presentation slides for stakeholders
