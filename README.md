# Machine Learning Sandbox

A centralized, engineering-focused repository dedicated to mastering machine learning principles through hands-on implementation. This repository documents my journey from foundational statistical models to advanced deep learning architectures, emphasizing clean code, reproducible experiments, and rigorous evaluation.

---

## 🚀 Repository Core Objectives

* **Algorithmic Mastery:** Implementing core ML models from scratch to deeply understand the underlying mathematics before leveraging high-level abstractions.
* **Production-Ready Pipelines:** Adhering to robust software engineering patterns for data preprocessing, feature engineering, and model evaluation.
* **Reproducible Research:** Utilizing deterministic seeding, versioned environments, and structured experiment logging to ensure consistent metrics.

---

## 🛠️ Tech Stack & Frameworks

| Category | Tools & Libraries |
| :--- | :--- |
| **Core Language** | Python 3.10+ |
| **Data & Analytics** | NumPy, Pandas, Scikit-Learn |
| **Deep Learning** | PyTorch / TensorFlow |
| **Visualization** | Matplotlib, Seaborn |
| **Environment** | Conda / Virtualenv, Jupyter Notebooks |

---

## 📁 Repository Structure

```text
├── .gitignore
├── README.md
├── requirements.txt          # Reproducible package dependencies
├── notebooks/                # Exploratory Data Analysis (EDA) & Prototyping
│   └── 01_exploratory_analysis.ipynb
├── src/                      # Production-grade, modular source code
│   ├── __init__.py
│   ├── data_pipeline.py      # Ingestion, cleaning, and preprocessing scaling
│   ├── models.py             # Model architectures and training loops
│   └── evaluate.py           # Validation metrics (ROC-AUC, F1, Confusion Matrix)
└── models/                   # Serialized weights and artifacts (.pkl, .pt)
