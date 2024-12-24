# GYM-MEMBERS-EXERCISE-TRACKING-ANALYSIS
This project delves into the behaviors, trends, and engagement patterns of gym members,  utilizing data-driven insights to improve retention, membership growth, and overall customer satisfaction.

### Project Title: GYM MEMBERS EXERCISE TRACKING ANALYSIS
---

[Overview](#overview)

[Column Descriptions](#column-descriptions)

[Data Sources](#data-sources)

[Data Types](#data-types)

[Tools Used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Visualization](#data-visualization)

[Insights and Conclusion](#insights-and-conclusion)

---

### Overview
---
The "Gym Members Exercise Tracking Analysis" dashboard is a dynamic and interactive tool designed to provide a comprehensive overview of gym members' workout performance and engagement. It showcases key metrics such as total calories burned, average age, workout duration, and distribution across various workout types. The analysis delves into trends by gender, age groups, and experience levels, offering insights into calorie burn, heart rate (BPM), workout frequency, and body weight patterns. Through visualizations like bar charts, pie charts, and filters, the dashboard highlights popular workout preferences, age-specific engagement, and gender-based differences, making it a valuable resource for identifying trends and optimizing gym programs.

### Column Descriptions
---
- Age: Age of the gym member.
- Gender: Gender of the gym member (Male or Female).
- Weight (kg): Member’s weight in kilograms.
- Height (m): Member’s height in meters.
- Max BPM: Maximum heart rate (beats per minute) during workout sessions.
- Avg BPM: Average heart rate during workout sessions.
- Resting BPM: Heart rate at rest before workout.
- Session Duration (hours): Duration of each workout session in hours
- Calories Burned: Total calories burned during each session.
- Workout Type: Type of workout performed (e.g., Cardio, Strength, Yoga, HIIT).
- Fat Percentage: Body fat percentage of the member.
- Water Intake (liters): Daily water intake during workouts.
- Workout Frequency (days/week): Number of workout sessions per week.
- Experience Level: Level of experience, from beginner (1) to expert (3).
- BMI: Body Mass Index, calculated from height and weight.

### Data Sources
---
The main primary source of data used here is “Data.Gym_Members_Exercise_Tracking.csv” and this is an open-source data that can be freely downloaded from an open online source such as Kaggle or FRED or any other data repository site.

### Data Types
---
The data types involved in the dataset included whole numbers, alphanumeric, decimal numbers, etc.

### Tools Used
---
- Power BI: Utilized for Data cleaning and Visualization [Download Here](https://www.microsoft.com).

### Data Cleaning and Preparations
---
The data cleaning process was performed in Power BI, following these steps:
- Changed data types for consistency.
- Column Renaming: Renamed columns for improved clarity and consistency.
- New Column Creation: Used conditional column to classify age brackets (Age_Band) and categorized Experience Level into “Beginner”, 
  “Advanced Beginner” and “Expert”.
- Created conditional column “Age sort” to arrange “Age Band” in order.
- Executed DAX to calculate Average Age and Session Duration amongst members.

### Exploratory Data Analysis
---
EDA involved the exploratory of Data to answer some questions about the data such as;
- What is the total calorie burn and average session duration?
- Which age group contributes most to calorie burn?
- Gender-Based Analysis
- How do calorie burn and workout frequency differ by gender?
- Which gender has a higher max and average BPM?
- Which age group maintains the highest BPM and workout frequency?
- How does calorie burn vary across age groups?
- Which workout type is most popular and burns the most calories?
- Which workout type has the highest BPM?
- Which experience level burns the most calories?
- How does workout intensity vary by experience level?
- What groups (gender, age, experience) need engagement improvement?
- How can programs be tailored for better participation?

### Data Visualization
---

![CWW - 1](https://github.com/user-attachments/assets/a6353989-b49c-413b-9ce5-5a89fe913ee5)




![CWW-2](https://github.com/user-attachments/assets/62710671-8371-422f-94ee-7cab81b78a3a)

