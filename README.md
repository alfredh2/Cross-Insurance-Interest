# Cross Insurance Interest

## Project Overview
This project aims to predict whether health insurance policyholders from the past year would be interested in purchasing vehicle insurance. The project involves data preprocessing, exploratory data analysis, model development, training, evaluation, and deployment.

## Project Structure
- `data/`: Directory for storing raw and processed data.
  - `raw/`: Raw data files.
  - `processed/`: Processed data files.
- `notebooks/`: Jupyter notebooks for different stages of the project.
  - `01_data_ingestion_and_preprocessing.ipynb`
  - `02_exploratory_data_analysis.ipynb`
  - `03_model_development.ipynb`
  - `04_model_training.ipynb`
  - `05_model_evaluation_and_optimization.ipynb`
  - `06_model_deployment.ipynb`
- `src/`: Python scripts for reusable code and functions.
  - `data_preprocessing.py`
  - `feature_engineering.py`
  - `model_utils.py`
- `outputs/`: Directory for storing output files such as trained models, visualizations, and reports.
  - `models/`: Trained model files.
  - `reports/`: Analysis and evaluation reports.
- `README.md`: Project overview and instructions.
- `requirements.txt`: List of dependencies.

## Setup Instructions
1. Install dependencies: `pip install -r requirements.txt`
2. Run the notebooks in sequence to preprocess data, perform EDA, develop, train, evaluate, and deploy the model.

## Usage
- The final model can be deployed using Flask as a web service. Use the `/predict` endpoint to make predictions.

## Future Work
- Explore advanced techniques like ensemble models or transfer learning.
- Investigate the impact of external factors (e.g., economic conditions) on interest in vehicle insurance.
