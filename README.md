# Iris Flower Classification

## Introduction
This project builds a machine learning classification system to predict the species of an Iris flower.

The model uses four physical measurements:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Dataset
The project uses the Iris Species dataset containing three flower species:
- Setosa
- Versicolor
- Virginica
- ### Dataset Sources

- [UCI Machine Learning Repository – Iris Dataset](https://archive.ics.uci.edu/dataset/53/iris)
- [Kaggle – Iris Species Dataset](https://www.kaggle.com/datasets/uciml/iris)
- ## Kaggle Notebook

[View the Iris Flower Classification notebook on Kaggle](https://www.kaggle.com/code/aimanazfal123/iris-flower-classification)

## Machine Learning Models
The following models were used:
- K-Nearest Neighbors (KNN)
- Decision Tree
- Logistic Regression

## Project Results
The models achieved high classification accuracy on the Iris dataset.
| Algorithm           | Test Accuracy | CV Accuracy |
| ------------------- | ------------: | ----------: |
| KNN                 |        93.33% |      96.67% |
| Decision Tree       |        96.67% |      93.33% |
| Logistic Regression |        93.33% |      95.83% |


## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- ## How to Run the Notebook Locally

1. Clone or download this repository.

2. Install the required Python packages:

```bash
pip install -r requirements.txt
jupyter notebook "iris-flower-classification (1).ipynb"
## Conclusion

K-Nearest Neighbors (KNN) was selected as the final model because it achieved the highest cross-validation accuracy of 96.67% among the three models. Although the Decision Tree achieved a higher test accuracy of 96.67%, KNN showed stronger cross-validation performance, indicating more consistent performance across different data splits.


## Files
- `iris-flower-classification (1).ipynb` — Complete machine learning notebook
- `requirements.txt` — Required Python libraries
