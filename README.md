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





