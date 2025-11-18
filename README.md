# Student_performance_analysis
Analysis of students’ performance across subjects with detailed dashboards and factor analysis.
# Analysis of Student Academic Performance Report

## General Description of the Report
This report, created using **Power BI Desktop** and based on the **Students_Academic_Performance_Dataset (CSV)** from Kaggle, provides a comprehensive study of student performance according to several factors: **gender, race, participation in a test preparation course, lunch program, and parental education level**.  
The report is structured around **four main pages**, each providing a specific perspective on the data.

---

## Report Structure

- **Page 1 – Basic Student Characteristics**  
  Provides an overview of the total number of students and the distribution by **gender, race, parental education level, lunch program, and test preparation course**.  
  **Visualizations:** KPI, bar charts, P-charts, Donut charts
  **Objective:** Describe general student population characteristics.

- **Page 2 – Student Performance Overview**  
  Focuses on analyzing **average scores and pass rates**, comparing results by gender, race, test preparation, lunch program, and parental education.  
  **Visualizations:** bar charts, column charts, stacked charts, performance KPIs  
  **Objective:** Highlight variations in performance according to different factors.

- **Page 3 – Factors Influencing Performance**  
  Analyzes the impact of certain factors on scores: test preparation, parental education, and gender.  
  **Visualizations:** scatter plots, box plots  
  **Objective:** Identify factors that truly influence student scores.

- **Page 4 – Students’ Scores by Subjects**  
  Detailed analysis of scores by subject (Reading, Math, Writing).  
  **Visualizations:** KPIs by subject, heatmaps (Math/Reading/Writing × Race × Parental Education), column charts by gender and test preparation  
  **Objective:** Examine score distributions and compare performance by category.

---

## Navigation and Filters
- **Main slicers:** Gender, Race, Test Preparation, Lunch  
- **Placement:** Slicers are on Page 2 and **synchronized on Pages 3 and 4** to ensure data consistency.  
- **Behavior:** Filters automatically apply across all pages, allowing consistent exploration of subgroups.

---

## Key Points and Conclusions
- Students with parents of **high education level** tend to achieve the best scores.  
- **Test Preparation Courses** significantly improve results.  
- **Gender** shows differences in certain subjects, but less pronounced than parental education or test preparation.  
- **Lunch Program** and certain characteristics (e.g., race) are more **descriptive** than causal.  
- Visualizations (KPI, box plots, heatmaps, scatter plots) help understand **both average performance and score distributions**.

---

## Instructions for Use
1. Start with **Page 1** to explore general student characteristics.  
2. Use the **slicers on Page 2** to filter by Gender, Race, Test Preparation, or Lunch.  
3. Navigate to **Page 3** to examine factors influencing scores.  
4. Check **Page 4** for a detailed analysis of scores by subject and Race × Parental Education.

---

## Technical Information
- **Software:** Power BI Desktop  
- **Dataset:** Students_Academic_Performance_Dataset (CSV) from Kaggle  
- **Version:** Slicer synchronization enabled; KPIs and visualizations optimized for clarity and consistency  

---

## Choice of Pages and Visualizations
- **Page 1:** Overview of student population; simple visualizations to identify main trends  
- **Page 2:** Compare overall performance by category; detect score differences quickly  
- **Page 3:** Focus on factors influencing scores; use box plots and scatter plots for distribution and correlation  
- **Page 4:** Detailed scores by subject; heatmaps for Race × Parental Education; column charts for gender and test preparation comparison

---

## Explanation of Visualization Choices
- **KPI:** Concise, immediately readable key indicators  
- **Bar / Column charts:** Compare categories easily  
- **Stacked charts:** Show composition of results  
- **Box plots:** Show median, quartiles, range, and outliers  
- **Scatter plots:** Detect correlations between quantitative variables  
- **Heatmaps:** Visualize average scores across multiple crossed factors

---

## Justification for Slicer Placement and Synchronization
- Slicers placed on **Page 2** to avoid clutter  
- Synchronized across all pages to ensure **data consistency** and facilitate exploration of student subgroups
