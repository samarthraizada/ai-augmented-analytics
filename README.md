# ai-augmented-analytics
AI-augmented analytics systems: anomaly detection, LLM SQL agent, and deepfake detection pipelines
# AI-Augmented Analytics

This repository contains a set of **AI-augmented analytics projects** that bring together
analytics engineering, data modeling, anomaly detection, and modern AI/LLM-driven analysis.

The focus areas include:
- **KPI anomaly detection** on WHS-style metrics  
- An **LLM-powered SQL analytics agent**  
- A **deepfake detection pipeline** for trust & safety–style scenarios  

---

## Projects

### 1. `project_01_anomaly_detection` — KPI Anomaly Detection
- Synthetic WHS-style dataset: sites, hours worked, incidents, KPIs  
- Isolation Forest anomaly detection for outlier sites/weeks  
- Visualizations for risk surfaces, trends, and anomaly flags  

### 2. `project_02_llm_sql_agent` — LLM SQL Assistant
- Natural-language → SQL generation  
- Schema-aware prompting + validation  
- Executes queries and returns interpreted results  
- Demonstrates LLM-augmented analytics  

### 3. `project_03_deepfake_detection` — Deepfake Detection Pipeline
- Face preprocessing + CNN/ViT-based classifier  
- Evaluation metrics (precision, recall, false positives)  
- Inference-style script simulating a lightweight production workflow  

---

## Tech Stack

- **Python**, **SQL**
- **pandas**, **numpy**, **scikit-learn**, **matplotlib**, **seaborn**
- **PyTorch** (deepfake project)
- **LangChain**, **OpenAI API**
- Environments: `venv` / `conda`  

---

## Getting Started

```bash
git clone https://github.com/<your-username>/ai-augmented-analytics.git
cd ai-augmented-analytics
pip install -r requirements.txt  # (coming soon)