# Student Exam Performance Prediction

An end-to-end machine learning project by Pratik Jawale that predicts a student's math score from demographic information and reading/writing scores.

## Run Locally

```bash
python -m venv .venv
```

Activate the environment, then install and start the app:

```bash
pip install -e .
python app.py
```

Open `http://127.0.0.1:5000` in your browser. To retrain the model using `notebook/data/stud.csv`, run:

```bash
python -m src.components.data_ingestion
```

## Project Files

- `app.py` and `templates/`: Flask prediction interface.
- `src/components/`: data ingestion, preprocessing, and model training.
- `src/pipeline/`: prediction pipeline and input data handling.
- `notebook/`: exploratory analysis, model training notebooks, and source dataset.
- `artifacts/`: train/test data, trained model, and preprocessing object.

## Author

**Pratik Jawale** · [btwiampratik@gmail.com](mailto:btwiampratik@gmail.com)