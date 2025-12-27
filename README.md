# 🚗 Data-Driven Insights Using Python: Austo Automobiles

## 📌 Project Overview
This project presents a comprehensive data-driven analysis of customer demographics, financial behavior, and automobile purchasing patterns for **Austo Motor Company**. Using Python-based exploratory data analysis (EDA), the study aims to uncover meaningful insights that can help optimize marketing strategies, improve customer targeting, and enhance overall business decision-making.

The analysis focuses on understanding how factors such as income, age, gender, profession, education, loan status, and household structure influence vehicle type selection (SUV, Sedan, Hatchback) and spending behavior.

---

## 🎯 Business Problem
Austo Motor Company lacks clear visibility into whether its current marketing campaigns are reaching the right customers and effectively influencing vehicle purchase decisions. Without data-backed insights into customer preferences and spending behavior, marketing efforts risk being inefficient and misaligned with actual demand.

---

## 🎯 Objective
- Analyze customer data to identify buying patterns and preferences  
- Understand how demographic and financial factors influence vehicle choice and spending  
- Support more targeted marketing strategies and improve customer experience  

---

## 💡 Business Opportunity
By identifying key customer segments and the drivers behind their vehicle choices, Austo Motor Company can:
- Improve campaign targeting and conversion rates  
- Align product positioning with customer income and lifestyle  
- Increase overall sales across SUVs, Sedans, and Hatchbacks  

---

## 📊 Dataset Description
- **Records:** 1,581 customers  
- **Features:** 14 variables (numerical + categorical)

### Key Variables
- **Demographic:** Age, Gender, Profession, Marital Status, Education  
- **Household:** Number of Dependents, Partner Working Status  
- **Financial:** Salary, Partner Salary, Total Salary, Personal Loan, House Loan  
- **Purchase:** Vehicle Price, Vehicle Type (SUV / Sedan / Hatchback)

---

## 🛠 Tools & Technologies
- **Python**
- **Google Colab**
- **Libraries Used:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn

---

## 🧹 Data Cleaning & Processing
- Handled missing values in `Gender` using mode imputation  
- Derived missing `Partner_salary` values logically from total household income  
- Corrected categorical inconsistencies (e.g., standardizing gender labels)  
- Verified logical consistency across salary variables  
- Detected and treated outliers using the IQR capping method  
- Confirmed absence of duplicate and invalid records  

---

## 🔍 Exploratory Data Analysis (EDA)

### Univariate Analysis
- Majority of customers fall within the young to mid-career age group  
- Salaries and vehicle prices are concentrated in the mid-range  
- Sedans are the most frequently purchased vehicle type  
- Customer base is predominantly male, married, salaried, and well-educated  

### Bivariate Analysis
Key relationships identified:
- Strong positive relationship between **income (salary & total salary)** and **vehicle price**
- **Age** is positively correlated with both **income** and **vehicle price**
- **Partner salary** significantly boosts total household income
- **Number of dependents** shows little influence on spending behavior

---

## 📈 Key Insights
- Sedans are preferred by salaried professionals seeking value and practicality  
- SUVs are purchased by higher-income, older, and financially stable households  
- Hatchbacks attract budget-conscious customers with lower income levels  
- Female customers, on average, spend more on vehicles than male customers  
- Customers without personal loans tend to spend more on automobiles  
- Dual-income households exhibit greater purchasing power  

---

## 📌 Key Business Questions Answered
- Do men prefer SUVs more than women? → **No, SUV preference is higher among women in this dataset**  
- Are salaried individuals likely to buy Sedans? → **Yes, Sedans are the dominant choice**  
- Does income influence vehicle price? → **Yes, moderately to strongly**  
- Does partner employment impact spending? → **It increases total income but has limited direct impact on vehicle price**  

---

## 📢 Actionable Insights
- Income and age are primary drivers of vehicle choice and spending  
- Sedans and Hatchbacks dominate due to affordability and practicality  
- SUVs function as aspirational, premium purchases  
- Gender-based differences suggest opportunities for tailored messaging  

---

## 🧠 Business Recommendations
- Target **SUV marketing** toward high-income, older, dual-income households  
- Strengthen **Sedan-focused campaigns** for salaried professionals  
- Position **Hatchbacks** as value-driven options for younger and budget-conscious buyers  
- Use gender-specific messaging to highlight premium features for female customers  
- Offer flexible financing options for loan-sensitive customers  
- Leverage personalized communication based on income and household structure  

---

## 🚀 Future Scope
- Build predictive models for vehicle price or vehicle type selection  
- Perform customer segmentation using clustering techniques  
- Create dashboards using Power BI or Tableau  
- Integrate behavioral and geographic data for deeper insights  

---

## 👤 Author
**Arhana Sen Chowdhury**  
Aspiring Data Analyst | Python | Data Visualization  

📎 *This project is part of my data analytics portfolio and demonstrates the application of Python for business-driven insights.*
