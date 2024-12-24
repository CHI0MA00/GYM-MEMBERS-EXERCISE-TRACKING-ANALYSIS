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

[Insights](#insights)

[Recommendations](#recommendations)

[Conclusion](#conclusion)

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


### Insights
---
- Total Calories Burned: Gym members have collectively burned 881,000 calories.
- Average Age: The average age of members is 39 years.
- Workout Variety: There are four workout types tracked (possibly including Cardio, HIIT, and Strength).
- Session Duration: The average workout session duration is approximately 1 hour.
- Experience Level: Most calories burned are by "Advanced Beginners" (366.18K), followed by Beginners (273.12K) and 
  Experts (241.68K).
- Gender Breakdown: Males burned 483K calories (54.78%), while females burned 398K calories (45.22%).
- Age Band: Members aged 45-54 burned the most calories (220K), while those over 55 burned the least (88K).
- Max BPM by Gender: Female members show a slightly higher maximum BPM (52.55%) compared to males (47.45%), 
  suggesting they reach higher heart rates during workouts.
- Body Weight by Workout Type and Gender: Female members generally have a higher body weight engagement across most 
  workout types (Cardio, Strength, Yoga, and HIIT). The distribution of body weight across workout types seems 
  balanced, with both males and females showing varied body weights across each workout type.
- Average BPM by Age Band: The 35-44 age group has the highest average BPM (26.12%), followed by the 45-54 (23.56%) 
  and 25-34 (22.23%) age groups. The under-25 and over-55 age bands contribute the least in terms of average BPM.
- Workout Frequency by Workout Type: Strength training has the highest frequency (866 days/week), followed by Cardio 
  (825 days/week), Yoga (801 days/week), and HIIT (740 days/week).This suggests that Strength and Cardio are the 
  most popular workout types in terms of frequency.
- Workout Frequency by Gender: Females show slightly higher workout frequency (52.26%) compared to males (47.74%), 
  indicating a more consistent workout routine among female members.

### Recommendations
---
1. Encourage Participation Among Beginners:
Increase support or guidance for beginners to help them increase their calorie burn and retain them longer.
Offer introductory sessions or classes to help beginners progress more quickly.
2. Optimize Workouts for Each Age Group:
Tailor programs for older members (especially those over 55) to boost their engagement and calorie burn.
Consider lower-impact, age-appropriate exercises to attract and retain older members.
3. Balance Workout Types:
Evaluate the popularity and effectiveness of each workout type (e.g., Cardio, HIIT, Strength) to ensure all member needs are met.
Introduce new workout options or hybrid classes to add variety and appeal to a broader audience.
4. Gender-Specific Marketing:
Promote programs and classes that encourage balanced participation across genders, especially if certain workout types appeal more to one gender.
5. Encourage Advanced Members to Burn More:
Offer advanced challenges or incentives to expert-level members to keep them motivated and increase their calorie burn even further.
6. Target Workouts Based on Body Weight Groups:
For members with higher body weights, consider offering personalized workout plans focused on strength and cardio to help them manage weight and improve fitness.
For lighter members, focus on high-intensity workouts like HIIT to further improve cardiovascular endurance and muscle tone.
7. Increase Engagement in HIIT Programs:
Since HIIT has the lowest frequency, consider creating beginner-friendly HIIT classes or shorter sessions to attract a broader range of members, including those who might find standard HIIT classes challenging.
8. Optimize Intensity by Age Group:
For the age groups with lower BPMs (Under 25 and Over 55), design specific programs that encourage appropriate intensity while remaining safe and enjoyable for their fitness levels.
9. Encourage Consistent Workout Routines Across Genders:
Leverage the consistency of female members to inspire similar engagement from male members, potentially through competitive or team-based workout programs that foster motivation.
10. Adjust Programs by Age Band to Maximize Engagement:
Since each age group has a different average BPM, tailor class intensity to suit these needs. For instance, focus on higher-intensity options for younger members (Under 25) to increase their engagement, and age-appropriate programs for older members to support longevity and safety.

### Conclusion
---
By applying these recommendations, the gym can enhance member satisfaction, retention, and the overall effectiveness of workout programs. These adjustments will help the gym align its offerings to members’   needs, encourage more consistent workout routines, and optimize engagement across different demographics.
