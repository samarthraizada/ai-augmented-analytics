## Project: WHS Anomaly Detection (Isolation Forest)
# Objective

Detect operational anomalies across multiple fulfillment sites using Isolation Forest.
Dataset simulates real-world WHS patterns (hours, incidents, overtime, staffing, idle time, etc.).

## Project Structure
project_01_anomaly_detection/
│
├── data/
│   ├── anomaly_output.csv           # Final model output
│
├── notebooks/
│   ├── anomaly_detection_starter.ipynb
│
├── src/
│   ├── (future Python modules)
│
├── visuals/
│   ├── incident_anomalies.png       # Visualization
│
└── README.md

## Techniques Used

Synthetic WHS dataset generation

Anomaly injection (spikes, outliers, corrupted data)

Feature scaling (StandardScaler)

Isolation Forest modeling

Anomaly score computation

Visualization with Matplotlib

## Results

~10% anomalies detected

Captured injury spikes, staffing dips, extreme idle times

Clean visualization saved in visuals/

Final dataset exported in data/