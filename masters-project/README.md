# Adversarial Vulnerability Analysis of Deep Neural Network–Based Intrusion Detection Systems

## 📌 Overview
This Master’s project investigates the **adversarial robustness of deep learning–based Intrusion Detection Systems (IDS)** against **gradient-based evasion attacks**.  
Although modern IDS models achieve high detection accuracy, this research demonstrates that they remain **highly vulnerable to adversarial machine learning (AML) attacks**.

The study evaluates a **Deep Neural Network (DNN)**–based IDS under **Fast Gradient Sign Method (FGSM)** and **Projected Gradient Descent (PGD)** attacks using **NSL-KDD** and **CICIDS2017** benchmark datasets.

---

## 🎯 Objectives
- Evaluate adversarial vulnerability in AI-driven IDS
- Implement **FGSM** and **PGD** evasion attacks
- Measure performance degradation under adversarial inputs
- Analyze attack success rates and feature sensitivity
- Highlight the need for adversarial defense mechanisms in IDS

---

## 🧠 Methodology
1. **Datasets**
   - NSL-KDD (legacy intrusion detection benchmark)
   - CICIDS2017 (modern real-world traffic dataset)

2. **Model Architecture**
   - Deep Neural Network (DNN)
   - ReLU activation with dropout regularization
   - Binary classification (benign vs intrusion)
   - Optimized using Adam optimizer

3. **Adversarial Attacks**
   - **FGSM (Fast Gradient Sign Method)**
   - **PGD (Projected Gradient Descent)**
   - Perturbation budget ε ranging from 0.01 to 0.20
   - White-box threat model

4. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - ROC-AUC
   - Attack Success Rate (ASR)

---

## 📊 Key Results
- Clean accuracy:
  - **NSL-KDD:** 97.80%
  - **CICIDS2017:** 98.10%
- Under adversarial attacks (ε = 0.1):
  - FGSM accuracy dropped to **79.45%**
  - PGD accuracy dropped to **75.30%**
- PGD demonstrated stronger attack capability:
  - **ASR up to 22.50%**
- Performance metrics degraded proportionally with increasing ε
- R2L and U2R attack classes showed highest vulnerability

---

## 🔐 Security Implications
- High-performing IDS models are **not inherently secure**
- Minor perturbations can cause severe misclassification
- Adversarial robustness must be treated as a **core security requirement**
- Highlights the need for:
  - Adversarial training
  - Input preprocessing
  - Ensemble and defense-aware architectures

---

## 🛠 Tools & Technologies
- Python
- Deep Neural Networks (DNN)
- FGSM & PGD adversarial attacks
- NSL-KDD & CICIDS2017 datasets
- Machine Learning Security
- Adversarial Machine Learning (AML)

---

## 📄 Project Documentation
📘 **Master’s Project Report (PDF)**  
[Click here to view the complete project report](Masters_Project_Report.pdf)

---

## 📚 Research Domain
- Cybersecurity
- Intrusion Detection Systems (IDS)
- Adversarial Machine Learning
- AI Security & Model Robustness

---

## ⚠️ Ethical Disclaimer
This project is conducted **strictly for academic and defensive research purposes**.  
All experiments aim to improve the resilience of cybersecurity systems against adversarial threats.

---

## 👨‍🎓 Author
**Tulasi Sai Charan Sharma Gaddam**  
Master’s in Cybersecurity  
Sacred Heart University, USA
