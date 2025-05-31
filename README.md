# 🌸 Iris Flower Classification using Logistic Regression

This machine learning project is focused on classifying iris flowers into one of three species — **Setosa**, **Versicolor**, or **Virginica** — based on measurements of their petals and sepals. We use the **Logistic Regression algorithm**, a widely used classification method in supervised machine learning, to train the model.

The goal is to predict the species of an iris flower using its physical characteristics with high accuracy.

---

## 📌 Project Objective

- **Build a machine learning model** using logistic regression.
- Use the **Iris dataset**, which includes 150 flower samples.
- Evaluate the model using **accuracy** as the primary metric.
- Visualize the dataset (optional) for better understanding of class distribution.

---

## 📊 Dataset Description

The **Iris dataset** is one of the most popular datasets in machine learning and statistics. It contains **150 rows and 5 columns**:

| Feature | Description |
|--------|-------------|
| `sepal length (cm)` | Length of the flower’s sepal |
| `sepal width (cm)`  | Width of the flower’s sepal |
| `petal length (cm)` | Length of the flower’s petal |
| `petal width (cm)`  | Width of the flower’s petal |
| `species`           | The category (Setosa, Versicolor, Virginica) |

There are **3 classes (species)**, each with **50 instances**:
- **0 = Setosa**
- **1 = Versicolor**
- **2 = Virginica**

---

## 🧰 Tools and Libraries Used

The project is written in **Python** and developed on **Google Colab**. The following libraries are used:

| Library | Description |
|--------|-------------|
| `pandas` | Data manipulation and structure (DataFrames) |
| `numpy` | Numerical operations |
| `matplotlib.pyplot` | Optional: Plotting graphs and data points |
| `sklearn.datasets` | To import the Iris dataset |
| `sklearn.model_selection` | To split data into training and testing sets |
| `sklearn.linear_model` | Contains the Logistic Regression algorithm |
| `sklearn.metrics` | To calculate model accuracy |

---

## ⚙️ Step-by-Step Implementation

### 1. **Import Required Libraries**

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score

## ✅ Output

accuracy:0.9666666666666667

SAMPLE PREDICTION :
![image](https://github.com/user-attachments/assets/846120b2-134a-4fa0-91a7-6d1d18a4b31f)

RESULT :
![image](https://github.com/user-attachments/assets/c8d74619-65fc-47f4-b9e0-6ffe40f3601a)

## 🙋‍♀️ Author
Done by Kulsum S G
University: B.S.A. Crescent Institute of Science and Technology
Internship: AI and ML Week 2 Internship at NSP Nexus

