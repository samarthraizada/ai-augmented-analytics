# Project 01 — KPI Anomaly Detection for Safety Metrics

This project simulates a **Workplace Health & Safety (WHS)** analytics environment.  
We generate synthetic site-level KPIs and apply anomaly detection to surface 
high-risk patterns.

---

## Goals
- Create synthetic WHS-style data  
- Compute KPIs (RIR, LTIR, SIR, etc.)  
- Detect anomalies using **Isolation Forest**  
- Produce clear visualizations for stakeholders  

---

## Structure
project_01_anomaly_detection/
├── data/
├── notebooks/
├── src/
├── models/
└── visuals/

## Setup

```bash
pip install pandas numpy scikit-learn matplotlib seaborn