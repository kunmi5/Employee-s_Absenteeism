# Employee's_Absenteeism
# Project Overview
Employee absenteeism is a major challenge that impacts productivity, team performance, and business costs. This project analyzes attendance data to uncover patterns and key factors driving absenteeism—such as health, commuting distance, workload, and seasonal trends.
In addition to analysis, it applies predictive models to forecast absenteeism risk, enabling HR teams to take proactive steps like flexible work policies or wellness programs. The goal is to show how data-driven insights can help organizations improve workforce planning, reduce disruptions, and support employee well-being.
--
# Tools
+ ### Microsoft Excel: Used for data loading and cleaning, transforming the dataset into a suitable format for analysis.
+ ### Power BI: Used for addition of new measures and new columns and data visualizations.
---

# Dataset
## Table 1 ( Absenteeism ) 
## Features
+ ### Seasons
+ ### Months
+ ### Disciplinary status
+ ### Weekday
+ ### Absenteeism reasons
+ ### Service time
+ ### Workload average
+ ### Hit target

  <img width="927" height="397" alt="Screenshot 2025-09-03 020318" src="https://github.com/user-attachments/assets/70800c10-3544-4d16-99f4-7f96ccdd1bf9" />


## Table 2 ( Employee's Info ) 
## Features
+ ### Age
+ ### BMI
+ ### Children
+ ### Education level
+ ### Height
+ ### Transportation expense
+ ### Drinker and smoker status
+ ### Pet

<img width="924" height="409" alt="Screenshot 2025-09-03 020237" src="https://github.com/user-attachments/assets/2a599602-53da-4a4b-9de2-5892c78b1752" />

## Data Preparation in Power BI
After importing the data into Power BI, the following additions were made:

+ ### A calculated Body Mass Index (BMI) field was derived to analyze the relationship between health and absenteeism which helped to highlight Obese, Overweight or Normal employees.
<img width="927" height="405" alt="Screenshot 2025-09-07 130738" src="https://github.com/user-attachments/assets/ea748a22-13b5-4479-ba34-a2f9a8c3302b" />

+ ### A calculated Season was derived Based on Month of Absence. These engineered features make it easier to identify seasonal patterns in absenteeism.
#### Winter: December – February

#### Spring: March – May

#### Summer: June – August

#### Autumn: September – November

<img width="922" height="404" alt="Screenshot 2025-09-07 130609" src="https://github.com/user-attachments/assets/1acfbf83-3d2a-4e1d-915c-1a2153a0f5ac" />

+ ### A calculated Absenteeism reason column → Simplified categories from numeric codes

#### Incomplete submission (code = 0)

#### Family-related (codes ≤ 4)

#### Unjustified leave (code = 26)

#### Medical reasons (all other codes)

#### These engineered features make the dataset cleaner and more interpretable, allowing better visualization and HR decision-making.
<img width="927" height="405" alt="Screenshot 2025-09-07 130503" src="https://github.com/user-attachments/assets/75d2b9de-c5a8-4f32-ba30-8400ea02ea05" />

## Objectives
+ ### Clean and preprocess raw absenteeism data
+ ### Perform Exploratory Data Analysis (EDA)
+ ### Identify key drivers of absenteeism (e.g., health, distance, seasons)
+ ### Train and evaluate ML models to predict absenteeism risk
+ ### Provide actionable recommendations for HR policy improvement

## Data Analysis and Visualization
+ ### Total Absences by Season  
   - #### Spring had the highest number of absences (195), followed by Summer (159). Autumn and Winter had the lowest and almost equal absenteeism rates, suggesting possible seasonal effects on attendance.
<img width="253" height="210" alt="Screenshot 2025-09-07 141505" src="https://github.com/user-attachments/assets/e1b14cdd-a90e-4a86-8221-780a636a4563" />

+ ### Absenteeism Reasons  
   - #### Medical reasons are by far the leading cause of absenteeism (555 cases), making up the majority. Other causes like incomplete submission (34), unjustified leave (30), and family-related issues (20) are minimal in comparison.
<img width="342" height="178" alt="Screenshot 2025-09-07 141517" src="https://github.com/user-attachments/assets/a0be9c72-6015-4943-bfb6-69d10f9fd481" />

+ ### Count of BMI  
   - #### Most employees fall under the normal BMI category (15 people, 40.54%). Overweight (12 people, 32.43%) and obese (10 people, 27.03%) follow, indicating that a notable portion of the workforce may be at risk of health-related absenteeism.
<img width="218" height="150" alt="Screenshot 2025-09-07 141603" src="https://github.com/user-attachments/assets/71ae9803-e257-4e60-acaa-93e37cd6cc6e" />

+ ### Count of Absenteeism Reason by Month  
   - #### March and February show the highest absenteeism counts, largely driven by medical reasons. There are consistent medical absences throughout the year, while other reasons like family or incomplete submission appear sporadically.
<img width="606" height="143" alt="Screenshot 2025-09-07 141539" src="https://github.com/user-attachments/assets/3df9428d-05b0-4e78-9944-d7345085b311" />






