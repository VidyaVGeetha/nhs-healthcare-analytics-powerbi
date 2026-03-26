# 🏥 NHS Admissions Analytics Dashboard (Power BI)

## 📌 Project Summary
Developed an interactive Power BI dashboard to analyse NHS hospital admissions, treatment costs, and departmental performance. The solution uses time intelligence techniques to identify trends, monitor growth, and support data-driven healthcare planning.

---

## 🎯 Business Context
Healthcare providers such as the NHS must efficiently manage:

- Increasing patient demand  
- Seasonal pressure (winter peaks)  
- Resource allocation across departments  
- Rising operational costs  

This project provides analytical insights to support better planning and decision-making.

---

## 🎯 Objectives

- Track patient admissions over time  
- Analyse monthly and yearly trends  
- Compare performance year-over-year  
- Evaluate department-wise workload  
- Monitor treatment cost patterns  

---

## 📊 Dataset

A synthetic dataset was created to simulate NHS hospital operations:

- Time period: **2019–2021**
- Departments:
  - Cardiology  
  - Oncology  
  - Neurology  
  - Orthopaedics  

### Data fields:
- Patient_ID  
- Admission_Date  
- Discharge_Date  
- Department  
- Treatment_Cost  

---

## 🧱 Data Modelling

- Created a **Date dimension table** using DAX  
- Established relationship:
  - `Date[Date] → NHS Data[Admission_Date]`  
- Ensured:
  - Continuous date range (validated: 1096 days)  
  - Correct data types  
  - Single active relationship  

---

## 📈 DAX Measures

- Total Admissions (DISTINCTCOUNT)  
- Total Cost (SUM)  
- Admissions YTD (TOTALYTD)  
- Admissions Previous Year (SAMEPERIODLASTYEAR)  
- YoY Growth %  

---

## ⏳ Time Intelligence

Implemented:

- Year-to-Date (YTD)  
- Year-over-Year (YoY) comparison  

---

## 📊 Dashboard Features

- KPI Cards:
  - Total Admissions  
  - Total Cost  
  - YoY Growth %  

- Line Chart:
  - Monthly Admissions Trend  

- Bar Chart:
  - Department-wise Admissions  

- Slicers:
  - Year  
  - Department  

---

## ✅ Data Validation

- Verified continuous date table (no missing dates)  
- Matched totals with raw data  
- Validated YTD and YoY calculations  
- Ensured correct relationships  
- Fixed sorting using Year-Month numeric key  

---

## 📌 Key Insights

- Admissions show variability due to dataset size  
- Department workload is relatively balanced  
- YoY growth highlights changes across years  
- Cost trends follow admission patterns  

---

## 🧠 Skills Demonstrated

- Data Modelling  
- DAX & Time Intelligence  
- Data Validation  
- Dashboard Design  
- Business Analysis  

---

## 🛠️ Tools Used

- Power BI  
- Microsoft Excel  

---

## 📸 Project Assets

- Power BI file (.pbix)  
- Dataset (Excel)  
- Dashboard screenshots  
- Data model screenshots  

---

## 🚀 Conclusion

This project demonstrates how Power BI can be used for healthcare analytics, enabling better decision-making through data-driven insights.
