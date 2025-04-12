# Bellabeat Fitness Tracker Users  Case Study
![fnp-sales-dashboard](https://github.com/tanvirfau/Sales-Analysis-Report-for-FNP/blob/main/fnp-sales-dashboard.png)
# Overview
This project analyzes fitness-related data from various datasets, focusing on user activity, caloric burn, and sleep patterns. The main goal is to explore how activity levels (steps, active minutes, sedentary time) influence calories burned and to segment users based on their physical activity. The analysis provides insights into user behavior, activity efficiency, and trends over time.

# Datasets Used
The following datasets were used in the analysis:

* daily_activity: Contains daily activity data, including total steps, distances, and active minutes.

* daily_steps: Logs the total steps taken by users.

* daily_calories: Contains information on the calories burned by users.

* daily_sleep: Logs users' sleep data, including total sleep time and time spent in bed.

# Key Features and Insights
* Data Cleaning and Merging
* Renaming Columns: Column names were standardized across datasets for consistency.

* Handling Missing Values: Missing data in several columns were filled with the mean of the column.

* Merging Data: The datasets were merged on common identifiers (user ID and date) to create a comprehensive dataset.

# Exploratory Data Analysis (EDA)
* Correlation Analysis: A correlation matrix was created to explore the relationships between activity levels, sleep, and calories burned.

* Sedentary Behavior: Analyzed the impact of sedentary minutes on calories burned.

* User Segmentation: Users were segmented based on their daily activity levels (steps) and sedentary behavior.

* Activity Efficiency: Calculated efficiency metrics such as calories burned per step and per active minute.

# Trends and Patterns
* Activity Levels by Day: Analyzed user activity patterns throughout the week. Found that users are most active on weekends (Friday and Saturday) and less active during the workweek (Monday to Thursday).

* Caloric Goals: Calculated the percentage of days users meet or exceed a 2000-calorie burn goal.

# Statistical Testing
* ANOVA: Conducted a statistical test (ANOVA) to determine if there were significant differences in caloric burn across different activity categories. The results indicated that the differences were not statistically significant.

# Visualizations
* Correlation Matrix
A heatmap visualization showing the correlation between activity levels, sleep, and calories burned.

* Activity Segmentation
A pie chart visualizing the distribution of users across different activity levels: Sedentary, Active, Moderately Active, and Very Active.

* Efficiency per Day of the Week
Bar charts displaying efficiency per step and efficiency per active minute across different days of the week, revealing that weekends (Friday and Saturday) are the most efficient days for users.

* Activity Trends
A bar chart showing the average steps taken per day, illustrating that users tend to be most active on Saturday.

# Contributing
Feel free to fork this repository, make improvements, and submit pull requests. Please follow best practices for code documentation and provide detailed explanations for any changes.

# Acknowledgements

* Data provided by the fitness tracking platform.

* Special thanks to the contributors of the fitness community.
