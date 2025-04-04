# Heart Disease Prediction Model

This project implements a machine learning model to predict the presence or absence of heart disease based on various health indicators. The model uses a Random Forest Classifier and achieves high accuracy in predicting heart disease outcomes.

## Project Overview

The model analyzes various health metrics including:
- Age
- Sex
- Chest pain type
- Blood pressure
- Cholesterol levels
- Blood sugar
- ECG results
- Maximum heart rate
- Exercise-induced angina
- ST depression
- Slope of peak exercise ST segment
- Number of major vessels
- Thalassemia type

## Dataset

The project uses the Heart Disease dataset from UCI Machine Learning Repository. The dataset contains 1027 samples with 13 features and a target variable indicating the presence (1) or absence (0) of heart disease.

## Features

- Data preprocessing and exploration
- Feature analysis and visualization
- Model training using Random Forest Classifier
- Model evaluation with various metrics
- Visualization of results and feature importance

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/heart-disease-prediction.git
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter notebook `heart_disease.ipynb`
2. Run all cells to see the complete analysis and model training process
3. The notebook includes data exploration, model training, and evaluation steps

## Model Performance

The Random Forest Classifier achieves high accuracy in predicting heart disease. The model's performance metrics include:
- Accuracy Score
- Classification Report
- Confusion Matrix
- Feature Importance Analysis

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- UCI Machine Learning Repository for providing the dataset
- Contributors and maintainers of the libraries used in this project 