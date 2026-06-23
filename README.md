# 🏥 Multiple Disease Prediction System

A Machine Learning-powered web application built using Streamlit that predicts the likelihood of multiple diseases based on user-provided health parameters.
This project was built as part of my Machine Learning learning journey to understand data preprocessing, model training, model evaluation, and deployment using Streamlit.
## Features

- 🩺 Diabetes Prediction
- ❤️ Heart Disease Prediction
- 🧠 Parkinson's Disease Prediction
- 🎨 User-friendly Streamlit interface

## Tech Stack

- Python
- Streamlit
- Scikit-learn
- Pandas

## Project Structure

```
multiple-disease-prediction/
│
├── app.py
├── requirements.txt
├── saved_models/
├── dataset/
├── colab_files_to_train_models/
└── README.md
```

## Installation

1. Clone the repository

```bash
git clone <your-github-url>
cd multiple-disease-prediction
```

2. Create a virtual environment

```bash
python -m venv .venv
```

3. Activate the virtual environment

Windows:

```bash
.venv\Scripts\activate
```

4. Install dependencies

```bash
pip install -r requirements.txt
```

5. Run the application

```bash
streamlit run app.py
```

## Machine Learning Models

Different machine learning models were evaluated during development, and the best-performing models were selected for deployment.

Diseases Covered:

- Diabetes
- Heart Disease
- Parkinson's Disease

## Disclaimer

This application is developed for educational and research purposes only. It should not be used as a substitute for professional medical diagnosis or treatment.

## Author

Rishi Gupta
