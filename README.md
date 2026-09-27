# Imamsidikov_ML_task1 — Data Preprocessing & Cleaning

MOP 3231 · Machine Learning (Python) · Week 2 Lab / Task 1.

Turns the synthetic Almaty apartment listings (`data/almaty_apartments_raw.csv`) into a model-ready table and
documents every cleaning decision in `task1_data_preprocessing.ipynb`.

## Steps
1. Project setup & versions
2. Load and inspect (types, grain, validation spec)
3. Clean and transform (duplicates/reposts, districts, text → numbers)
4. Sentinels, impossible values, outliers → `data/almaty_apartments_clean.csv`
5. Missing data (split first, MCAR/MAR diagnosis, masking experiment, fill)
6. Scaling and encoding (scaler comparison, leakage, final matrix + R² sanity check)
7. EDA and cleaning log
8. Summary and git history

## Run
```bash
python3.12 -m venv .Imamsidikov_ML_task1
source .Imamsidikov_ML_task1/bin/activate
pip install -r requirements.txt
jupyter notebook task1_data_preprocessing.ipynb   # Kernel → Restart & Run All
```
