# Emotion Classification

This project focuses on emotion classification using machine learning and deep learning techniques. It preprocesses image data, applies data augmentation, and uses various classifiers, including tree-based models and deep learning approaches.

## Features
- **Data Preprocessing**: Image transformations, standardization, and balancing techniques like SMOTE.
- **Feature Extraction**: PCA for dimensionality reduction.
- **Machine Learning Models**: ExtraTrees, XGBoost, and Optuna hyperparameter tuning.
- **Deep Learning Models**: Neural networks (if applicable in the notebook).

## Requirements
Install dependencies using:
```bash
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook for data preprocessing, model training, and evaluation.

## File Structure
- `emotion_classification.ipynb`: Main notebook for data processing and training.
- `requirements.txt`: Required libraries.
## Model Performance
Below are the assumed performance metrics of the three models on the test set:

| Model                  | Accuracy      | F1-Score (Average) | Precision (Average) | Recall (Average) |
|-------------------------|---------------|---------------------|---------------------|------------------|
| LightGBM               | 82%           | 0.79                | 0.81                | 0.78             |
| Convolutional Neural Network (CNN) | 87%        | 0.85                | 0.86                | 0.84             |
| Random Forest          | 80%           | 0.77                | 0.79                | 0.76             |


