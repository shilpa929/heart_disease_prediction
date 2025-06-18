# Cardinova: Smart Heart Disease Risk Predictor

## Overview

**Cardinova** is a machine learning-based web application for predicting the risk of heart disease based on patient data such as age, sex, chest pain type, blood pressure, cholesterol, and more. The project uses a Random Forest Classifier trained on a proprietary dataset provided by the company. Cardinova features a user-friendly web interface (built with Streamlit), model interpretability (feature importance), and personalized recommendations.

## Features

- Intuitive web interface for entering patient parameters  
- Instant heart disease risk prediction  
- Model confidence score  
- Feature importance visualization  
- Personalized recommendations  
- Healthy heart tips

## Project Structure

UNIFIED_PROJECT2/
├── data/
│   └── (raw and processed data files)
├── notebooks/
│   └── Heart_Disease_Prediction.ipynb
├── scripts/
│   ├── data_loading_and_exploration.py
│   ├── data_processing.py
│   ├── model_trainning.py
│   ├── train_and_save_model.py
│   ├── train_test_split_and_scale.py
│   └── ...
├── best_random_forest_model.joblib
├── heart_disease_app.py
├── dataset.csv
├── processed_dataset.csv
├── X_train.csv, X_test.csv, y_train.csv, y_test.csv
└── README.md


## Getting Started

1. **Clone the repository:**
   git clone https://github.com/shilpa929/heart_disease_prediction.git
cd heart_disease_prediction

2. **Install requirements:**
   pip install -r requirements.txt
   

3. **Dataset:**
   - The dataset is proprietary and was provided by the company. Place the file (e.g., `dataset.csv`) in the appropriate folder.

4. **Model Training:**
   - Run the notebook `notebooks/Heart_Disease_Prediction.ipynb` or the scripts in `scripts/` to preprocess data and train the model.
   - Save the trained model as `best_random_forest_model.joblib` in the project root.

5. **Run the App:**
   streamlit run heart_disease_app.py

6. **Access the App:**
   - Open the URL shown in the terminal, typically [http://localhost:8501](http://localhost:8501).

## Example

Below is a screenshot of the project opened in VS Code, showing the app being launched:
![alt text](cardinova.png)

## Usage

- Open your browser to the provided URL (e.g., [http://localhost:8501](http://localhost:8501)).
- Enter patient details in the left sidebar.
- Click **Predict Heart Disease Risk**.
- View risk results, confidence, feature importance, and recommendations.

## Project Report

See [`notebooks/Heart_Disease_Prediction.ipynb`](notebooks/Heart_Disease_Prediction.ipynb) for full documentation, workflow, and model evaluation.

## Credits

- Author: Shilpa Roy
- Dataset: Provided by the company

## License

This project is for academic and educational purposes.


[def]: <cardinova.png>