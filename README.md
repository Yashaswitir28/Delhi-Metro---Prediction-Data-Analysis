# Delhi-Metro---Prediction-Data-Analysis

# Project Overview
This project utilizes Python and Power BI to optimize Delhi Metro operations by analyzing passenger flow, predicting demand, optimizing train schedules, and delivering actionable insights through data visualization and machine learning models. The goal is to enhance operational efficiency, reduce wait times, and improve the commuter experience.

# Dataset Overview
The dataset consists of multiple files detailing various aspects of the Delhi Metro system, structured as follows:

1️⃣ Agency – Details about DMRC, including name, URL, and contact information.

2️⃣ Calendar – Specifies service schedules for weekdays, weekends, and valid operation dates.

3️⃣ Routes – Information on metro routes, including short/long names, types, and descriptions.

4️⃣ Shapes – Geographical coordinates representing the exact paths of metro lines.

5️⃣ Stop Times – Timetables listing arrival and departure times for each stop.

6️⃣ Stops – Location data for metro stops, including latitude and longitude.

7️⃣ Trips – Links trips to routes, including trip identifiers and route IDs.

These datasets offer a comprehensive view of Delhi Metro operations, enabling deep analysis and optimization.

# Problem Statement 🔍
Despite having a vast network and frequent services, the Delhi Metro faces challenges such as:

✅ Overcrowding during peak hours 🚉

✅ Uneven service distribution across routes 🛤️

✅ Longer wait times at high-traffic stations ⏳

The primary goal is to optimize metro operations by aligning train frequencies and capacities with demand across different routes and times. This will lead to:

✔️ Better service distribution

✔️ Reduced waiting times

✔️ Efficient use of resources

✔️ Enhanced commuter experience

# 🔬 Our Python-Based Prediction Model
To address these challenges, we developed a Machine Learning-based Passenger Flow Prediction Model using Python.

🔹 Steps in Model Development

✅ Data Preprocessing : 
Converted arrival times into hourly trends and identified weekday vs. weekend patterns.
Estimated passenger flow using trip frequency data.
Adjusted demand for peak hours (10 AM - 4 PM) 📈.

✅ Feature Engineering : 
Created key features: stop ID, hour of the day, weekday/weekend indicator, peak hour flag, and rolling average passenger count.
Applied One-Hot Encoding and Label Encoding where necessary.

✅ Model Training & Optimization : 
Used a Random Forest Regressor with GridSearchCV for hyperparameter tuning.
Applied train-test split and standardization to improve model accuracy.
Introduced slight random noise to simulate real-world variations.

✅ Performance Evaluation: 
Achieved high prediction accuracy using R² Score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
Validated results against real-world metro data to ensure robustness.

✅ Passenger Flow Prediction System : 
Allows users to input a stop ID, time of the day, and day of the week.
Predicts expected passenger count based on historical trends and real-time adjustments.
Helps in dynamic scheduling by identifying overloaded and underutilized routes.

# 📊 Power BI Analysis & Dashboards
To complement our machine learning model, we created interactive Power BI dashboards to visualize key insights from the Delhi Metro data.

# Key Power BI Metrics & Visualizations

✅ Trip Frequency Analysis – A bar chart displaying scheduled trips for each day of the week, highlighting peak and low-demand days.

✅ Route Complexity & Transfer Hubs – A scatter plot showcasing how many routes pass through each stop, identifying key interchange stations.

✅ Passenger Flow Trends – Time-based analysis categorizing ridership patterns: Early Morning, Morning Peak, Midday, Evening Peak, Late Evening.

✅ Trip Intervals Throughout the Day – A bar chart illustrating how trip frequency changes across different time slots.

✅ Key Metrics Summary:

These dashboards provide real-time insights for metro planners to optimize scheduling, reduce congestion, and improve passenger experience.

# 🚆 Conclusion
This project demonstrates the power of data-driven solutions in public transportation. By integrating machine learning, Power BI, and predictive analytics, we provide actionable insights to enhance metro operations. Our passenger flow prediction model enables real-time demand-based scheduling, while Power BI dashboards visualize key trends for better decision-making.

# 🌟 Expected Impact:

🚀 Real-time passenger flow predictions for dynamic train frequency adjustments.

🚀 Reduced overcrowding through optimized train deployment.

🚀 Improved service efficiency and commuter satisfaction using data-driven strategies.

With this AI-powered approach, we aim to create a smarter, more efficient Delhi Metro system for millions of daily commuters. 🚇✨
