# Data-Driven Biomedical Signal Analysis: Disease Classification and Forecasting

## Overview
This project explores Data Science and Machine Learning techniques for biomedical signal analysis using real-world health data. The goal is to classify health conditions and forecast biomedical signals using time-series data from the MIMIC database on the PhysioNet website. A hybrid model integrates forecasting outputs as input features for disease classification to improve disease progression insights.

## Project Objectives
- **Classifying Health Conditions:** Identify patterns in biomedical signals to determine if a person is healthy or ill.
- **Predicting Health Signals:** Develop models to forecast future health signals based on past observations.
- **Hybrid Approach:** Combine classification and forecasting to enhance disease detection and progression modeling.

## Dataset
The project utilizes real patient data from the **MIMIC database** available on the [PhysioNet website](https://physionet.org). Access requires completing the **[CITI Data or Specimens Only Research Certification](https://www.citiprogram.org/verify/?wb92a1f94-0181-4596-be1f-6004cb410f11-54334187)**.

## Project Components
### 1. Classifying Health Conditions
<!-- #### Steps:
1. **Data Preprocessing:**
   - Handle missing values (imputation).
   - Remove noise from signals.
   - Normalize or standardize data.
2. **Exploratory Data Analysis (EDA):**
   - Extract statistical features (mean, variance, skewness).
   - Analyze frequency components (Fourier Transform).
   - Compute physiological metrics (heart rate variability).
3. **Machine Learning Model:**
   - Train classifiers (Regression, Decision Trees, etc.).
   - Evaluate performance using metrics like accuracy and precision. -->

### 2. Predicting Health Signals
<!-- #### Steps:
1. **Understanding Temporal Data:**
   - Split data into time windows.
   - Normalize values for consistency.
2. **Deep Learning Models:**
   - Implement **Recurrent Neural Networks (RNNs)** and **Long Short-Term Memory (LSTM)** using PyTorch.
   - Optimize model hyperparameters.
3. **Evaluation:**
   - Use **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)** to assess performance. -->

### 3. Hybrid Approach: Combining Classification and Forecasting
<!-- - Forecasting outputs will be used as additional features in disease classification models.
- This approach enhances decision-making and improves insights into disease progression. -->

## Deliverables
- **Preprocessed and cleaned dataset** for analysis.
- **Classification and forecasting models** with performance metrics.
- **Mid-term oral presentation** showcasing project progress.
- **Final Jupyter Notebook report** detailing methodology, results, and key findings.

## Tools & Libraries
- **Data Processing:** `pandas`, `numpy`, `scipy`, `neurokit2`
- **Machine Learning:** `scikit-learn`, `pytorch`
- **Visualization:** `matplotlib`, `seaborn`

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo-name.git
   cd your-repo-name

2. Install dependencies:
    ```sh
    pip install -r requirements.txt

## Acknowledgments

This project is part of CIIC4998 - Data-Driven Biomedical Signal Analysis: Disease Classification and Forecasting (Spring 2025). The dataset is sourced from the MIMIC database available on the PhysioNet website.# Research-Signal-Processing-ML
