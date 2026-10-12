# MACHINEGUARD
### Predictive Maintenance Using Machine Learning

**Course:** Machine Learning  
**University:** Salymbekov University  
**Student:** [Omurakunova Ailin]  
**Practical Work:** PR-1 — Environment Setup and First Notebook  
**Difficulty Level:** C (Advanced)

## 1. Project Overview

MACHINEGUARD is an educational machine learning project focused on predicting industrial equipment failures using operational data.

The project explores data analysis, preprocessing, regression, classification, model evaluation, and explainable machine learning.

## 2. Dataset

**Name:** AI4I 2020 Predictive Maintenance Dataset

**Source:** UCI Machine Learning Repository

**Link:** https://archive.ics.uci.edu/dataset/601/ai4i%2B2020%2Bpredictive%2Bmaintenance%2Bdataset

The dataset contains 10,000 records and 14 columns, including temperature, rotational speed, torque, tool wear, and machine failure indicators.

The dataset is synthetic and intended for predictive maintenance research.

## 3. Technologies

- Python 3.14
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code

Exact dependency versions are recorded in `requirements.txt`.

## 4. Project Structure

```text
machineguard-ml/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── PR1_first_look.ipynb
├── requirements.txt
└── README.md
```

The structure will be expanded as the practical works progress.

## 5. Practical Work 1

**Title:** Environment Setup and Initial Data Analysis

**Objective:** Configure a reproducible Python environment and perform an initial examination of an open dataset.

**Completed activities:**
- Created a Python virtual environment.
- Installed and recorded project dependencies.
- Loaded the AI4I 2020 dataset.
- Inspected dataset dimensions and data types.
- Checked missing values and duplicate records.
- Calculated descriptive statistics.
- Visualized air temperature and product type distributions.
- Created a data dictionary.
- Documented dataset selection and limitations.

## 6. Initial Findings

The dataset contains 10,000 records and 14 columns, with no missing values or duplicate rows.

The average air temperature is approximately 300.00 K, while the average process temperature is approximately 310.01 K.

Product type L represents 60% of the records, followed by M (29.97%) and H (10.03%).

These results describe the dataset but do not establish causal relationships with machine failures.

## 7. Reproducibility

The project uses a Python virtual environment and fixed dependency versions.

Install dependencies using:

```bash
python -m pip install -r requirements.txt
```

Open `notebooks/PR1_first_look.ipynb` in VS Code and select the project's Python environment.

The notebook should be executed from beginning to end to reproduce the analysis.

## 8. Future Work

The next practical works will cover exploratory data analysis, preprocessing pipelines, regression, imbalanced classification, text classification using a separate corpus, and random forest interpretation.

## 9. Project Status

Practical Work 1 is in progress. Final notebook verification and GitHub submission are pending.