# 🤖 Reinforcement Learning – Upper Confidence Bound (UCB)

This repository contains a practical implementation of the **Upper Confidence Bound (UCB)** algorithm, a Reinforcement Learning strategy used to solve the **multi-armed bandit problem**. The project demonstrates how UCB balances exploration and exploitation to optimize decision-making over time.

---

## 📁 Repository Structure

```
├── upper_confidence_bound.ipynb   # Jupyter Notebook with UCB implementation
├── Ads_CTR_Optimisation.csv       # Dataset used for ad selection simulation
├── README.md                      # Project documentation
```

---

## 🚀 Project Overview

The objective of this project is to:
- Implement the **Upper Confidence Bound (UCB)** algorithm from scratch
- Simulate an online advertising scenario
- Maximize rewards by selecting the best-performing ad over time
- Visualize ad selection frequency and learning behavior

This is a classic Reinforcement Learning example widely used in **online advertising, recommendation systems, and A/B testing**.

---

## 🧠 Algorithm Used

- **Upper Confidence Bound (UCB)**
  - Addresses the exploration vs. exploitation trade-off
  - Selects actions based on confidence intervals
  - Guarantees logarithmic regret under theoretical assumptions

---

## 📊 Dataset

**Ads_CTR_Optimisation.csv** simulates user clicks on different ads:
- Each column represents an ad
- Each row represents a user interaction
- Values indicate whether an ad was clicked (1) or not (0)

The dataset allows offline simulation of an online learning problem.

---

## 🛠️ Technologies & Libraries

- Python  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Matplotlib  

---

## 📈 Results

- Identification of the most effective ad
- Visualization of ad selection frequency
- Demonstration of how UCB converges to optimal actions

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   ```
2. Open the notebook:
   ```bash
   jupyter notebook upper_confidence_bound.ipynb
   ```
3. Run all cells to reproduce the results.

---

## 📌 Use Cases

- Online advertising optimization
- Recommendation systems
- Reinforcement Learning fundamentals
- Machine learning portfolio project

---

## 📄 License

This project is for educational and demonstration purposes.
