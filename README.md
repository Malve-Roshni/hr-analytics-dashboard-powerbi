# HR Analytics Dashboard

## 📌 Project Overview
This project presents an **HR Analytics Dashboard** built using **Power BI** to analyze key HR metrics such as employee attrition, demographics, job satisfaction, and department performance. The dashboard offers actionable insights to help organizations improve employee retention, engagement, and overall workforce management.

Key metrics include:
- **Total Employees**
- **Active Employees**
- **Attrition Count**
- **Attrition Rate**
- **Performance Ratings**
- **Job Satisfaction Ratings**

---

## 📂 Project Structure
```
HR_Analytics_POWERBI/
│── dataset
│   ├── HR Data.xlsx            # Original HR dataset
│
├── Dashboard/
│   ├── HR_Analytics_Dashboard.pbix    # Power BI dashboard file
│   ├── dashboard_screenshot.png       # Visual snapshot of dashboard
│
├── Documentation/
│   ├── project_report.pdf             # (Optional - Now merged into README)
│   ├── key_insights.txt               # (Optional - Now merged into README)
│
├── README.md                    # Project documentation
```

---

## ⚙️ Data Cleaning Process
To ensure data accuracy and enable better analysis, key cleaning steps included:

### **1. Attrition Count (Conditional Column)**
- Created a **conditional column** named `Attrition Count`.
- Mapped:
  - **"Yes"** = `1` (Employee left the organization)
  - **"No"** = `0` (Employee remained active)
- Converted the new column data type from **text** to **whole number** for improved calculation accuracy.

### **2. Additional Cleaning Steps**
- Removed duplicates.
- Ensured consistent formatting for key fields (e.g., department names, job roles, etc.).
- Filled missing values in critical columns for reliable visualizations.

---

## 📊 Key Insights from Analysis
### **Employee Overview:**
- **Total Employees:** `1470`
- **Active Employees:** `1233`
- **Attrition Count:** `237`
- **Attrition Rate:** `16%`

### **Department Insights:**
- **R&D Department** has the **highest number of attrition cases**.
- The **HR Department** shows the **lowest attrition** levels.

### **Income & Job Role Insights:**
- Higher-income job roles generally have **fewer employees**, indicating specialized positions with limited workforce.
- The **average monthly income** decreases significantly across lower-level job roles.

### **Education Field Analysis:**
- Most employees belong to the **Life Sciences** field (41.93%) and **Medical** field (32.52%).
- Departments with technical expertise show comparatively lower attrition rates.

### **Job Satisfaction Ratings:**
- **Research Scientists** and **Laboratory Technicians** report **lower job satisfaction levels**, indicating a need for improved work conditions or incentives in these roles.

---

## 📊 Conclusion
- The **16% attrition rate** highlights a moderate employee turnover concern that should be addressed.
- The **R&D Department** requires targeted HR strategies to reduce high attrition cases.
- Enhanced employee engagement strategies should focus on improving job satisfaction, particularly for **Research Scientists** and **Laboratory Technicians**.
- Increasing retention incentives for **higher-income roles** may help retain specialized talent.

---

## 🛠️ Technologies Used
- **Power BI**: Data visualization and dashboard creation.
- **Excel**: Data cleaning and transformation.
- **DAX (Data Analysis Expressions)**: For calculated measures and dynamic visuals.
- **VS Code**: For managing the project structure and documentation.
- **GitHub**: Version control and project sharing.

---

## ⚡ Usage Instructions
### **1. Clone the Repository**
```sh
git clone https://github.com/Malve-Roshni/hr-analytics-dashboard-powerbi.git
cd hr_analytics_dashboard
```

### **2. Open the Power BI Dashboard**
- Open the **`HR_Analytics_Dashboard.pbix`** file in Power BI.

### **3. Explore Key Visuals**
- Utilize interactive filters to analyze specific departments, employee demographics, and satisfaction ratings.

✅ The dashboard will provide insights to improve HR strategies, reduce attrition, and enhance employee engagement.


---

## 📄 About

HR Analytics Dashboard using Power BI: This interactive dashboard provides insights into employee data, covering key metrics such as Total Employees, Attrition Rate, Active Employees, and Job Satisfaction Ratings.

The dashboard leverages Power BI visuals, DAX measures to highlight trends in employee
👉 **GitHub Repository:** [HR Analytics Dashboard](https://github.com/Malve-Roshni/hr-analytics-dashboard-powerbi)

---
