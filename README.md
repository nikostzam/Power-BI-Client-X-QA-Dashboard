# 📊 Power BI Client X QA Dashboard  
### Comprehensive Quality Analytics & Performance Insights  

---

## 🧭 Overview  

This project delivers a **Power BI dashboard** that provides **end-to-end visibility into QA (Quality Assurance)** performance for *Client X*.  
The solution integrates **multiple data sources**, automates **data cleaning and modeling**, and visualizes insights through **interactive reports and advanced visual analytics**.  

💡 The goal: to help decision-makers identify trends, improve agent performance, and enhance service quality through data-driven insights.  

---

## ⚙️ Project Scope  

The dashboard consolidates **11 separate data exports** from both **client systems** and **internal CRM tools** into a unified analytical model.  
Each dataset underwent cleaning, normalization, and transformation before being integrated into the Power BI semantic layer.  

---

## 🧩 Data Engineering & Modeling  

### 🧼 Data Cleaning  
- Conducted with **Python (Pandas)** for efficiency and reproducibility.  
- Steps included:
  - Handling missing values and duplicates.  
  - Standardizing date/time and categorical formats.  
  - Normalizing KPIs across multiple data sources.  
  - Creating calculated fields for QA performance metrics.  

### 🧱 Data Modeling  
- Built a **Star Schema** in SQL and Power BI combining:
  - **Fact Tables** (QA Scores, Evaluations, Tickets).  
  - **Dimension Tables** (Agents, Teams, Dates, Categories).  
- Relationships established using **1-to-many** and **many-to-one** cardinality.  
- Applied **data validation** rules to ensure consistency and referential integrity.  

---

## 📈 Data Visualization  

Power BI visuals are designed for **clarity, interactivity, and performance benchmarking**.  
The following visual elements and libraries were used during analysis and prototyping:  

### 🧠 In Python (before PBI integration):  
- Created exploratory graphs using **Seaborn** and **Matplotlib**.  
- Visualized QA distribution, score variance, and agent-level performance trends.  
- Identified outliers and correlation patterns through pair plots and heatmaps.  

### 🎨 In Power BI:  
- Developed **dynamic dashboards** with slicers for filtering by:
  - Date range  
  - Line of Business (LOB)  
  - QA evaluator  
  - Category and Subcategory  
- Implemented **KPI Cards**, **Drill-through Views**, and **Trend Analysis Pages**.  
- Added **conditional formatting** and **DAX-based dynamic titles** for better readability.  

---

## 🔍 Key Insights  

📊 **Real-Time QA Monitoring**  
> Automated refresh ensures stakeholders always see up-to-date QA results.  

📈 **Trend & Variance Analysis**  
> Performance deviations and improvement patterns are highlighted monthly.  

🧩 **Cross-System Data Integration**  
> Blends client QA data with internal CRM metrics for holistic insights.  

💬 **Root Cause Insights**  
> Category-level breakdown helps identify areas of concern and training needs.  

---

## 🧰 Technologies Used  

| Tool / Language | Purpose |
|------------------|----------|
| **Python (Pandas, Seaborn, Matplotlib)** | Data cleaning, preprocessing, and exploratory visualizations |
| **SQL Server** | Data transformation and model preparation (views for Power BI) |
| **Power BI Desktop** | Dashboard design, modeling, and reporting |
| **DAX** | Custom metrics and dynamic calculations |
| **Excel / CSV** | Source data exports integration |

---

## 🧮 Example Workflow  

QA Tab
<img width="1311" height="743" alt="image" src="https://github.com/user-attachments/assets/9300751f-89fa-4a47-b881-4770d508c0e5" />
FCR Tab
<img width="1313" height="742" alt="image" src="https://github.com/user-attachments/assets/42b20a6d-99f2-4136-987a-3533cb40d4ec" />


