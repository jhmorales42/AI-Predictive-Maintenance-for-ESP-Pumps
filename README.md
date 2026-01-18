# AI-Predictive-Maintenance-for-ESP-Pumps

## Overview
This project implements a Machine Learning solution using the **Isolation Forest** algorithm to monitor the health of Electro-Submersible Pumps (ESP). By analyzing historical sensor data (Pressure, Temperature, Vibration), the system establishes a "Normal Operation" baseline and detects early signs of mechanical or electrical failure.

## Technical Approach
1. **Baseline Learning**: The model is trained on healthy operational data to define an "Anomalous Score" threshold.
2. **Real-time Monitoring**: The health monitor processes incoming data and calculates a smoothed health score.
3. **Predictive Analytics**: The system successfully detected failures with a lead time of **5.2 days**, allowing for proactive maintenance planning.
4. **Root Cause Analysis (RCA)**: Automatic identification of the sensor driving the anomaly (e.g., Motor Temperature or Vibration).

## Key Results
- **Lead Time Gained**: 124 hours of advance warning.
- **Precision**: Effectively filtered operational noise using a 2-Sigma statistical threshold.

## Requirements
To run this project, install the dependencies:
`pip install -r requirements.txt`
