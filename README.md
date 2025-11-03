# Machine Learning–Based Fault Diagnosis for a Simulated CSTR under Domain Shift
This project uses different ML models to classify 13 operating modes (1 normal + 12 faults) for a simulated CSTR. It also tests how well models trained on the source domain transfer to target domains (domain shift).
# Dataset
Source: Kaggle – "Continuous Stirred Tank Reactor – Domain Adaptation" (eddardd)
Shape: (2860, 1404)
0:1400 → 200×7 time-series (flattened)
1400 → fault label (0–12)
1401 → domain ID (0=source, 1–6=targets)
# Models
Logistic Regression, Decision Tree, Random Forest trained and tested in source domain.
Logistic Regression, Decision Tree, Random Forest trained in source domain and tested in target domains.
