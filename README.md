# HR_Analytics
# 📊 HR Analytics Dashboard | Power BI

An interactive Power BI dashboard that analyses **employee attrition** to understand *who leaves, and why*.

![Dashboard Preview]

## 🎯 Objective
Help HR identify the key factors behind employee attrition so the company can improve retention.

## 📈 Key Metrics
| Metric | Value |
|---|---|
| Total Employees | 1,470 |
| Attrition Count | 237 |
| **Attrition Rate** | **16.1%** |
| Avg. Age | 37 |
| Avg. Monthly Salary | ₹6.5K |
| Avg. Years at Company | 7.0 |

## 🔍 Key Insights
- 💰 **Low salary = high attrition**: 163 of 237 leavers earn *under 5K*.
- 🧑‍💼 **Lab Technician, Sales Executive & Research Scientist** roles have the highest attrition.
- 🎂 **26–35 age group** leaves the most (116 employees).
- 🎓 Employees with **Bachelor's-level education** show the highest attrition (38%).
- ⏳ Attrition is highest in the **first 1–2 years** at the company.
- 👥 Male attrition (123) is higher than female (66).

## 🛠️ Tools & Process
- **Power BI Desktop**: data cleaning (Power Query), DAX measures, dashboard design
- **Data cleaning**: handled duplicates/nulls, fixed data types, created `AgeGroup` and `SalarySlab` columns
- **Dataset**: HR Analytics (1,470 employees, 38 columns)

## 🖱️ Interactive Features
- Slicers/filters by Department, Gender, Job Role, etc.
- Cross-filtering across all charts
- Hover tooltips for detailed values

## 📁 Repository Structure
```
├── HR_Analytics.csv                # Dataset
├── hr_analytis_powerBI.pbix        # Power BI file
├── hr_analytis_powerBI.pdf         # Dashboard export
└── README.md
```
## ▶️ How to Use
1. Download the `.pbix` file
2. Open it in **Power BI Desktop**
3. Explore using the filters
