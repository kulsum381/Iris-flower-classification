Objective
The goal of the project is to build a model that can accurately classify the species of an Iris flower based on four key features:

Sepal Length (cm)
Sepal Width (cm)
Petal Length (cm)
Petal Width (cm)

The dataset includes three species of Iris flowers:

Iris-setosa
Iris-versicolor
Iris-virginica

By analyzing the relationships between these features, a machine learning model can learn to predict the species of an unseen flower with high accuracy.

 Dataset Description
 
The dataset contains 150 samples, 50 from each species. It is balanced, well-structured, and has no missing values, which makes it ideal for practicing classification algorithms. This dataset was originally introduced by the British biologist and statistician Ronald Fisher.

Each row in the dataset represents a single flower with the four measured features and its corresponding species label.

What I Did in This Project
This project follows a standard machine learning pipeline:

1. Data Preprocessing
Loaded the dataset using Pandas.

Assigned meaningful column names to the dataset.

Checked for missing values, duplicate entries, and outliers.

Displayed basic statistics such as mean, standard deviation, and data types.

2. Exploratory Data Analysis (EDA) and Visualization
Used Seaborn and Matplotlib to:

Create pairplots to visualize relationships between features.

Plot histograms and box plots to understand distributions and detect outliers.

Visualize the class distribution to ensure the data is balanced.

Observed clear separations between some classes based on petal length and width, which indicated that the features were informative.

3. Model Building
Implemented three different classification models using Scikit-learn:

k-Nearest Neighbors (k-NN): A simple and effective algorithm based on feature similarity.

Support Vector Machine (SVM): A powerful algorithm that works well for linear and non-linear classification tasks.

Logistic Regression: A linear model used for binary and multiclass classification.

4. Model Evaluation
Split the dataset into training and testing sets.

Evaluated models using:

Accuracy Score: The percentage of correct predictions.

Confusion Matrix: A breakdown of correct and incorrect predictions by class.

Classification Report: Included precision, recall, and F1-score for deeper insights.
