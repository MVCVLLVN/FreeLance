# 🧠 Credit Risk Decision Tree — Manual ID3 Implementation

A hands-on project demonstrating how to manually build a **Decision Tree Classifier** using the **ID3 algorithm**. This mini-project is based on a credit risk dataset with categorical features and walks through:

- Calculating entropy,
- Computing information gain,
- Building the decision tree by hand,
- Classifying new examples using the constructed tree.

This project is part of an AI/machine learning coursework assignment.

---

## 📊 Dataset Overview

The dataset contains 14 training examples with the following categorical features:

- `Credit History` — {good, bad, unknown}
- `Debt` — {low, high}
- `Collateral` — {none, adequate}
- `Credit Risk` — target: {low, high}

---

## 🧮 Entropy & Information Gain

Initial entropy:

\[
H(S) = 0.985
\]

Information gain by attribute:

| Attribute       | Information Gain |
|----------------|------------------|
| Credit History | **0.638** ✅     |
| Collateral     | 0.124            |
| Debt           | 0.061            |

---


Visualized using `networkx` + `matplotlib`.

---

## 📌 Classification of New Cases

| No | Credit History | Debt | Collateral | Predicted Credit Risk |
|----|----------------|------|------------|------------------------|
| 15 | good           | high | adequate   | ✅ low                 |
| 16 | unknown        | low  | adequate   | ✅ low                 |

---

## 📦 Requirements

This project uses:

- Python ≥ 3.7
- matplotlib
- networkx

You can install dependencies via:

```bash
pip install matplotlib networkx



