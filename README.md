# Iris Flower Classification

## Overview
This project implements a machine learning model to classify Iris flower species using the K-Nearest Neighbors (KNN) algorithm. The dataset used is the famous Iris dataset, which contains measurements of different features of Iris flowers and their corresponding species.

## Dataset
The Iris dataset consists of 150 samples of iris flowers, each with four features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)
- Species (Iris Setosa, Iris Versicolor, Iris Virginica)

The dataset can be found in the file `IRIS.csv`.

## Requirements
To run this project, you need the following Python libraries:
- pandas
- seaborn
- matplotlib
- scikit-learn

You can install the required libraries using pip:

```bash
pip install pandas seaborn matplotlib scikit-learn
```
## Usage
Clone the repository or download the project files.
Ensure that the IRIS.csv file is in the same directory as the script.
Run the script in a Python environment (e.g., Jupyter Notebook, Google Colab, or any Python IDE).

## Code Explanation
Data Loading: The dataset is loaded using pandas.
Data Overview: The first few rows, shape, summary statistics, and missing values are displayed for a quick overview.
Class Distribution: The distribution of different species in the dataset is printed.
Data Visualization: Pairwise relationships between features are visualized using seaborn's pairplot.
Data Splitting: The dataset is split into training and testing sets (80% training, 20% testing).
Model Training: A KNN classifier is initialized and trained on the training data.
Model Evaluation: The model's accuracy, confusion matrix, and classification report are printed and visualized.

## Results
The model's accuracy and performance metrics will be displayed after running the script. The confusion matrix will also be visualized to show the classification results.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions or suggestions, feel free to reach out to Abhijeet Samantaray at abhijeetsamantaray123@gmail.com .
