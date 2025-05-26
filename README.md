# 📡 Sensor Failure Prediction for Machine Health Monitoring

## 🧾 Project Summary

This project focuses on predictive maintenance and anomaly detection for industrial systems using time-series sensor data. By analyzing patterns in signals such as vibration, temperature, and pressure, we aim to detect early signs of machine failure and optimize maintenance strategies.

The approach mimics real-world system health monitoring for logistics warehouses, manufacturing lines, and operational equipment — closely aligned with system control and optimization in companies like Lazada.

---

## 🎯 Objectives

- Analyze and visualize sensor signal behavior over time  
- Detect anomalies and deviations from normal performance  
- Estimate mean time to failure (MTTF) and cycle length  
- Build a rule-based logic for early failure prediction  
- Support technical decision-making for predictive maintenance  

---

## 📁 Dataset

**Source:** [CMAPSS Jet Engine Sensor Dataset](https://www.kaggle.com/datasets/behrad3d/jet-engine-sensor-data)  
- Data from 100+ simulated jet engines  
- Each engine contains time-series measurements from 21 sensors  
- Includes engine ID, operating condition, and failure cycle

**Key Fields:**
- `sensor_1` to `sensor_21`: vibration, temperature, pressure, etc.  
- `cycle`: time unit of each reading  
- `unit_number`: unique engine ID  
- *(optional)* `failure_mode` for binary classification  

---

## 🧠 Skills Demonstrated

| Category             | Details                                       |
|----------------------|-----------------------------------------------|
| Programming          | Python (pandas, numpy, matplotlib, seaborn)  |
| Data Analysis        | Signal trend detection, statistical analysis  |
| Feature Engineering  | Rolling averages, z-score, sensor drift logic|
| Automation Logic     | Rule-based anomaly & failure flagging         |
| Visualization        | Time series plots, failure patterns           |
| System Thinking      | Predictive maintenance simulation             |

---

## 🛠️ Folder Structure

