# Dashboards



### **Healthcare Analytics & Billing Insights Dashboard (Power BI)**

*A comprehensive analytics solution for patient demographics, financial insights, payer spend, and provider performance*

---

# 📌 **PROJECT OVERVIEW**

This project analyzes a synthetic Healthcare dataset from Kaggle and transforms it into an **interactive, insights-driven Power BI dashboard**.
The solution provides a full 360° view of patient population, billing trends, medical conditions, payer performance, hospital activity, and doctor efficiency — similar to dashboards used by health plans (Cigna, Medicare, UnitedHealthcare) and provider organizations.

Using a BI industry-standard approach, the dataset was cleaned, modeled using a star schema, and enriched through DAX measures to support drill-downs, segmentation, and year-over-year financial analysis.

---

# 📊 **KEY FEATURES OF THE DASHBOARD**

### ⭐ **1. Patient Demographics**

* Total patient population
* Gender distribution
* Age insights and segmentation
* Patient count by medical condition

### ⭐ **2. Financial & Billing Intelligence**

* Total billing amount (with B/M/K formatting)
* Average billing per patient and per condition
* Year-over-year billing trend
* Cost per condition and cost per insurance provider
* Billing trend by year (2019–2024)

### ⭐ **3. Payer (Insurance Provider) Analytics**

* Billing distribution across Cigna, Medicare, Aetna, Blue Cross, UnitedHealthcare
* Comparison of payer spend across medical conditions
* Total contribution of each payer to system revenue

### ⭐ **4. Provider Performance**

* **Top 10 doctors** by billing amount
* **Hospital-level billing insights** (Treemap visualization)
* Billing variation by doctor, hospital, and condition

### ⭐ **5. Admission Insights**

* Patient distribution by admission type (Emergency, Urgent, Elective)
* Gender split by admission type
* Billing impact by admission category

### ⭐ **6. Fully Interactive Experience**

* Slicers for dynamic exploration:
  Medical Condition, Insurance Provider, Gender, Admission Type, Year
* Drill-down capability
* Conditional formatting to highlight cost drivers

---

# 🧠 **TECHNICAL HIGHLIGHTS**

### ✔ **Tools & Skills Used**

* **Power BI**
* **DAX Measures**
* **Power Query (ETL)**
* **Data Modeling (Star Schema)**
* **Data Visualization & UX Design**

---

# 🏗 **DATA MODELING**

The dataset was modeled using a **Star Schema**:

### **Fact Table**

* FactBilling (Billing Amount, Patient ID, Condition, Payer, Year, Admission Type)

### **Dimension Tables**

* DimPatient (Age, Gender)
* DimCondition
* DimInsuranceProvider
* DimHospital
* DimDoctor
* DimDate

This provides cleaner relationships, better performance, and flexible DAX calculations.

---

# ✨ **DAX MEASURES CREATED**

* Total Billing
* Total Patients
* Avg Billing per Patient
* Avg Billing per Condition
* YoY Billing % Change
* Billing Trend (Year)
* Billing Contribution % by Payer
* Distinct Patient Count
* Cost per Admission Type
* Gender Share (%)
* Billing by Provider / Condition / Payer

Each measure was designed for performance and reusability.

---

# 📈 **INSIGHTS DISCOVERED**

* Arthritis and Diabetes are the highest-volume medical conditions.
* Cigna and Medicare contribute the majority of payer billing.
* Emergency admissions drive more than 50% of patient volume.
* Patient gender distribution is nearly equal.
* Billing peaked in 2021–2023 and declined in 2024.
* Top doctors and hospitals show significant variation in total billing.

---

# 🎯 **PROJECT IMPACT (FOR RECRUITERS)**

This project demonstrates proficiency in:

* Translating healthcare data into business insights
* Building scalable BI solutions
* Applying DAX for complex calculations
* Designing dashboards for decision-making
* Understanding provider and payer analytics
* Storytelling with data

It highlights strong analytical thinking, data modeling, and real-world BI development skills relevant to **Healthcare Analytics**, **BI Developer**, **Data Analyst**, and **Reporting Analyst** roles.

---

# 📁 **FILES INCLUDED**

* Power BI Dashboard (`Healthcare_Analytics.pbix`)
* Cleaned and transformed dataset
* DAX measures script
* Data model diagram
* Project documentation (README)

---

# 📌 **READY-TO-USE README MARKDOWN**

If you want, I can generate a **complete GitHub README.md** with formatting, badges, headers, screenshots, and instructions for running the dashboard.

Would you like me to generate the README file next?
