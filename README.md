# 🇮🇳 India Petroleum Consumption Analysis Dashboard

## 📌 Project Overview

This project is an interactive **Power BI Dashboard** developed to analyze India's petroleum consumption trends over multiple financial years. The dashboard provides insights into crude oil prices, fuel consumption patterns, and state-wise petroleum usage through interactive visualizations.

It enables users to explore data dynamically using Financial Year and Month slicers, making it easier to identify consumption trends and support data-driven decision-making.

---

# 📊 Dashboard Preview

<img width="1307" height="750" alt="Dashboard" src="https://github.com/user-attachments/assets/73c67c7f-f934-464a-81a2-88dce532e77f" />


---

# 🎯 Objectives

- Analyze India's petroleum consumption trends.
- Compare Motor Spirit (MS) and High-Speed Diesel (HSD) consumption.
- Study monthly fluctuations in crude oil prices.
- Identify top fuel-consuming states.
- Build an interactive Business Intelligence dashboard using Power BI.

---

# 📂 Dataset

The project uses publicly available petroleum datasets covering the period:

**Financial Year:** **1998–99 to 2025–26**

### Data Sources

- Historical Crude Oil Prices
- Monthly Petroleum Consumption
- State-wise Petroleum Consumption

---

# 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query (ETL)
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Data Modeling
- GitHub

---

# 🔄 ETL (Extract, Transform, Load)

The raw datasets were cleaned and transformed using **Power Query**.

The transformation process included:

- Removing unnecessary rows and columns
- Promoting headers
- Changing data types
- Removing null values
- Standardizing Financial Year format
- Creating Month Number column
- Creating YearMonth column
- Appending multiple yearly datasets
- Creating calculated columns
- Loading clean data into Power BI

---

# 🏗 Data Model

The dashboard follows a **Star Schema** consisting of:

## Dimension Tables

- Dim_Date
- Dim_FinancialYear

## Fact Tables

- Fuel_Consumption
- Crude_Oil
- Statewise_Consumption

Relationships were created between dimension and fact tables to enable dynamic filtering across all visuals.

---

# 📈 Dashboard Features

## Executive KPI Cards

- Average Crude Oil Price
- Total Fuel Consumption
- Total MS Consumption
- Total HSD Consumption

---

## Interactive Filters

- Financial Year
- Month

---

## Visualizations

- Monthly Crude Oil Price Trend (Line Chart)
- Monthly Fuel Consumption (MS vs HSD) (Clustered Column Chart)
- Fuel Consumption by Fuel Type (Donut Chart)
- Petroleum Consumption by State (Bubble Map)
- Top Fuel Consuming States (Horizontal Bar Chart)

---

# 📊 KPI Explanation

## Average Crude Oil Price

Displays the average international crude oil price.

**Unit:** USD per Barrel (USD/bbl)

---

## Total Fuel Consumption

Represents the total petroleum products consumed during the selected period.

**Unit:** Thousand Metric Tonnes (000 MT)

---

## Total MS Consumption

Represents the total consumption of Motor Spirit (Petrol).

**Unit:** Thousand Metric Tonnes (000 MT)

---

## Total HSD Consumption

Represents the total consumption of High-Speed Diesel (HSD).

**Unit:** Thousand Metric Tonnes (000 MT)

---

# 💡 Key Insights

- Analyze petroleum consumption trends across financial years.
- Compare petrol (MS) and diesel (HSD) consumption patterns.
- Monitor fluctuations in crude oil prices.
- Identify states with the highest petroleum consumption.
- Explore monthly consumption trends using interactive slicers.

---

# 📁 Repository Structure

```text
India_Petroleum_Consumption_Analysis_Dashboard
│
├── README.md
├── India_Petroleum_Consumption_Analysis.pbix
├── Dashboard.pdf
├── Images
│   └── Dashboard.png
├── Dataset
│   ├── Crude_Oil.xlsx
│   ├── Fuel_Consumption.xlsx
│   └── Statewise_Consumption.xlsx
└── LICENSE
```

---

# 🚀 Skills Demonstrated

- Data Cleaning
- ETL using Power Query
- Data Modeling
- DAX Measures
- Interactive Dashboard Design
- Business Intelligence
- Data Visualization
- Analytical Thinking
- Power BI Reporting

---

# 🔮 Future Enhancements

- Forecast future petroleum consumption
- Year-over-Year (YoY) Growth Analysis
- Drill-through report pages
- Import and Export analysis
- Additional petroleum product categories
- Advanced DAX measures and KPIs

---

# 👩‍💻 Author

**Raksha Maurya**

MBA (Finance)

**Skills**

- Power BI
- Advanced Excel
- SQL
- Python
- Data Analytics
- Business Intelligence

---

# ⭐ If you found this project useful

If you like this project, consider giving it a **⭐ Star** on GitHub!

---

# 📜 License

This project is intended for educational and portfolio purposes.
