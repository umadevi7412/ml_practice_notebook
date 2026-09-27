<<<<<<< HEAD
# Women Safety Risk Prediction

A machine-learning regression project that estimates a synthetic women-safety `Risk_Score` from location, time, lighting, CCTV, crowd density, security availability, and incident-index data.

## Project structure

```text
Women-Safety-Risk-Prediction/
├── dataset/
│   └── KIET_Women_Safety_365_Days_2023_2026.csv
├── notebooks/
│   └── women_safety_prediction.ipynb
├── app.py
├── requirements.txt
└── README.md
```

## Setup

Use Python 3.10 or newer, then run:

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

## Run the dashboard

```bash
streamlit run app.py
```

The app trains a `RandomForestRegressor` when it starts and provides an interactive scenario form plus a dataset overview.

## Run the notebook

```bash
jupyter notebook notebooks/women_safety_prediction.ipynb
```

The notebook covers data loading, validation, exploratory analysis, preprocessing, train/test evaluation, and a sample prediction.

## Data note

The CSV is labeled `Synthetic/assumption data`. The resulting scores are for educational and analytical use only; they must not be treated as verified safety measurements, emergency guidance, or a substitute for local safety resources.
=======
# ml_practice_notebook
>>>>>>> 3ef804f783d8587ae8598d5b3360dcf70b74c811
