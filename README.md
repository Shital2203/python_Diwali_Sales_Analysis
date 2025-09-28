# 🪔 Diwali Sales Analysis

This project explores **customer purchasing behavior during the Diwali festival season**.  
The analysis uncovers trends in demographics, geography, and product preferences to help businesses improve their sales and marketing strategies.

---

## 📂 Project Structure
- `Diwali_Sales_Analysis.ipynb` → Main analysis notebook  
- `Diwali Sales Data.csv` → Dataset used for analysis (not shared publicly if confidential)  
- `README.md` → Project documentation  

---

## ✅ Steps Performed

### 1. Import Libraries
- Loaded Python libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`.

### 2. Load Dataset

- Imported `Diwali Sales Data.csv` into a pandas DataFrame.
- Checked data shape, head, and column types.

### 3. Data Cleaning
- Dropped **null values**.  
- Removed irrelevant columns (`Status`, `unnamed1`).  
- Converted **Amount** column to integer type.  
- Reset DataFrame index.  

### 4. Exploratory Data Analysis (EDA)

#### Demographic Analysis
- **Gender** → Females purchased more and spent more.  
- **Age Groups** → Most buyers were **26–35 years old**, mainly females.  
- **Marital Status** → Married women contributed the highest to sales.  
- **Occupation** → Top spenders were from **IT, Healthcare, and Aviation sectors**.  

#### Geographic Analysis
- **State-wise** → Top states: **Uttar Pradesh, Maharashtra, Karnataka**.  

#### Product Analysis
- **Product Categories** → Electronics, Clothing, and Food were top sellers.  
- **Top Products** → Identified top 10 products by Orders and Amount.  

### 5. Correlation Analysis
- Checked correlations between `Orders`, `Amount`, `Age`, etc.  
- Found **no strong correlations**, showing categorical insights are more important.  

### 6. Customer Segmentation (FM by State)
- Aggregated **Frequency (Orders)** and **Monetary (Amount)** per state.  
- Visualized states by FM values.  
- Used **K-Means clustering** to group states into:  
  - High frequency & high spend (loyal markets)  
  - High frequency but low spend  
  - Low frequency but high spend  

---

## 📊 Key Insights
- **Women (26–35 yrs, married)** are the biggest buyers.  
- **Uttar Pradesh, Maharashtra, Karnataka** are top performing states.  
- **IT, Healthcare, Aviation professionals** spend the most.  
- **Electronics and Clothing** dominate sales.  
- State-wise FM analysis reveals **loyal and high-value regions**.  

---

## 🚀 Tech Stack
- Python  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn (for clustering)  

---

## 🎯 Future Improvements
- Add **Recency (RFM)** if transaction dates become available.  
- Build **predictive models** for sales forecasting.  
- Create an **interactive dashboard** in Power BI or Tableau.  

---
