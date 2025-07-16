# nyc-taxi-pyspark-analysis
# NYC Taxi Trip Analysis using PySpark 🚖

This project demonstrates how to process and analyze a large real-world dataset using **PySpark**, a big data processing framework. The analysis focuses on the **NYC Yellow Taxi Trip dataset**, showcasing how PySpark enables scalable and efficient computation on large datasets.
---
## Objective

- Perform **big data processing** using PySpark
- Derive insights such as average fare, trip distance, duration, and trip frequency
- Demonstrate **scalability and performance** in handling large datasets
- Visualize trends such as **trip distribution by hour**

## Key Analysis Performed

- Data cleaning (removal of nulls, filtering invalid trips)
- Calculation of:
  - Total valid trips
  - Average fare
  - Average trip distance
  - Average trip duration
- Grouped insights:
  - Top pickup locations (by GPS)
  - Trips by passenger count
  - Trip frequency by hour
-  Simple time-of-day plot using `matplotlib`
