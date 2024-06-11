# Iris Species Classification

This project demonstrates a machine learning model that classifies Iris species based on their characteristics. The model uses the Iris dataset from the `sklearn` library and a Random Forest classifier.</br>
<br>
![Iris](https://github.com/cleverson0803/Iris_Species_Classification/blob/main/iris_plot.png)
</br>
## Project Overview

The Iris dataset is a well-known dataset in the field of machine learning and statistics. It contains 150 samples of Iris flowers with four features each: sepal length, sepal width, petal length, and petal width. The samples belong to three different species: Iris setosa, Iris versicolor, and Iris virginica.

This project aims to build a machine learning model that can classify the species of an Iris flower based on its features.

## Dataset

The dataset used in this project is the Iris dataset, which is available in the `sklearn` library. It contains the following columns:
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`
- `species` (target variable)

## Getting Started

### Prerequisites

Make sure you have Python and the following libraries installed:
- `numpy`
- `pandas`
- `scikit-learn`

You can install the required libraries using pip:

```sh
pip install numpy pandas scikit-learn
```

## Cloning the repository

### Clone the repository

git clone [Iris_Species_Classification](https://github.com/cleverson0803/Iris_Species_Classification.git) </br>
cd Iris_Species_Classification

## Run the script
python iris_classification.py

## Script Explanation
The iris_classification.py script performs the following steps:

1. Load the Iris dataset using the sklearn.datasets module.</br>
2. Explore the dataset by displaying the first few rows.</br>
3. Split the dataset into training and testing sets using train_test_split.</br>
4. Standardize the features using StandardScaler.</br>
5. Train the Random Forest classifier on the training set.</br>
6. Make predictions on the testing set.</br>
7. Evaluate the model by calculating the accuracy and displaying the classification report.</br>

## Example Output
After running the script, you should see an output similar to the following:
```sh
   sepal length (cm)  sepal width (cm)  petal length (cm)  petal width (cm)  species
0                5.1               3.5                1.4               0.2        0
1                4.9               3.0                1.4               0.2        0
2                4.7               3.2                1.3               0.2        0
3                4.6               3.1                1.5               0.2        0
4                5.0               3.6                1.4               0.2        0
Accuracy: 1.0
Classification Report:
              precision    recall  f1-score   support

      setosa       1.00      1.00      1.00         8
  versicolor       1.00      1.00      1.00        12
   virginica       1.00      1.00      1.00        10

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30
```

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request. You can also open an issue to discuss any improvements or suggestions.
