# Patient Readmission Prediction (Streamlit)

This project provides a Streamlit app for multiclass patient readmission prediction using a trained `.pkl` model:

- Class 0: `NO`
- Class 1: `<30 days`
- Class 2: `>30 days`

## Project Structure

- `app.py`: Streamlit frontend
- `backend/pipeline.py`: backend training and inference logic
- `models/`: trained `.pkl` model file
- `artifacts/`: report, plots, preprocessing artifacts and prediction outputs

## Setup

```bash
pip install -r requirements.txt
```

## Run

```bash
streamlit run app.py
```

## Workflow

1. Open the `Training` tab and click **Start Training**.
2. After training, review confusion matrix and feature-importance plots.
3. Open the `Inference` tab, upload a CSV, and view prediction visualization/output.
