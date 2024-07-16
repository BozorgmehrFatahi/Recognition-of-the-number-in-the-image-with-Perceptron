# Recognition-of-the-number-in-the-image-with-Perceptron
# Number Recognition with Multilayer Perceptron (MLP) Classifier

This project aims to recognize numbers in images using the MNIST dataset through the implementation of a Multilayer Perceptron (MLP) classifier. The code utilizes libraries such as NumPy, pandas, Matplotlib, and scikit-learn for data manipulation, visualization, model building, and evaluation.

## Overview
The code reads the MNIST training data from a CSV file, preprocesses the data by separating features and labels, splits the data into training and testing sets using the train_test_split function, and trains an MLP classifier on the training data. The trained model is then used to make predictions on the test data, and the F1 score is calculated to evaluate the model's performance.

## Steps Involved
1. **Data Loading**: The MNIST training data is loaded from a CSV file using Pandas.
2. **Data Preprocessing**: The features (pixel values) and labels (target numbers) are extracted from the training data.
3. **Data Splitting**: The data is split into training and testing sets using a test size of 20% and a random seed for reproducibility.
4. **Model Training**: An MLP classifier is initialized and trained on the training data.
5. **Prediction**: The trained model is used to predict the target numbers for the test data.
6. **Evaluation**: The F1 score is computed to assess the model's accuracy in predicting the numbers.

## Libraries Used
- NumPy: For numerical operations and array manipulation.
- Pandas: For data loading and preprocessing.
- Matplotlib: For visualizing data and results.
- scikit-learn: For implementing the MLP classifier, data splitting, and model evaluation.

## Results
The F1 score obtained from evaluating the model on the test data provides an indication of the model's performance in recognizing numbers in images.