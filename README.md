# LogDetectX  
### Multi-Model Log Mining & Anomaly Detection System with Consensus Learning

Modern distributed systems generate massive volumes of unstructured log data, making manual monitoring inefficient and error-prone. Detecting anomalies in such logs is critical for ensuring system reliability, security, and fault diagnosis.

**LogDetectX** is an end-to-end intelligent pipeline that performs:
- Log Parsing (Drain and Spell) & Template Mining  
- Feature Extraction from Structured Logs  
- Multi-Model Anomaly Detection  
- Consensus Learning (Ensemble-based Decision Making)  

---

## Key Idea

Instead of relying on a single model, LogDetectX combines predictions from multiple anomaly detection algorithms (e.g., Isolation Forest, LOF, KNN, PCA, Autoencoder, etc.) and applies **majority voting** to produce a robust and reliable anomaly decision.

---

## Pipeline Overview

1. **Log Collection**  
   Raw system logs (e.g., HDFS logs)

2. **Log Parsing**  
   Convert unstructured logs into structured templates using log mining techniques (e.g., Drain, Spell)

3. **Feature Engineering**  
   Extract meaningful features such as:
   - Event frequency
   - Sequence patterns
   - Temporal features
   - Statistical features

4. **Anomaly Detection Models**  
   Apply multiple models:
   - K-Means  
   - Isolation Forest  
   - Local Outlier Factor (LOF)  
   - HBOS  
   - KNN  
   - PCA  
   - GMM  
   - Autoencoder  
   - Self-Organizing Maps (SOM)

5. **Consensus Learning**  
   Combine model outputs using **majority voting** to improve detection robustness

---

## Motivation

- Logs are **high-volume, high-velocity, and unstructured**
- Single models are often **unstable or biased**
- Ensemble approaches improve:
  - Accuracy  
  - Robustness  
  - Generalization  

---

## Applications

- Intrusion Detection  
- System Failure Detection  
- System Monitoring & Observability  
- Distributed Systems (HDFS, Cloud Logs)

---

## Highlights

- End-to-end pipeline from raw logs → anomaly prediction  
- Supports multiple ML & deep learning models  
- Consensus-based decision system  
- Modular and extensible design  

---

## Future Work

- Real-time streaming anomaly detection  
- LLM-based log understanding  
- Explainable anomaly detection  
- Integration with monitoring dashboards  

---
📌 Developed by: Sarthak Kalia & et al.
