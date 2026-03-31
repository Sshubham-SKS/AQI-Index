🌍 AQI Index Analysis Dashboard

<img width="1240" height="698" alt="Screenshot 2026-04-01 022319" src="https://github.com/user-attachments/assets/feb9bfd0-54cd-44c5-9f32-16e34e30664c" />

<img width="1241" height="698" alt="Screenshot 2026-04-01 023556" src="https://github.com/user-attachments/assets/755aa021-fa7d-417d-b204-2c699de4324b" />

An interactive Air Quality Index (AQI) Analysis Dashboard built using Power BI, Python, and DAX to monitor pollution levels, analyze environmental trends, and generate actionable insights across cities and states in India.

This project transforms raw AQI data into meaningful visualizations to support data-driven environmental awareness and decision-making.

📊 Project Overview

Air pollution is a critical global issue. This dashboard provides a comprehensive analysis of AQI data, helping users understand:

Pollution levels across cities and states
Key pollutants affecting air quality
Trends and seasonal variations
High-risk and low-risk regions

The dashboard enables interactive exploration of AQI data using filters and dynamic visuals.

🧩 Dataset Description
The dataset includes air quality measurements such as:

City / State
AQI Value
Pollutants (PM2.5, PM10, NO2, O3, CO, etc.)
Date (Year, Month)
AQI Category (Good, Moderate, Poor, Unhealthy, etc.)

⚙️ Tech Stack
Power BI → Dashboard creation & visualization
Python (Pandas) → Data cleaning & preprocessing
DAX → Measures and calculated columns
SQL (optional) → Data aggregation
🛠️ Data Engineering Approach
Data Cleaning (Python)
Removed null and inconsistent values
Standardized pollutant columns
Formatted date fields
Data Transformation
Created AQI categories based on value ranges
Aggregated data by city, state, and time
Data Modeling (Power BI)
Established relationships between tables
Optimized data model for performance
DAX Measures
Average AQI
Maximum AQI
Pollutant frequency
Category distribution

📈 Dashboard Features
🔹 KPI Overview
Average AQI
Maximum AQI
Primary Pollutant
AQI Category
🔹 City-Level Analysis
Top polluted cities
AQI comparison across cities
🔹 State-Level Analysis
Interactive map visualization
AQI distribution across India
🔹 AQI Distribution
Category-wise breakdown
Visual segmentation of air quality levels
🔹 Trend Analysis
Monthly AQI trends
Seasonal variation insights
🔹 Pollutant Analysis
Frequency of pollutants
Dominant pollution contributors

🎨 Visualization Components
KPI Cards
Bar Charts
Donut Chart
Line Chart
Map Visualization
Slicers (Year, Month, State, Area)

🔍 Key Insights
PM2.5 is the most dominant pollutant affecting air quality
Major cities show consistently high AQI levels
Significant variation exists between regions
Seasonal patterns impact AQI trends
Certain areas are identified as high-risk pollution zones

📌 Outcome
Built an interactive and scalable dashboard
Improved understanding of environmental data
Enabled data-driven insights for pollution monitoring
Demonstrated strong skills in data analysis and visualization

🚀 How to Use
Download the .pbix file from this repository
Open using Power BI Desktop
Use slicers to filter by:
Year
Month
State
Area
Explore insights through interactive visuals
📂 Project Structure
AQI-Dashboard/
│── data/
│   ├── raw_data.csv
│   ├── cleaned_data.csv
│
│── notebooks/
│   ├── data_cleaning.ipynb
│
│── dashboard/
│   ├── AQI_Dashboard.pbix
│
│── README.md
🔗 Project Demo


📌 Future Enhancements
Real-time AQI data integration (API-based)
Machine Learning model for AQI prediction
Alert system for hazardous air quality
Deployment on web dashboard

📬 Contact

If you have any questions or feedback, feel free to connect with me on LinkedIn or reach out!

⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
