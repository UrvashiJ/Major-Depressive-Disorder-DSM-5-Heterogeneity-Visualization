# 🧠 MDD Heterogeneity Visualization Notebook

A Python-based notebook to **quantify and visualize the diagnostic heterogeneity of Major Depressive Disorder (MDD)** using DSM-5 criteria.

---

## 📌 Overview

Major Depressive Disorder (MDD) is defined by:

* At least **5 out of 9 symptoms**
* Including **at least one core symptom**:

  * Depressed Mood
  * Anhedonia

This leads to a large number of **valid symptom combinations**, highlighting the **heterogeneous nature of the diagnosis**.

This notebook:

* Generates all valid DSM-5 symptom profiles
* Converts them into a structured dataset
* Visualizes the combinatorial structure using multiple methods

---

## 🚀 Features

### ✅ Data Generation

* Enumerates all valid symptom combinations
* Applies DSM-5 constraint (≥5 symptoms + ≥1 core)

### 📊 Visualizations

* **Bar Chart** → Symptom frequency across all valid profiles
* **Heatmap** → Symptom co-occurrence matrix
* **Network Graph** → Structural relationships between symptoms
* **UpSet Plot (optional)** → Intersection-based visualization of combinations

### 💾 Output

* Exports dataset as `mdd_symptom_profiles.csv` for further analysis

---

## 🛠️ Installation

Install required dependencies:

```bash
pip install pandas matplotlib networkx seaborn upsetplot
```

---

## ▶️ Usage

1. Open the notebook in Jupyter / JupyterLab / Google Colab
2. Run all cells sequentially
3. Explore the generated visualizations

---

## 🧠 Conceptual Goal

This project helps demonstrate that:

> MDD is not a single uniform condition, but a **combinatorial space of symptom profiles**.

Different individuals can:

* Share few symptoms
* Yet meet the same diagnostic criteria

---

## 📈 Key Insights You Can Explore

* Total number of valid diagnostic profiles
* Which symptoms are most vs least common
* Which symptoms frequently co-occur
* Whether clusters of symptoms emerge

---

## 🔬 Possible Extensions

* Clustering symptom profiles (identify subtypes)
* Dimensionality reduction (PCA, t-SNE)
* Simulating patient populations
* Comparing DSM-5 with alternative diagnostic frameworks

---

## 📁 File Structure

```
.
├── notebook.ipynb
├── mdd_symptom_profiles.csv
└── README.md
```

---

## ⚠️ Notes

* The full combinatorial space grows rapidly with more symptoms
* Visualizations represent **structure**, not clinical prevalence
* This is a **conceptual / computational model**, not patient data

---

## 📜 License

MIT License (or specify your preferred license)

---

## 🙌 Acknowledgments

Inspired by research in:

* Psychiatric heterogeneity
* Network models of mental disorders
* Combinatorial diagnostics

---
