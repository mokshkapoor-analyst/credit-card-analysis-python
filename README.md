# 💳 Credit Card Customer Behavior & Profit Analysis (Python)

A comprehensive Python-based analytics project focused on analyzing customer spending behavior, repayment trends, and profitability for a bank’s credit card operations. This project transforms raw transactional data into actionable business insights using EDA, visualization, and profitability analysis.

---

## 📊 Project Preview

### 🎥 Analytics Report Carousel / PDF Demo

<a href="https://www.linkedin.com/posts/moksh-kapoor-618495322_credit-card-analysis-python-project-02-ugcPost-7457045248188489728-gGS2?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFGVzjQBQzKnpNzkuOZayyyvYW4FkHnrf28" target="_blank">
  <img src="Images/Credit%20Card%20Case%20Study.jpg" alt="Credit Card Analytics" width="100%">
</a>

---

## 📁 Dataset Overview

This project analyzes credit card customer data for PSPD Bank, which serves customers across Gold, Silver, and Platinum card categories.

The dataset was created by merging multiple tables containing:

- Customer demographics
- Credit card information
- Spending transactions
- Repayment transactions
- Credit limits
- Transaction dates
- Spending categories

The final merged dataset (`merged_data`) was used for complete analysis and profitability evaluation.

---

## 🎯 Business Problem & Analysis

The main objective of this project is to understand:

- How customers spend and repay using credit cards
- Which customer segments generate the highest revenue
- Which cities and card types drive maximum spending
- How repayment behavior impacts bank profitability
- Identification of high-value and risky customers
- Seasonal and monthly spending trends

The analysis helps banks improve:

- Customer targeting
- Profitability strategies
- Risk management
- Credit card marketing campaigns

---

## 🧹 Data Preparation & Cleaning

Data cleaning and preprocessing were performed using Python.

### ✔ Data Cleaning

- Replaced invalid age values (`<18`) using mean age
- Capped spending exceeding credit limits
- Adjusted repayment values exceeding limits
- Handled missing values and ensured consistency

### ✔ Data Merging

- Combined customer acquisition, spend, and repayment datasets
- Used joins to retain complete transaction history
- Created a final unified dataset: `merged_data`

### ✔ Exploratory Data Analysis (EDA)

- Distribution analysis using histograms
- Category analysis using bar charts
- Outlier detection using boxplots
- Monthly spending & repayment trend analysis
- Segment-wise profitability analysis

---

## 📈 KPI Overview

| KPI | Value |
|------|------|
| Total Customers | 100 |
| Total Spend | ₹57.48 Cr |
| Total Repayment | ₹63.45 Cr |
| Net Amount | ₹5.97 Cr |
| Total Profit | ₹19.47 Lakh |
| Average Age | ~45 Years |
| Avg Monthly Spend | ₹1.92 Cr |
| Avg Monthly Repayment | ₹2.15 Cr |

---

## 📊 Key Insights & Findings

### 🏙 Top Spending Cities

- Bangalore leads in spending
- Cochin, Calcutta, and Bombay also contribute significantly
- Indicates concentration of premium customers in major urban regions

### 💳 Card Type Analysis

- Gold Cards generate the highest revenue
- Platinum Cards contribute strong premium spending
- Silver Cards show steady but lower spending behavior

### 👥 Customer Segment Insights

- Adult customers contribute the majority of spending
- A small number of customers contribute significantly to repayments
- High spending does not always result in high profitability

### 📅 Time-Based Trends

- Spending and repayment fluctuate monthly
- Strong seasonal spending behavior observed
- Gold & Platinum users spend more during Jan–June
- Silver users show increased spending during Oct–Dec festive periods

### 🛍 Spending Category Insights

Highest spending categories include:

- Camera
- Petro
- Food

These categories dominate transaction volume and revenue generation.

### 💰 Profitability Insights

- Profitability depends heavily on repayment behavior
- Repayment exceeding spend drives profit generation
- Monthly profit trends are highly volatile

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Exploratory Data Analysis (EDA)
- Data Cleaning & Transformation
- Data Visualization

---

## 📌 Key Learnings

- Customer spending alone does not guarantee profitability
- Repayment behavior is critical for financial performance
- Seasonal trends can influence spending significantly
- Data visualization helps identify high-value customer segments
- Python is powerful for financial analytics and behavioral analysis

---

## ⚡ Recommendations

- Focus marketing campaigns on high-value adult customers
- Promote profitable card categories like Gold Cards
- Expand targeting in underutilized cities like Delhi and Patna
- Improve repayment monitoring for better profitability
- Leverage seasonal spending patterns for promotional campaigns

---

## 📂 Repository Structure

```bash
credit-card-customer-behavior-analysis/
├── Images/
│ ├── Credit Card Analytics Preview.png
├── notebooks/
│ └── credit_card_analysis.ipynb
└── README.md
```

---

## 👤 Author

**Moksh Kapoor**  
Aspiring Data Analyst  

<p>
  🔗 <strong>LinkedIn:</strong> 
  <a href="[https://www.linkedin.com/in/moksh-kapoor-618495322](https://www.linkedin.com/posts/moksh-kapoor-618495322_credit-card-analysis-python-project-02-ugcPost-7457045248188489728-gGS2?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFGVzjQBQzKnpNzkuOZayyyvYW4FkHnrf28)/" target="_blank">
    Visit My LinkedIn Profile
  </a>
</p>

📢 You can also check this project on my LinkedIn post:

<a href="#" target="_blank">
View Post 🚀
</a>
