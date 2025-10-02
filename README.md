# Hotel Booking Cancellation Prediction

Predicting hotel booking cancellations with **83.98% accuracy and 89.78% ROC-AUC** using Random Forest.

## 📖 Full Project Documentation

**See [04_summary.ipynb](notebooks/04_summary.ipynb) for complete analysis** including:
- EDA insights & visualizations
- Feature engineering process
- Model comparison & selection
- Business recommendations

## Quick Results

| Metric | Value |
|--------|-------|
| **Model** | Random Forest |
| **ROC-AUC** | 89.78% |
| **Accuracy** | 83.98% |
| **Top Predictor** | Lead time (15% importance) |

**Feature Importance**:

| Rank | Feature | Importance |
|------|---------|------------|
| 1 | lead_time | 15.22% |
| 2 | country | 10.87% |
| 3 | adr | 9.01% |
| 4 | total_of_special_requests | 8.51% |
| 5 | market_segment | 7.73% |

## Project Structure

```
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_modeling.ipynb
│   └── 04_summary.ipynb          # Start here
├── data/
│   ├── raw/
│   └── processed/
├── models/
│   └── random_forest_final.pkl
└── requirements.txt
```

## Dataset

[Hotel Booking Demand (Kaggle)](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

87,370 bookings • 32 features • 27.5% cancellation rate

## Tools used

Python • Pandas • Scikit-learn • XGBoost • LightGBM • Matplotlib • Seaborn

## License

MIT License
