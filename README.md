# 🏠 Sydney House Prices Analysis

* This project explores housing prices in Sydney using a public dataset.
The goal is to perform an **Exploratory Data Analysis (EDA)** to understand property price patterns, trends over time, and relationships between property characteristics.

---

## 📅 Code and Resources Used 
**Python Version:** 3.7  
**Packages:** `pandas` for EDA, `matplotlib` and `seaborn` for data visualization.

---

## 📊 Dataset

**Columns included:**
- `Date`: Sale date of the property (converted to datetime format).
- `Id`: Unique identifier for each record.
- `suburb`: Suburb where the property is located.
- `postalCode`: Postal code of the property.
- `sellPrice`: Selling price in Australian dollars.
- `bed`: Number of bedrooms.
- `car`: Number of parking spaces.
- `propType`: Type of property (e.g., House, Unit, Townhouse).

---

## 🔍 Main Analyses

- Data type conversion and null value analysis.  
- Summary statistics and outlier detection.  
- Top and bottom 10 properties by `sellPrice`.  
- Average price analysis by suburb and property type.  
- Yearly price trends using `sns.pointplot`.  
- Validation of inconsistent or unrealistic values (e.g., price = 1).

---

*Author: **Melisa Di Giacomo***  
*Project created as part of the Data Science Diploma program at ICARO.*