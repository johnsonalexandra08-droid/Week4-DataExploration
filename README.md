# Week 4 Hands-On Assignment: Data Exploration, Feature Engineering, and GitHub Workflow

**Course:** Introduction to Machine Learning
**Instructor:** Becky Deitenbeck
**Student:** Hannah Johnson
**Date:** February 10, 2026

---

## Assignment Overview

This assignment focuses on practical data exploration, feature engineering, and basic modeling using Python and scikit-learn. The Adult Income dataset (UCI Census Income dataset) is used to predict whether an individual earns more or less than $50,000 per year. GitHub is used to document and share the workflow.

---

## Instructions

1. **Set up your GitHub repository**
   - Name: `week4-data-exploration-ml`
   - Include this README and your Jupyter Notebook.

2. **Data Exploration & Feature Engineering**
   - Dataset: Adult Income (UCI / OpenML)
   - Explore the data, visualize features, and perform feature engineering (encoding, new features).

3. **Model Training & Evaluation**
   - Train a `RandomForestClassifier`
   - Evaluate using accuracy and a classification report (precision, recall, F1).
   - Interpret results and discuss strengths and limitations.

4. **Reflection**
   - Briefly reflect on the process and findings in a Markdown cell within the notebook.

---

## How to Run

1. Clone this repository or download the notebook:
   ```bash
   git clone https://github.com/YOUR_USERNAME/week4-data-exploration-ml.git
   cd week4-data-exploration-ml
   ```

2. Install requirements:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

3. Open the notebook:
   ```bash
   jupyter notebook M4_Data_Exploration_Feature_Engineering.ipynb
   ```
   Or open in **Google Colab** by uploading the `.ipynb` file directly.

4. Run all cells from top to bottom (`Kernel > Restart & Run All`).

---

## Dataset

- **Name:** Adult Income Dataset (Census Income)
- **Source:** UCI Machine Learning Repository / `sklearn` fetch_openml
- **Target:** `income` — binary classification (`<=50K` vs `>50K`)
- **Features:** Age, workclass, education, marital status, occupation, hours-per-week, and more.

---

## Files in This Repository

| File | Description |
|------|-------------|
| `README.md` | This file — project overview and instructions |
| `M4_Data_Exploration_Feature_Engineering.ipynb` | Main Jupyter Notebook with all code and analysis |

---

## Submission

- Push your completed notebook and reflection to this repository.
- Submit the repository link in Canvas.
