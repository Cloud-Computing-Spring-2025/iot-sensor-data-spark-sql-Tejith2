# IoT Sensor Data Analysis using Spark SQL

This project performs data analysis on IoT sensor readings using PySpark. The analysis covers filtering, aggregation, time-based patterns, ranking, and pivoting.

## 📁 Tasks Overview

### 🟢 Task 1: Load & Basic Exploration
- Loaded `sensor_data.csv`
- Displayed 5 rows
- Counted total records: `10`
- Extracted distinct locations

📤 Output: `task1_output.csv`

---

### 🟢 Task 2: Filtering & Aggregations
- Filtered temperature between 18°C and 30°C
- In-range count: `7`
- Out-of-range count: `3`
- Grouped by location to compute average temperature & humidity

📤 Output: `task2_output.csv`

---

### 🟢 Task 3: Time-Based Analysis
- Converted string to timestamp
- Extracted `hour_of_day`
- Grouped by hour and calculated average temperature

📤 Output: `task3_output.csv`

---

### 🟢 Task 4: Ranking Sensors
- Computed `avg_temp` for each `sensor_id`
- Ranked using `dense_rank()` (descending)

📤 Output: `task4_output.csv`

---

### 🟢 Task 5: Pivot Table
- Created pivot table with `location` vs. `hour_of_day`
- Observed hottest period:  
  ➤ **BuildingA_Floor1 at 8 AM – 34.5°C**

📤 Output: `task5_output.csv`

---

## ✅ Technologies Used

- Apache Spark (PySpark)
- Spark SQL
- Python 3.11 (via Anaconda)
- macOS (Local Execution)

---

# iot-sensor-data-spark-sql
