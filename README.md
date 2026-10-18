# AI-Based 3-Phase Induction Motor Fault Diagnosis

An end-to-end pipeline for modeling 3-phase induction motor dynamics, generating transient operational datasets, and training machine learning models for automated condition-based anomaly detection.

## 📌 Overview
Detecting mechanical and electrical faults early in industrial induction motors prevents catastrophic failures. This project models motor dynamics under healthy and faulty states using MATLAB/Simulink, extracts transient signals, and evaluates classification/anomaly detection pipelines using Python.

## 🛠️ Tech Stack & Tools
* **Simulation:** MATLAB, Simulink
* **Data Processing & ML:** Python (NumPy, SciPy, Scikit-learn / Pandas)
* **Domains:** Electric Drives, Condition Monitoring, Machine Learning

## ⚙️ Key Workflow & Implementation
1. **Dynamic Modeling:** Modeled a 3-phase induction motor in Simulink to simulate electrical and mechanical behaviors.
2. **Dataset Generation:** Extracted transient current, speed, and torque profiles across various operating conditions for both healthy and fault-state scenarios.
3. **Feature Engineering & ML Training:** Processed raw motor dynamic data to train machine learning classifiers capable of automated anomaly detection.
4. **Classical Benchmark Evaluation:** Validated phase-plane trajectories and controller responses on non-linear benchmark systems (Inverted Pendulum, Ball & Beam).

