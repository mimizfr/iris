# Iris Flower Classification

This repository contains a small machine learning notebook exploring the Iris dataset. The goal is to examine relationships between features, visualize the data, and train a few basic classification models to predict the species of an iris flower.

The dataset includes measurements such as sepal length, sepal width, petal length, and petal width. Using these features, the models classify the flowers into three species: *Iris setosa*, *Iris versicolor*, and *Iris virginica*.

---

## Exploration

The notebook starts with a quick exploration of the dataset. A **Seaborn pairplot** is used to visualize how the features relate to each other and how well the species separate in the feature space.

---

## Models

Three classification models were trained and evaluated:

- Support Vector Machine (SVM)  
- Logistic Regression  
- Decision Tree Classifier  

All three models produced very similar results on the test dataset.

---

## Results

| Model | Accuracy |
|-------|---------|
| Support Vector Machine | 93.33% |
| Logistic Regression    | 93.33% |
| Decision Tree          | 93.33% |

**Classification Report**

| Species           | Precision | Recall | F1-Score | Support |
|------------------|-----------|--------|----------|--------|
| Iris-setosa       | 1.00      | 1.00   | 1.00     | 11     |
| Iris-versicolor   | 0.91      | 0.91   | 0.91     | 11     |
| Iris-virginica    | 0.88      | 0.88   | 0.88     | 8      |
| **Accuracy**      |           |        | 0.93     | 30     |
| **Macro Avg**     | 0.93      | 0.93   | 0.93     | 30     |
| **Weighted Avg**  | 0.93      | 0.93   | 0.93     | 30     |

---

## Screenshot

Seaborn pairplot from the exploratory analysis:

<img width="1275" height="643" alt="Iris 1" src="https://github.com/user-attachments/assets/c392525c-0dac-43d8-a736-1d6f8448e223" />


---

## Files

-iris_model.ipynb

-README.md

---
## Author
Maryam Zafar

## GitHub 
mimizfr
