# Project-3-
# 🏡 Real Estate Price Analysis (EDA Project)

This project performs Exploratory Data Analysis (EDA) on the Ames Housing dataset to identify 
the key factors influencing house prices. The goal is to uncover important relationships, trends, 
and patterns that help understand how property size, quality, amenities, and market conditions 
affect home valuation.

---

## 📌 Project Objectives
- Analyze house price distribution and feature patterns  
- Identify strongest correlated variables  
- Study size impact: GrLivArea, TotalSF, Bedrooms, Bathrooms  
- Explore market trends across years (YrSold)  
- Examine customer preferences through amenities like Garage & Pool  
- Apply feature engineering for deeper insights  
- Summarize actionable insights for pricing strategy  

---

## 🗂 Dataset
- **Rows:** 1460  
- **Columns:** 80  
- **Target Variable:** `SalePrice`  
- Contains information on:
  - Living area  
  - Basement size  
  - House quality  
  - Bedrooms, bathrooms  
  - Garage, pool  
  - Year sold  

---

## 🧹 Data Cleaning Performed
- Removed duplicates  
- Treated missing values  
- Dropped sparse columns (e.g., Alley)  
- Outlier check (4000+ sqft luxury homes retained)  
- Corrected data types  

---

## 📊 Univariate Analysis
Key distributions examined:
- SalePrice  
- GrLivArea  
- OverallQual  
- LotShape  

---

## 🔗 Bivariate Analysis
Relationship studied:
- GrLivArea vs SalePrice  
- OverallQual vs SalePrice  
- LotShape vs SalePrice  

---

## 🔥 Feature Engineering
Created new features:
- `TotalSF = TotalBsmtSF + GrLivArea`
- `PricePerSF = SalePrice / GrLivArea`
- `HouseAge = YrSold - YearBuilt`

---

## 📈 Size Impact
Analyzed:
- Bedrooms vs SalePrice  
- Bathrooms vs SalePrice  
- TotalSF vs SalePrice  

---

## 📆 Market Trends
- Year-wise average SalePrice trends visualized  
- Market stability observed  

---

## 🏊 Amenities Impact
Examined:
- GarageArea vs SalePrice  
- PoolArea vs SalePrice  

---

## 🤖 AI Integration
AI helped with:
- Choosing professional color palettes  
- Visual styling recommendations  
- Identifying key correlated features  
- Structuring analysis & insights  

---

## 📝 Final Insights
- Quality (OverallQual) is the strongest price driver  
- TotalSF & GrLivArea highly influence SalePrice  
- Amenities add premium value  
- Bedrooms count is a weak predictor  
- Market trends stable across years  

---

## 📎 Files Included
- `housing-eda.ipynb` – Full analysis
- `data/` – Dataset
- `images/` – Visualizations
- `report/documentation.pdf` – Project report

---

## 👤 Author
**Ankit**  
EDA & Data Analysis Project | Python | Seaborn | Plotly  

