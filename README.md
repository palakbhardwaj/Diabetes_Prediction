# Diabetes_Prediction


This project aims to predict diabetes using a Support Vector Machine (SVM) model. The dataset includes various medical predictor variables and an outcome variable indicating the presence of diabetes.

## Dataset

The dataset consists of the following columns:
- `Pregnancies`: Number of times pregnant
- `Glucose`: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skin fold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index (weight in kg/(height in m)^2)
- `DiabetesPedigreeFunction`: Diabetes pedigree function
- `Age`: Age (years)
- `Outcome`: Class variable (0 or 1), indicating the absence or presence of diabetes

## Project Structure

- `data/`: Directory containing the dataset.
- `notebooks/`: Jupyter notebooks used for analysis and model training.
- `src/`: Source code for data processing, model training, and evaluation.
- `models/`: Directory to save trained models.
- `README.md`: Project documentation.

## Getting Started

### Prerequisites

- Python 3.7+
- Required packages listed in `requirements.txt`

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/diabetes-prediction-svm.git
    cd diabetes-prediction-svm
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1. Preprocess the data and train the model:
    ```sh
    python src/train.py
    ```

2. Evaluate the model:
    ```sh
    python src/evaluate.py
    ```

### Example

You can find an example of the data preprocessing, training, and evaluation process in the Jupyter notebooks located in the `notebooks/` directory.

## Results

The trained SVM model achieves an accuracy of 77% on the test set. Detailed evaluation metrics and visualizations can be found in the `notebooks/` directory.



