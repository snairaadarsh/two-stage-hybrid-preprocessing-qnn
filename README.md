# A Two-Stage Hybrid Preprocessing Framework for Quantum Neural Networks

## Overview
Quantum Neural Networks (QNNs) are emerging as a promising paradigm for next-generation cybersecurity systems, particularly for Distributed Denial-of-Service (DDoS) intrusion detection where robustness, accuracy, and scalability are critical. However, QNN performance is highly sensitive to data distribution due to the reliance of quantum feature encoding on rotation-based gate mappings.

This repository accompanies the research work **“A Two-Stage Hybrid Preprocessing Framework for Quantum Neural Networks”**, which proposes a preprocessing and feature engineering strategy specifically designed to stabilize and enhance QNN learning pipelines for real-world network traffic data.

---

## Key Idea
The central insight of this work is that **effective preprocessing is essential for quantum machine learning**. Poorly scaled or highly skewed features can result in:
- Saturation of quantum rotation angles  
- Vanishing or unstable quantum gradients  
- Degraded optimization and classification performance  

To address these challenges, a **two-stage hybrid preprocessing pipeline** combined with **hybrid feature selection** is introduced to produce quantum-friendly feature representations.

---

## Methodology Summary

### Two-Stage Hybrid Preprocessing
1. **RobustScaler** – mitigates the impact of outliers common in network traffic data  
2. **Logarithmic Transformation** – corrects skewness and heavy-tailed feature distributions  
3. **StandardScaler** – performs final normalization aligned with quantum rotational encodings  

### Hybrid Feature Selection
- Mutual Information-based feature ranking  
- Random Forest-based feature refinement  
- Retention of the most quantum-informative features  

---

## Experimental Scope
The proposed framework is evaluated under multiple realistic conditions, including:
- Binary DDoS classification  
- Multiclass balanced binary intrusion detection  
- Balanced and highly imbalanced datasets  
- Cross-dataset transfer learning  
- Single-feature QNN expressiveness analysis  

All experiments are conducted using curated subsets derived from the CIC-DDoS2019 dataset.

---

---

## Code Availability
The complete implementation—including preprocessing pipelines, feature selection modules, quantum circuit construction, QNN training procedures, and experimental configurations—**will be released publicly after publication**.

At present, the **manuscript is under final preparation**, and code release will follow acceptance to ensure compliance with publication and reproducibility guidelines.

---

## Publication Status
- **Manuscript:** Under final preparation  
- **Code & Experiment Scripts:** To be released after publication  
- **Curated Dataset Subsets:** To be released after publication  

---

