# Student Performance Analysis

**Analysis of students’ performance across subjects with detailed factor analysis.**

---

## General Description

This project, built using **Power BI Desktop**, analyzes student performance based on multiple factors: **gender, race, test preparation course, lunch program, and parental education level**.  
The dataset used is the **Students_Academic_Performance_Dataset (CSV)** from Kaggle.

The report aims to provide insights on **average performance, pass rates, and factor influences**.

---

## Key Insights

### 1. Impact of Test Preparation
- Students who **completed the test preparation course** perform significantly better than those who did not.  
- **Average score improvement:** +8 points.  
- **Minimum score** is higher for prepared students → fewer severe failures.  
- **Quartiles (Q1, Q3)** are higher → both weaker and stronger students benefit.  
- Non-prepared students have:
  - More severe failures  
  - Greater score dispersion  
  - Lower median scores  

**Conclusion:** Test preparation provides a **real and measurable advantage**, improving average performance and stability.

### 2. Effect of Parental Education Level
- **High education level parents** → students achieve the best scores.  
- **Low education level parents** → students have lower scores and less variability.  
- **Median education level parents** → students perform between the two groups.  

**Conclusion:** Parental education is positively correlated with student performance. High parental education → higher average scores.

### 3. Performance Observations by Subject and Group
- Certain student groups perform better in **specific subjects** regardless of parental education.  
- Family practices and community dynamics can influence performance, sometimes counterbalancing lower parental education.  
- Prepared students show **more stable results** with fewer very low scores.

---

## Data Preparation and Modeling

### 1. Creation of New Columns
- **Categorized variables** (e.g., parental education levels grouped for comparisons)  
- **Grouped performance indicators** for cross-factor analysis  
- **Text-standardized columns** for consistency

### 2. Creation of DAX Measures
- **Average Math Score**  
- **Average Reading Score**  
- **Average Writing Score**  
- **Overall Average Score**  
- **Total Students**  
- **Pass Rate**

These measures allow **dynamic and accurate calculations** across all report pages.

### 3. Pass/Fail Definition
- **Pass:** Overall Average Score ≥ 60  
- **Fail:** Overall Average Score < 60  

Used to create **clear performance categories** and compute pass rates across groups.

---

## Navigation and Filters
- **Slicers:** Gender, Race, Test Preparation, Lunch  
- Slicers are **placed on Page 2** and **synchronized** across relevant pages for consistent subgroup analysis.  
- Filters can be applied selectively depending on the analytical context.

---

## Skills Used
- **Power BI Desktop** – report building and data visualization  
- **DAX** – calculation of measures and pass rates  
- **Data Cleaning & Preparation** – column creation, text standardization  
- **Data Analysis** – interpretation of distributions, quartiles, and factor influence  
- **Kaggle Dataset Handling** – working with CSV datasets  

---

## Dataset
- **Source:** [Kaggle – Students Academic Performance Dataset](https://www.kaggle.com/datasets)  
- **Format:** CSV  
- **Rows:** 1000  
- **Columns:** Performance and demographic variables

---

## How to Use
1. Open the **Power BI report**.  
2. Explore general student characteristics on Page 1.  
3. Filter by Gender, Race, Test Preparation, or Lunch using slicers on Page 2.  
4. Examine factors influencing scores on Page 3.  
5. Review subject-level performance in Page 4.  





 



