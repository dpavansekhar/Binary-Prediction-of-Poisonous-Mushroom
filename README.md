# Mushroom Edibility Prediction

## Project Overview

This project is designed to predict mushroom edibility using machine learning techniques. It utilizes a dataset with various features such as cap shape, color, and habitat to determine whether a mushroom is edible or poisonous.

## Dataset

The project uses two main datasets:
- **`train.csv`**: Contains training data with features and target labels.
- **`test.csv`**: Contains test data with features for which predictions are to be made.
- To access the data set Follow the link 🔗 ![https://www.kaggle.com/competitions/playground-series-s4e8/data] 

## Steps Involved

### 1. Data Preparation
- **Handling Missing Values**: Missing values are imputed using mean (for numerical features) or mode (for categorical features).
- **Encoding Categorical Features**: Categorical attributes are converted into numerical values using `LabelEncoder`.

### 2. Model Training
- **Algorithm**: A `RandomForestClassifier` is employed to train the model on the prepared training data.

### 3. Prediction and Results
- **Prediction**: The trained model makes predictions on the test dataset.
- **Results**: The predictions are saved for further evaluation.

## Approach

The project ensures accurate predictions by addressing data quality issues and applying robust machine learning techniques. This process helps in effectively classifying mushrooms as edible or poisonous based on their features.

## Usage

To run this project:
1. Prepare the dataset as described in the data preparation section.
2. Train the model using the `RandomForestClassifier`.
3. Make predictions on the test dataset.
4. Save and evaluate the results.

For more details, please refer to the code files and documentation provided in this repository.

