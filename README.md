# Data Science Mini Project

## Introduction

This project is a mini project for the Data Science course at HTL Wiener Neustadt. The goal is to explore, analyze, clean, visualize, and model a health-related dataset using common machine learning techniques and best practices in data science.

## Team

* [Akos Papp](https://github.com/PPAPSONKA)
* [Itmam Alam](https://github.com/itmam07)

## Data

* **Dataset**: [Predict Students' Dropout and Academic Success](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success) 
* **Download** the necessary files and **describe all attributes** in the notebook, including:

  * Data types
  * Classes / Labels (if applicable)
* **Initial standard analysis**:

  * `.sample()`, `.head()`, `.info()`, `.describe()`
  * `.unique()` where meaningful


## Data Visualization

* Use **Seaborn** and **Matplotlib** to create and discuss **at least 4 different diagram types**, including:

  * Correlation (e.g., `heatmap()` or `matshow()`)
  * Histograms / KDE
  * Scatterplots
  * Boxplots / Violinplots
* Include a **custom color palette**
* Provide a **discussion for each visualization**
* Include a **class imbalance analysis** with a suitable **visualization**

## Data Cleaning

If necessary (or explain why not needed):

* Identify and correct **wrong values**
* Handle **missing values**
* Perform **justified feature reduction or type conversions**
* Save the **cleaned and, if applicable, merged dataset** as `korr.csv`

## Data Preparation

* Create **separate preprocessing pipelines** for each algorithm:

  * SVM
  * Decision Tree
  * Random Forest
  * k-Nearest Neighbors
  * Logistic Regression
* Split the data into **training and validation sets** using **stratified sampling**
* Save:

  * **Numerical values** → `num.csv`
  * **Normalized values** → `norm.csv`
  * **Nominal values** → `nom.csv`


## Model Training and Evaluation

* For **each algorithm**:

  * Apply **GridSearchCV (cv=5)** for hyperparameter optimization
  * Time the optimization process (≤ 15 minutes per algorithm)
  * Train and validate using the optimized parameters
  * Show and discuss the **decision boundary** (see: [Decision Surface Tutorial](https://data-science-crashkurs.de/chapters/kapitel_07.html#id2))
* Create and discuss a **performance comparison table** using:

  * Accuracy
  * F1 Score
  * Precision
  * Recall
  * MCC (Matthews Correlation Coefficient)
* If applicable (binary classification):

  * Show a **confusion matrix** and discuss the result

## Conclusion

Summarize key findings, model performance insights, and potential next steps or applications of the models. Include reflections on what worked well and what could be improved.

<small>**Disclaimer**</small>

<small>This README.md has been translated by ChatGPT.</small>