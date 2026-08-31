# anaemia-prediction-model

A PyTorch neural network that predicts anaemia using hemoglobin levels and RGB pixel features, with feature scaling, train/validation/test evaluation, and classification metrics.

## Project Overview

This project preprocesses patient data, trains a neural network, and evaluates its performance on a test dataset.

## Results

The model achieved 94% accuracy. Performance was also evaluated using:

- Precision
- Recall
- F1 score
- Confusion matrix

## Technologies Used

- Python
- PyTorch
- Pandas
- NumPy
- scikit-learn
- Matplotlib
- Google Colab

## Dataset

This project uses the [Anaemia Prediction dataset by Humair Munir on Kaggle](https://www.kaggle.com/datasets/humairmunir/anaemia-prediction).

The dataset contains image-derived pixel values and patient information used to predict whether an individual is anaemic. The dataset is not included in this repository; download it directly from Kaggle before running the notebook.

## Running the Project

1. Download the notebook.
2. Open it in Google Colab or Jupyter Notebook.
3. Upload the required dataset.
4. Run all cells in order.
