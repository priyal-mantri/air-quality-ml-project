# Air Quality Machine Learning Project

A multi-phase machine learning project analyzing air quality data using regression,
feature engineering, classification, and temporal generalization.

This project is designed as a progressive learning and research-oriented workflow,
with increasing real-world constraints across phases.

---

## Dataset

Source: Kaggle – Air Quality Data in India  
- City-level daily data (`city_day.csv`) is included for reproducibility.
- Larger datasets (city_hour, station_day, station_hour) are not uploaded due to size
  and will be used in future phases.

---

## Project Structure

- `data/raw/` – Original datasets
- `data/processed/` – Cleaned and engineered datasets
- `notebooks/` – Phase-wise analysis notebooks
- `docs/figures/` – Visualizations and plots

---

## Phase Overview

### Phase 1 — Baseline Regression
- Predict AQI using raw pollutant features
- Linear regression with RMSE and R² evaluation

### Phase 2 — Feature Engineering
- Constructed PM Index, Gas Index, VOC Index
- Normalization and regression comparison

### Phase 3 — Classification
- Predict AQI Bucket (Good → Severe)
- Logistic Regression, Decision Tree, Random Forest
- Addressed class imbalance using macro F1-score

### Phase 4 — Temporal Generalization
- Time-aware train/test split (past → future)
- Evaluated model robustness under temporal drift

---

## Key Learnings

- Trade-off between raw variance and structured features
- Effects of class imbalance in multi-class classification
- Performance degradation under real-world temporal shifts
- Importance of evaluation beyond accuracy

---

## Future Work (Planned)

- Phase 5: Granularity shift (city → station level)
- Phase 6: Spatial generalization
- Phase 7: Error-focused analysis
- Phase 8: Advanced ensemble methods

