# Digital_Twin_Productivity

Colab notebook and code for MSc thesis: 
**Lightweight Digital Twin for Team Productivity** — a human-centered framework using ML to analyze productivity & well-being in hybrid work.

## Digital Twin – Remote/Hybrid Productivity (MSc Thesis)
This repository contains the Colab notebook used in my MSc thesis to model and simulate productivity under hybrid/remote work. The focus is on calibrated probabilities, subgroup stability, and bounded “what-if” scenarios.

## Files
- `notebooks/Digital_Twin_Productivity.ipynb` — step-wise notebook (Logistic Regression, Random Forest, Gradient Boosting + scenarios)
- `attachments/` — exports used in the thesis PDF:
  - `results_real.tex` (baseline model table)
  - `calibration_rf.png` (calibration plot)
  - `results_scenarios.tex` (scenario table)

## Dataset
- **Garment Worker Productivity** — UCI Machine Learning Repository  
  Download from UCI and place as `data/garments_worker_productivity.csv`.

## Run (Colab)
1. Open the notebook in **Google Colab**.
2. Upload the dataset CSV to the runtime at `data/garments_worker_productivity.csv`.
3. Run all cells top-to-bottom.

## Reproducibility
Random seeds are set; the notebook prints the metrics and scenario results reported in the thesis and exports the three files in `attachments/` for direct inclusion in Overleaf.

UCI dataset page: https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees
