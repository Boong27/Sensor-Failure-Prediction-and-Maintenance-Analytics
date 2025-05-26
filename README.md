#📡 Sensor Failure Prediction for Machine Health Monitoring
🧾 Project Summary
This project focuses on predictive maintenance and anomaly detection for industrial systems using time-series sensor data. By analyzing patterns in signals such as vibration, temperature, and pressure, we aim to detect early signs of machine failure and optimize maintenance strategies.

The approach mimics real-world system health monitoring for logistics warehouses, manufacturing lines, and operational equipment — closely aligned with system control and optimization in companies like Lazada.

🎯 Objectives
Analyze and visualize sensor signal behavior over time

Detect anomalies and deviations from normal performance

Estimate mean time to failure (MTTF) and cycle length

Build a rule-based logic for early failure prediction

Support technical decision-making for predictive maintenance

📁 Dataset
Source: CMAPSS Jet Engine Sensor Dataset

Data from 100+ simulated jet engines

Each engine contains time-series measurements from 21 sensors

Includes engine ID, operating condition, and failure cycle

Key Fields:

sensor_1 to sensor_21: vibration, temperature, pressure, etc.

cycle: time unit of each reading

unit_number: unique engine ID

(optional) failure_mode for binary classification

🧠 Skills Demonstrated
Category	Details
Programming	Python (pandas, numpy, matplotlib, seaborn)
Data Analysis	Signal trend detection, statistical summarization
Feature Engineering	Rolling average, z-score anomaly flag, sensor drift
Automation Logic	Rule-based function for failure alerts
Visualization	Sensor trends, outlier detection, cycle life plot
System Thinking	Maintenance logic, machine health classification

🛠️ Folder Structure
css
Sao chép
Chỉnh sửa
sensor-failure-prediction/
├── data/
│   └── sensor_data.csv
├── notebooks/
│   └── sensor_analysis.ipynb
├── src/
│   └── failure_logic.py
├── img/
│   ├── sensor_outliers.png
│   └── failure_flagged.png
├── reports/
│   └── predictive_maintenance_summary.pdf
└── README.md
📊 Key Analyses
🔹 Sensor Drift Detection
Calculated rolling mean and std for each sensor

Flagged segments that deviated more than 2.5σ from norm

🔹 Mean Time to Failure Estimation
Aggregated engine life cycle per unit

Calculated average run cycles before failure

🔹 Multi-Sensor Alert Logic
If 3+ sensors show critical values within 10 cycles → trigger early failure warning

Simple yet effective rule-based anomaly logic

🔹 Failure Pattern Heatmap
Correlated sensor behaviors across units approaching failure

Helps detect which sensor is most predictive

🧩 Use Cases
Department	Use
Logistics Ops (e.g. Lazada Warehouse)	Monitor conveyor systems or packaging lines for downtime risks
Maintenance Engineers	Predict optimal repair windows before actual failure
System Analysts	Build internal alert logic for recurring breakdowns
AI/IoT Developers	Prototype condition-based predictive logic using low-compute rules

🧠 Business Impact (If Applied)
⚙️ Reduce unplanned downtime by predicting faults in advance

💸 Lower maintenance costs with smarter scheduling

🔄 Improve system uptime and delivery throughput in warehouse operations

📈 Enhance transparency and reporting for system status tracking

🔭 Future Work
Integrate basic machine learning models (Random Forest) for classification

Build a dashboard using Streamlit for real-time visualization

Incorporate domain-specific thresholds for different machine types

Explore real-time implementation with industrial IoT systems

📬 Contact
Nguyen Gia Khiem
3rd-year student | Electronic Physics Technology and Informatics
🔗 github.com/Boong27 | ✉️ Giakhime2709@gmail.com
