# Gym Members Exercise Data Set

## About Dataset
This dataset provides a detailed overview of gym members' exercise routines, physical attributes, and fitness metrics. It contains 973 samples of gym data, including key performance indicators such as heart rate, calories burned, and workout duration. Each entry also includes demographic data and experience levels, allowing for comprehensive analysis of fitness patterns, athlete progression, and health trends.

## Dataset Features
Age: Age of the gym member.
Gender: Gender of the gym member (Male or Female).
Weight (kg): Member’s weight in kilograms.
Height (m): Member’s height in meters.
Max_BPM: Maximum heart rate (beats per minute) during workout sessions.
Avg_BPM: Average heart rate during workout sessions.
Resting_BPM: Heart rate at rest before workout.
Session_Duration (hours): Duration of each workout session in hours.
Calories_Burned: Total calories burned during each session.
Workout_Type: Type of workout performed (e.g., Cardio, Strength, Yoga, HIIT).
Fat_Percentage: Body fat percentage of the member.
Water_Intake (liters): Daily water intake during workouts.
Workout_Frequency (days/week): Number of workout sessions per week.
Experience_Level: Level of experience, from beginner (1) to expert (3).
BMI: Body Mass Index, calculated from height and weight.

This dataset is ideal for data scientists, health researchers, and fitness enthusiasts interested in studying exercise habits, modelling fitness progression, or analysing the relationship between demographic and physiological data. With a wide range of variables, it offers insights into how different factors affect workout intensity, endurance, and overall health.

## Approach Used
Feature Engineering
* Create a column named   BMI_Category   to categorize the members as Underweight, Normal weight, Overweight, or Obese based on their BMI.
* Create column named experience_level to categorize different experience levels as Beginner, Intermediate, Advanced.
* Create a new column Meets_recommended_Frequency to categorize participants as meeting or not meeting the recommended frequency ((4+ days/week)=meet's recomanded frequency,else does not meet the recommended frequency).

## Analysis List

### Demographic Analysis

1. What is the number of male and female participants across different age groups? 

2. How are participants categorized by BMI (Underweight, Normal, Overweight, and Obese) across different age groups and genders?

### Health and Fitness Metrics

3. How does the average body fat percentage vary across different workout types?

4. How does the maximum heart rate (Max_BPM) vary across different experience levels (Beginner, Intermediate, and Advanced)?

5. What is the average weight and height of gym members?

### Performance and Workout Efficiency

6. Which workout type leads to the highest average calorie burn per hour?

7. How does water intake correlate with session duration and calories burned?

8. What is the distribution of workout types across different experience levels?

9. What is the average number of days worked out per week for each experience level?

10. How does consistency in workout frequency (4+ days per week) vary by gender?

### Hydration and Recovery

11. What is the average water intake per session across different workout types?

### Statistical Insights

12. Determine the mean and standard deviation of calories burned across all sessions.

13. Calculate the Inter Quartile Range (IQR) for Calories_Burned.

14. Calculate and visualize the normal distribution curve for the calories burned during gym exercises.


