
# 📊 AtliQ Hospitality Data Analysis

This project analyzes booking and revenue data from the AtliQ hotel chain. The objective is to extract business insights using Python by exploring, cleaning, and analyzing hospitality datasets. This project is part of a data analytics initiative and simulates real-world hotel management scenarios.

---

## 🔍 Project Overview

- **Goal**: To analyze hotel booking trends, identify overbooking patterns, evaluate room performance, and optimize revenue.
- **Data Sources**: CSV files representing dimensional and fact tables:
  - `dim_date.csv`
  - `dim_hotels.csv`
  - `dim_rooms.csv`
  - `fact_bookings.csv`
  - `fact_aggregated_bookings.csv`

---

## 📂 Steps Performed

1. **Data Import & Exploration**  
   Loaded all datasets and explored structure, value distributions, and relationships between dimensions and facts.

2. **Data Cleaning**  
   - Removed invalid guest entries (e.g., negative guest counts).
   - Filtered outliers in revenue values.
   - Standardized room types and hotel identifiers.

3. **Data Analysis & Insights**  
   - Identified properties with highest capacity.
   - Detected overbooking instances where guests exceeded capacity.
   - Analyzed booking volume trends per room type and hotel.

---

## 📌 Key Insights

- Certain hotels consistently exceed their guest capacity — flagging potential overbooking issues.
- RT4 room types (presidential suites) generate significantly higher revenue but are rare.
- Seasonal booking trends were evident when analyzing by date and capacity.

---

## 🛠️ Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Data Cleaning & Transformation**
- **Exploratory Data Analysis**

---

## 🧠 Skills Demonstrated

- Relational data analysis
- Outlier detection and treatment
- Groupby aggregation & business logic filtering
- Visualization for decision-making

---

## 🚀 How to Use

1. Clone this repository.
2. Open the notebook `atliq_hospitality_analysis.ipynb` in Jupyter or VS Code.
3. Run the notebook step-by-step to explore the analysis.

---

## 👤 Author

**Meet Patel**  
📧 [LinkedIn Profile](https://www.linkedin.com/in/patelmeetde)  
🔧 Data Analytics | Python | Power BI | SQL
