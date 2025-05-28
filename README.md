# 🚀 Customer Churn Analysis

Welcome! This project provides a comprehensive solution for understanding and predicting customer churn using a blend of SQL, Power BI, and machine learning. From raw data to actionable insights, every step is included: cleaning, EDA, modeling, and interactive dashboards.

---

## 📋 Table of Contents

- [📖 Overview](#-overview)
- [🔄 Workflow](#-workflow)
- [📁 Project Structure](#-project-structure)
- [⚙️ Setup & Usage](#️-setup--usage)
- [📊 Results & Visualizations](#-results--visualizations)
- [🛠️ Technologies Used](#️-technologies-used)
- [🤝 Contributing](#-contributing)
- [📝 License](#-license)

---

## 📖 Overview

**Customer churn analysis** helps businesses identify why customers leave and predict who is at risk. By acting on these insights, companies can significantly improve retention and profitability.

---

## 🔄 Workflow

1. **Data Acquisition & Cleaning**  
   🗃️ Data imported and cleaned in **SQL**  
   🏷️ Created two key SQL views:  
   &nbsp;&nbsp;&nbsp;• `churndata` – Customers who have churned  
   &nbsp;&nbsp;&nbsp;• `joinersdata` – Customers who have joined

2. **Business Intelligence Visualization**  
   📈 Connected SQL database to **Power BI**  
   📊 Built summary dashboards to visualize churn metrics

3. **Exploratory Data Analysis & Modeling**  
   🧐 Exported views to **Excel/CSV** for EDA  
   🤖 Developed a **Random Forest** churn prediction model in Python  
   💾 Exported results to CSV

4. **Final Reporting**  
   🖥️ Visualized model results and insights in **Power BI**

---

## 📁 Project Structure

```
.
├── data/         # CSV files for EDA and modeling
├── notebooks/    # (Optional) Jupyter notebooks/scripts for EDA/modeling
├── powerbi/      # Power BI dashboards and exports
├── sql/          # SQL scripts for data prep and views
├── README.md
└── ...
```

---

## ⚙️ Setup & Usage

1. **SQL Data Preparation**
   - Run the SQL scripts to clean data and create `churndata` and `joinersdata` views.

2. **Power BI Dashboards**
   - Connect Power BI to your SQL database
   - Import views and explore interactive dashboards

3. **EDA & Modeling**
   - Export data to CSV
   - Use Python (see `notebooks/`) for EDA and churn prediction modeling
   - Export predictions to CSV

4. **Visualization**
   - Import results CSV into Power BI for final visual reports

---

## 📊 Results & Visualizations

- 🚦 Interactive churn summary dashboards (Power BI)
- 🔍 EDA findings and feature importances
- 🎯 Predictive insights on customer churn

---

## 🛠️ Technologies Used

- **SQL** – Data cleaning and preparation
- **Power BI** – Visualization and reporting
- **Excel / CSV** – Data transfer and EDA
- **Python (Random Forest)** – Churn prediction modeling

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to open an issue or submit a pull request.

---

## 📝 License

Distributed under the MIT License.
