# Digital_Twin_Productivity
Colab notebook and code for MSc thesis: Digital Twin Models for Remote Employee Productivity — human-centered framework using ML to analyse productivity &amp; well-being in hybrid work.

# Digital Twin – Remote/Hybrid Productivity (MSc Thesis)

This repository contains the Colab notebook used in my MSc thesis to model and simulate productivity under hybrid/remote work.

## Files
- `notebooks/Digital_Twin_3models_STEPWISE.ipynb` — step-wise notebook (Logistic Regression, Random Forest, Gradient Boosting + simulations)
- `requirements.txt` — basic Python libs
- `outputs/` — optional metrics/figures

## Dataset
Use the Kaggle dataset “Remote Work Productivity.” Download the CSV and place it in the Colab runtime as:
`remote_work_productivity.csv`

## Run (Colab)
1. Open the notebook in Google Colab.
2. Upload `remote_work_productivity.csv` to the runtime.
3. Run all cells top-to-bottom.

## Reproducibility
Random seeds are set; the notebook prints metrics and simulation outputs used in the thesis.
