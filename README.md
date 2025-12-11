# Students-Performance-Prediction — End-to-End Machine Learning Project

**Predicting student exam performance using an end-to-end ML pipeline and a Flask demo.**

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Repository Structure](#repository-structure)
- [Requirements](#requirements)
- [Quick Start — Run locally](#quick-start---run-locally)
- [Model & Training](#model--training)
- [API / Web App](#api--web-app)
- [CI / Deployment](#ci--deployment)
- [Notes & Next Steps](#notes--next-steps)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

---

## Project Overview
This repository contains an end-to-end machine learning project that predicts student performance (exam scores) given demographic and educational features. It includes data, preprocessing, model files (artifacts), notebooks for EDA and model training, a Flask-based demo app, and CI workflow configuration.

---

## Features
- Exploratory Data Analysis (notebooks)
- Data preprocessing & feature engineering
- Model training (CatBoost / scikit-learn usage in notebooks)
- Prebuilt model and preprocessor artifacts (`artifacts/`)
- Flask web app to interact with the model (`app.py`, templates)
- GitHub Actions workflow for CI (`.github/workflows/`)

---

## Repository Structure
```yaml
├── app.py                       # Flask app entrypoint
├── requirements.txt             # Python dependencies
├── README.md
├── artifacts/
│   ├── model.pkl                # Trained model artifact
│   ├── preprocessor.pkl         # Preprocessing pipeline
│   ├── data.csv
│   ├── train.csv
│   └── test.csv
├── notebook/
│   ├── 1. EDA STUDENT PERFORMANCE.ipynb
│   ├── 2. MODEL TRAINING.ipynb
│   └── data/
│       └── stud.csv
├── src/
│   ├── components/              # ingestion, transformation, trainer
│   ├── pipeline/                # predict_pipeline.py, train_pipeline.py
│   ├── logger.py
│   ├── exception.py
│   └── utils.py
├── .github/
│   └── workflows/               # CI workflow
└── .ebextensions/               # Elastic Beanstalk config
```

---

## Requirements
Install dependencies (recommended to use a virtual environment or conda):

```bash
# Using pip
python -m venv venv
source venv/bin/activate        # Linux / macOS
venv\Scripts\activate           # Windows

pip install -r requirements.txt
```
### Clone the project
```bash
git clone (https://github.com/Arnab-Ghosh7/Students-Performance-Prediction-End-to-End-Machine-Learning-Project)
cd Students-Performance-Prediction
```




## Repository Structure
