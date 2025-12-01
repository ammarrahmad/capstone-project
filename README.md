# Fair Multi-Objective Deep Q-Learning (F-MDQ)
### Implementation for the Capstone Project under Prof. Samrat Mondal  
**Paper Implemented:**  
*Learning Fair Pareto-Optimal Policies in Multi-Objective Reinforcement Learning*  
Umer Siddique, Peilang Li, Yongcan Cao (2020)

---

## 📌 Overview
This repository contains an implementation of the **F-MDQ algorithm**, a fairness-aware extension of Multi-Objective Deep Q-Learning built upon the Envelope method (Yang et al., 2019).  
The project focuses on learning **fair Pareto-optimal policies** in Multi-Objective Reinforcement Learning (MORL) by optimizing the **Generalized Gini Welfare (GGF)** function.

This work was completed as part of my **B.Tech AI & DS Capstone Project** at **IIT Patna**, under the supervision of **Prof. Samrat Mondal**.

---

## 🧠 Key Features
- Complete implementation of **F-MDQ** with GGF-based welfare optimization  
- Training environment: **Resource Gathering MOMDP**  
- Preference-resampling scheme inspired by HER for improved sample efficiency  
- Full computation of fairness metrics:
  - **Generalized Gini Welfare (GGF)**
  - **Coefficient of Variation (CV)**
  - **Min–Max resource fairness**
- Comparison with **Envelope Q-Learning** (baseline)
- Logging and saving of Q-networks, returns, and learned policies

---

## 📁 References
- U. Siddique, P. Li, Y. Cao, Learning Fair Pareto-Optimal Policies in Multi-Objective Reinforcement Learning, 2020.
- R. Yang, E. Wiecek, B. C. da Silva, A Generalized Algorithm for Envelope-Based Multi-Objective RL, 2019.
