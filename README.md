Chicago Ride-Sharing Analysis (SQL & Python)
📊 Project Overview

In this project, I worked as a data analyst for Zuber, a new ride-sharing company launching operations in Chicago. The goal was to analyze ride data stored in a relational database to uncover passenger behavior patterns, identify high-demand neighborhoods, and evaluate how external factors—specifically weather conditions—affect ride duration.

🗄️ Data Collection (SQL)

Using SQL, I extracted and joined data from multiple tables, including:

Neighborhoods (location information)

Cabs (vehicle and company details)

Trips (ride timestamps, duration, and destinations)

The SQL queries were used to prepare clean, structured datasets for further analysis in Python.

📈 Data Analysis & Visualization (Python)

After loading the SQL query results into Python, I:

Cleaned and preprocessed the data

Identified the most frequent ride destinations (e.g., Loop and O’Hare neighborhoods)

Visualized ride distributions and demand patterns using bar charts

Compared ride durations under different weather conditions

📐 Hypothesis Testing

To evaluate the impact of weather on ride behavior, I tested the hypothesis that average ride duration does not change on rainy Saturdays.
Using a significance level of α = 0.05, the hypothesis was rejected, indicating a statistically significant increase in ride duration during rainy conditions—likely due to reduced visibility and slower traffic.

✅ Key Insights

The Loop and O’Hare are the most popular ride destinations

Weather conditions significantly impact ride duration

Rainy days lead to longer trips, which can affect pricing, driver availability, and customer experience

🛠️ Tools & Skills Used

SQL (joins, filtering, aggregation)

Python (pandas, matplotlib, scipy)

Statistical hypothesis testing

Exploratory data analysis

Business-driven insights
