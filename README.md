# Truck-Fleet-Risk-Analysis-using-Hadoop

The project centers on evaluating driver safety and operational risk for a fictional nationwide logistics company, AZ National Trucking (ANT). The objective is to improve road safety and regulatory compliance by identifying drivers and vehicle models that exhibit high-risk behavior. By analyzing driving patterns such as speeding, harsh braking, unsafe following distance, and lane deviations, the project helps uncover critical risk indicators.
Leveraging the Hadoop ecosystem for large-scale data processing and Tableau for visualization, the solution transforms raw fleet and location data into actionable safety insights that can help reduce accidents and operational losses.



🔍 Key Workflow Steps
- Data Acquisition:
The project uses publicly available datasets containing geographic information (latitude, longitude, city, state) along with fleet-level metrics such as mileage, fuel usage, driving events, and driver identifiers. These datasets are enhanced with calculated safety indicators derived from driving behavior.
- Data Engineering & Processing:
Data is ingested into the Hadoop ecosystem using HDFS for distributed storage. Hive is used to structure the data into queryable tables for drivers, vehicles, events, and geographic mappings. The processing layer prepares clean, analytics-ready datasets by aggregating events and computing risk scores.
- Risk Analysis & Visualization:
Each driver is assigned a composite risk score based on the frequency and severity of unsafe driving events. Drivers exceeding a predefined risk threshold (greater than 7) are categorized as high-risk. Tableau dashboards visualize driver risk profiles, vehicle model performance, and regional safety trends, highlighting accident-prone locations and recurring unsafe behaviors.



📈 Key Findings
- High-Risk Driver Identification:
Driver A97 emerges as the highest-risk individual, with repeated overspeeding and lane departure incidents.
- Vehicle Model Insights:
Oshkosh trucks record the highest overall risk score, while Ford vehicles show the greatest number of safety-related events.
- Behavioral Trends:
Speeding and unsafe following distance are the most frequent contributors to elevated risk.
- Geographical Patterns:
Certain cities, including Hollister, show higher concentrations of incidents, with lane departures being the leading cause.



📊 Technology Stack
- Hadoop Ecosystem – Scalable big data processing
- HDFS – Distributed data storage
- Hive – Data modeling and analytical queries
- Tableau – Interactive dashboards and visual analytics
- Python – Data preprocessing, transformations, and scripting
- JDBC / ODBC – Integration between Hadoop and Tableau



💡 Business Value
- Actionable Risk Insights: Enables proactive identification of unsafe drivers and vehicles through data-driven risk scoring.
- Enhanced Road Safety: Supports targeted driver training, policy enforcement, and preventive measures to reduce accidents.
- Operational Optimization: Improves fleet utilization, lowers insurance exposure, and strengthens compliance with transportation regulations.



This project illustrates how big data and analytics can be applied to real-world transportation challenges, demonstrating the power of data engineering and visualization in improving safety, efficiency, and decision-making within the logistics industry.
