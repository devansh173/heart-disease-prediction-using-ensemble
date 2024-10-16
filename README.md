# Heart Disease Prediction using Ensemble Methods

## Project Overview

This project aims to predict the likelihood of heart disease in patients using an ensemble of machine learning models. The dataset consists of various features related to patient health metrics, such as age, blood pressure, cholesterol levels, and more, which are used to determine whether a patient has heart disease.

The ensemble approach combines the strengths of multiple models to improve prediction accuracy and robustness.

## Dataset

The dataset contains 14 attributes related to patient health:

- `age`: Age of the patient
- `sex`: Gender (1 = male, 0 = female)
- `cp`: Chest pain type (0 = typical angina, 1 = atypical angina, etc.)
- `trestbps`: Resting blood pressure (in mm Hg)
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- `restecg`: Resting electrocardiographic results (0 = normal, 1 = abnormal, etc.)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes, 0 = no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy (0-3)
- `thal`: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)
- `target`: Presence of heart disease (1 = disease, 0 = no disease)

## Requirements

To run the project, you need the following Python packages:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly`
- `scikit-learn`
- `warnings`

You can install these packages using the following command:

```bash
pip install -r requirements.txt
```

## How to Run

### Step-by-Step Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/heart-disease-prediction.git
    cd heart-disease-prediction
    ```

2. Install the required libraries:
    Run the following command to install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the Jupyter notebook:
    If you don’t have Jupyter installed, you can install it using:
    ```bash
    pip install notebook
    ```

    Then start the notebook server:
    ```bash
    jupyter notebook
    ```

4. Run the notebook:
    Open the `ensemble_heart_disease_prediction.ipynb` file in Jupyter Notebook and run the cells in sequence. The notebook includes:
    
    - Data loading and preprocessing
    - Exploratory Data Analysis (EDA) with visualizations
    - Training and evaluation of ensemble models

5. Upload the dataset:
    The dataset (`data.csv`) must be uploaded within the notebook environment when prompted. This dataset should have the features mentioned above (age, sex, cp, etc.).

6. Training Models:
    The notebook includes various ensemble models for training, such as:

    - Random Forest Classifier
    - Gradient Boosting Classifier
    - Voting Classifier
    - Bagging and Boosting techniques

7. Evaluate Models:
    After training, the models are evaluated using performance metrics like accuracy, precision, recall, F1-score, and ROC-AUC curve. The notebook includes code to visualize model performance.
"""
