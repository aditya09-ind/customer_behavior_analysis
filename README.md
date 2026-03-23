# 📊 Customer Shopping Behavior Analysis

## 🔍 Overview
This project analyzes customer shopping behavior to uncover insights that can help businesses improve sales, customer engagement, and decision-making.

The analysis is based on transactional data and follows a complete data analytics pipeline — from data cleaning and exploration to SQL analysis, dashboard creation, and reporting.

The key objective is to answer:
**“How can customer data be used to identify trends and optimize business strategies?”** :contentReference[oaicite:0]{index=0}

---

## 📁 Dataset
- Total Records: **3,900 transactions**
- Features: **18 columns**
- Includes:
  - Customer demographics (age, gender, location, subscription status)
  - Purchase details (category, amount, season, item)
  - Behavioral data (discounts, frequency, ratings, shipping type)

- Missing values:
  - 37 missing entries in the **review rating** column (handled during cleaning) :contentReference[oaicite:1]{index=1}

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SQL** (PostgreSQL / MySQL / SQL Server)
- **Power BI** (Dashboard & Visualization)
- **Jupyter Notebook**
- **Gamma** (Presentation)

---

## ⚙️ Project Steps

### 1. Data Loading (Python)
- Loaded dataset using Pandas
- Performed initial inspection using `.info()` and `.describe()`

### 2. Data Cleaning
- Handled missing values (review ratings)
- Removed inconsistencies and duplicates
- Standardized column names
- Created new features:
  - Age groups
  - Purchase frequency metrics

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer demographics and behavior
- Identified trends and correlations using visualizations

### 4. SQL Analysis
- Loaded cleaned data into database
- Executed business queries such as:
  - Revenue by gender
  - Customer segmentation (New, Returning, Loyal)
  - Top products by rating
  - Discount impact analysis
  - Revenue contribution by age group :contentReference[oaicite:2]{index=2}

### 5. Dashboard Creation
- Built an interactive **Power BI dashboard**
- Visualized:
  - Customer distribution
  - Revenue trends
  - Category-wise sales
  - Subscription insights

### 6. Reporting & Presentation
- Created a structured report summarizing insights
- Designed a presentation using Gamma for stakeholders

---

## 📊 Dashboard
The Power BI dashboard provides an interactive view of key business metrics:

- Total Customers: **3.9K**
- Average Purchase: **$59.76**
- Average Rating: **3.75**
- Filters: Subscription status, category, gender, shipping type

Includes:
- Revenue by category
- Sales by age group
- Subscription distribution

*(Refer to dashboard file in the repository)* :contentReference[oaicite:3]{index=3}

---

## 📈 Results & Insights
- Majority of customers fall into the **loyal segment**
- **Discounts significantly influence purchases**
- **Top-performing products** drive higher engagement
- **Young adults contribute the highest revenue**
- Subscription users show similar spending but lower total revenue

Key recommendations:
- Improve subscription benefits
- Optimize discount strategies
- Focus on high-performing products
- Target high-revenue customer segments :contentReference[oaicite:4]{index=4}

---

## ▶️ How to Run

### 1. Clone Repository
```bash
git clone https://github.com/aditya09-ind/customer_behavior_analysis.git
cd customer_behavior_analysis
