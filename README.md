# VitaTrack Wellness – Power BI Dashboard

## Project Overview
This project analyzes health and lifestyle data for **VitaTrack Wellness**, a digital health company focused on monitoring user well-being.  
The dashboard is built using **Power BI** and aims to uncover lifestyle patterns, health risks, and actionable insights from user activity data.

The analysis focuses on daily steps, calorie intake, sleep habits, BMI, and lifestyle factors such as smoking and alcohol consumption.

---

## Dataset
The dataset contains individual-level health metrics, including:
- Age and Gender  
- Height, Weight, and BMI  
- Daily Steps  
- Calories Intake  
- Hours of Sleep  
- Heart Rate and Blood Pressure  
- Exercise Hours per Week  
- Smoking Status and Alcohol Consumption  
- Diabetic Status and Heart Disease indicator  

Each row represents a unique user’s health profile.

---

## Objectives
The dashboard is designed to answer the following key questions:
- Are users maintaining a balanced lifestyle in terms of steps, calories, and sleep?
- How does BMI vary across age groups and gender?
- Is there a relationship between sleep and physical activity?
- What is the impact of smoking and alcohol on heart rate and blood pressure?
- Which user segments are at higher risk of heart disease?

---

## Data Preparation
The following steps were performed in Power BI:
- Data type validation for numeric and categorical fields
- Creation of **Age Groups (10-year intervals)**
- Categorization of BMI into health ranges
- Handling of missing values where required
- Creation of calculated measures for averages and percentages

---

## Key Features of the Dashboard
- Age group and gender-based comparisons
- Number of people of heart disease
- Number of heart disease by Age-group
- Avg steps and avg sleep by Age-group
- Table for risk profile
- Lifestyle impact analysis for smoking and alcohol consumption
- Interactive slicers for gender, age group, smoking status, and diabetic status

---

## Tools Used
- Power BI Desktop  
- DAX for calculated columns and measures  
- CSV dataset for data source  

---

## Insights Summary
- Users show relatively balanced sleep patterns, averaging close to recommended levels
- A segment of users consumes higher calories without proportional physical activity
- Lifestyle factors like smoking and alcohol show noticeable impact on heart rate and blood pressure

---

## Files in This Repository
- `.pbix` – Power BI dashboard file  
- `.csv` – Dataset used for analysis  
- `README.md` – Project documentation  

---

## How to View the Dashboard
1. Download the `.pbix` file  
2. Open it using **Power BI Desktop**
3. Use slicers to explore insights interactively

---

## Author
**Satyam Kumar**  
Aspiring Business Analyst | Power BI | Data Analytics  

---

## Note
This project was created for learning and academic purposes as part of a data analytics assignment.
