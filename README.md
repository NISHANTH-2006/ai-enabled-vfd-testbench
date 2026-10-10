# AI-Enabled VFD Testbench

An AI-based framework for analyzing Variable Frequency Drives (VFDs) using machine learning to detect anomalies, assess drive health, classify faults, and predict Remaining Useful Life (RUL).

## Project Overview

This project combines machine learning models with VFD operational data to support condition monitoring and predictive maintenance.

### Key Features

- **Anomaly Detection:** Identifies unusual operating patterns using Isolation Forest.
- **Health Classification:** Assesses the health condition of the drive using Random Forest.
- **Fault Classification:** Classifies faults using a trained machine-learning model.
- **Remaining Useful Life Prediction:** Estimates the remaining useful life using a regression model.
- **Diagnostic Reporting:** Supports generating diagnostic reports from model predictions.

## Repository Structure

- `MASTER_VFD_DEPLOYMENT.ipynb` — Deployment notebook and model inference workflow.
- `models/` — Trained machine-learning models and preprocessing scalers.
- `data/` — Datasets used by the project.
- `metrics/` — Model evaluation metrics.
- `reports/` — Diagnostic report examples.
- `requirements.txt` — Python dependencies.

## Technologies Used

Python, Pandas, NumPy, Scikit-learn, Joblib, and Jupyter Notebook.

## Dataset

This project uses publicly available VFD datasets for model development, testing, and evaluation.

The datasets are used as input data for anomaly detection, drive health classification, fault classification, and Remaining Useful Life (RUL) prediction.

**Dataset source:** [Insert the original dataset name and URL here]

The dataset is credited to its original authors or publishers. Please refer to the original source for its license and usage conditions.

## Getting Started

1. Clone or download this repository.
2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Open `MASTER_VFD_DEPLOYMENT.ipynb` in Jupyter Notebook or Google Colab.
4. Configure the dataset and model paths to match the repository structure.
5. Run the notebook cells in order.

## Notes

The trained models require the corresponding preprocessing scalers and input features expected during training. Model predictions depend on the quality and format of the input data.



