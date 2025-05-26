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

**Source:** [CMAPSS Jet Engine Simulated Data](https://www.kaggle.com/datasets/palbha/cmapss-jet-engine-simulated-data ) 
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


---

## 📊 Key Analyses

### 🔹 Sensor Drift Detection
- Calculated rolling mean and std for each sensor  
- Flagged segments that deviated more than 2.5σ from normal pattern  

### 🔹 Mean Time to Failure Estimation
- Aggregated engine life cycle per unit  
- Computed average operational cycles before failure  

### 🔹 Multi-Sensor Alert Logic
- If 3+ sensors exceed thresholds within 10 cycles → early warning  
- Implemented rule-based alert using Python logic  

### 🔹 Failure Pattern Heatmap
- Correlated sensor behaviors across units prior to failure  
- Identified most predictive sensors based on late-cycle trends  

---

## 🧩 Use Cases

| Department              | Use Case Description                                                                 |
|-------------------------|----------------------------------------------------------------------------------------|
| Logistics Operations    | Monitor conveyor/packing systems in warehouse for early malfunction detection        |
| Maintenance Engineers   | Predict optimal servicing intervals based on real usage instead of fixed schedules   |
| System Analysts         | Build internal alert systems for asset health                                        |
| AI/IoT Engineers        | Prototype logic-based predictive systems for industrial IoT platforms                |

---

## 💼 Business Impact

- ⚙️ Reduce unplanned downtime through early fault detection  
- 💸 Lower repair costs via smarter maintenance planning  
- 🔄 Increase uptime and throughput in warehouse operations  
- 📈 Support transparency in system performance reporting  

---

## 🔭 Future Work

- Integrate ML classifiers (Random Forest, XGBoost)  
- Build Streamlit dashboard for real-time visualization  
- Add failure mode classification (optional Kaggle labels)  
- Explore real-time use with IoT pipeline & MQTT simulation  

---

## 📬 Contact

**Nguyen Gia Khiem**  
3rd-year BSc student – Electronic Physics Technology and Informatics  
📍 Ho Chi Minh City, Vietnam  
🔗 [github.com/Boong27](https://github.com/Boong27)  
✉️ Giakhiem@gmail.com  

---

![image](https://github.com/user-attachments/assets/a57ae425-19d9-4f50-8067-161cf1d22465)

