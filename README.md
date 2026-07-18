# 🛡️ CyberGuard AI
### Autonomous AI-Powered Cybersecurity Threat Detection & Incident Response Agent

<p align="center">
  <b>Real-Time Anomaly Detection • Explainable AI • Automated Mitigation • Interactive SOC Dashboard</b>
</p>

---

## 📌 Overview

CyberGuard AI is an end-to-end AI-powered cybersecurity agent designed to detect network anomalies, classify cyber threats, explain model predictions, and automatically recommend mitigation strategies.

The project combines Machine Learning, Explainable AI (SHAP), automated incident response, forensic PDF generation, and an interactive Gradio dashboard into a single security operations workflow.

Instead of relying on static datasets, CyberGuard AI generates realistic SIEM (Security Information and Event Management) telemetry that simulates enterprise network traffic, intrusion attempts, brute-force attacks, DDoS activity, and data exfiltration behavior.

---

# 🚀 Key Features

✅ High-Fidelity SIEM Log Generator

- Generates 6,000 realistic enterprise security logs
- Simulates multiple network zones
- Simulates attacker and normal user behavior
- Creates balanced multi-class cybersecurity datasets

---

✅ Intelligent Feature Engineering

- Traffic Intensity Index
- Legacy Vulnerability Detection
- One-Hot Encoding
- Security Feature Extraction
- Automated Data Processing Pipeline

---

✅ Machine Learning Threat Detection

- Random Forest Classifier
- GridSearchCV Hyperparameter Optimization
- Multi-Class Threat Classification
- High Accuracy Prediction
- Balanced Class Training

Threat Classes:

- 🟢 Normal Activity
- 🟠 Suspicious Reconnaissance / Exploitation
- 🔴 Critical Compromise

---

✅ Explainable AI

CyberGuard AI explains every prediction using SHAP.

Visual explanations include:

- Feature Contribution Analysis
- SHAP Importance Graphs
- Top Security Indicators
- Threat Reasoning Visualization

---

✅ Automated Incident Response

Based on predicted threat severity, CyberGuard AI automatically recommends security actions.

Examples include:

- Rate Limiting
- MFA Enforcement
- Session Isolation
- Quarantine VLAN
- BGP Null Routing
- Process Termination
- Memory Dump Collection
- Forensic Investigation

---

✅ Interactive SOC Dashboard

Built using Gradio.

Features:

- Interactive Threat Simulation
- Real-Time Predictions
- Threat Severity Score
- Automated Mitigation Recommendations
- SHAP Visualization
- PDF Report Download

---

✅ Automated Forensic Report Generation

The system automatically creates professional PDF incident reports containing:

- Incident Summary
- Host Information
- Threat Score
- Risk Classification
- Mitigation Strategy
- Security Metrics

---

# 🏗 Project Architecture

```
SIEM Log Generator
        │
        ▼
Feature Engineering
        │
        ▼
Machine Learning Model
        │
        ▼
Threat Classification
        │
        ▼
Explainable AI (SHAP)
        │
        ▼
Automated Mitigation Engine
        │
        ▼
Forensic PDF Generator
        │
        ▼
Interactive Gradio Dashboard
```

---

# 📊 Machine Learning Pipeline

Dataset Generation

↓

Feature Engineering

↓

One-Hot Encoding

↓

Train/Test Split

↓

Random Forest Classifier

↓

GridSearchCV Optimization

↓

Threat Prediction

↓

SHAP Explainability

↓

Incident Response

↓

PDF Report Generation

---

# 📈 Model Performance

The optimized Random Forest classifier achieved excellent performance across all three threat classes.

### Performance Summary

| Metric | Score |
|---------|-------|
| Accuracy | **99%** |
| Precision | High |
| Recall | High |
| F1 Score | High |

---

# 📂 Project Structure

```
CyberGuardAI/
│
├── CyberGuardAI.ipynb
├── CyberGuardAI_Architecture.svg
├── shap_security_vector_contribution.png
├── CyberGuard_Incident_Forensics_Report.pdf
├── README.md
└── requirements.txt
```

---

# 🛠 Technologies Used

### Programming Language

- Python

### Machine Learning

- Scikit-learn
- Random Forest
- Gradient Boosting

### Explainable AI

- SHAP

### Data Processing

- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn
- SVGWrite

### User Interface

- Gradio

### PDF Reports

- ReportLab

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/shiksha5245/CyberGuard-AI.git
```

Move into the project

```bash
cd CyberGuardAI
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch the notebook

```bash
jupyter notebook
```

---

# ▶️ Running the Project

Open

```
CyberGuardAI.ipynb
```

Run every notebook cell sequentially.

The notebook will:

- Generate synthetic SIEM logs
- Train the AI model
- Evaluate performance
- Display analytics
- Generate SHAP explanations
- Produce forensic PDF reports
- Launch the Gradio dashboard

---

# 🎯 Dashboard Outputs

The Gradio dashboard provides:

- Threat Severity Score
- Predicted Threat Level
- Automated Mitigation Actions
- SHAP Feature Explanation
- Downloadable Incident Report PDF

---

# 📊 Visualizations

The notebook generates:

- Confusion Matrix
- Feature Importance Plot
- SHAP Explanation Plot
- SVG Architecture Diagram

---

# 🎯 Future Improvements

- Live SIEM Integration
- Real-Time Log Streaming
- IDS/IPS Integration
- Threat Intelligence APIs
- Docker Deployment
- Kubernetes Support
- Cloud Deployment
- User Authentication
- Database Logging
- REST API Support

---

# 👨‍💻 Author

Developed as an AI-powered cybersecurity project demonstrating:

- Machine Learning
- Explainable AI
- Threat Detection
- Incident Response Automation
- Security Analytics
- Interactive AI Applications

---

# ⭐ If you found this project useful, consider giving it a Star!
