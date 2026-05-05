# Health Data Analysis - Machine Learning Project

This project is an academic machine learning project focused on analyzing health-related data and comparing several classification models. The main objective is to identify which model performs best for analyzing age-related patterns related to hypertension and diabetes risk.

## Project Overview

The project uses a structured health dataset and applies machine learning techniques to support basic health data analysis. The workflow includes data preparation, exploratory data analysis, model implementation, model evaluation, model comparison, and result interpretation.

The classification models used in this project include:

- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Tree

Based on the project evaluation, Decision Tree and KNN achieved the strongest performance, with an accuracy of approximately **0.732240**.

## Objectives

The objectives of this project are:

- To analyze health-related data using machine learning methods.
- To compare the performance of Naive Bayes, KNN, and Decision Tree models.
- To identify the most suitable model for the given classification problem.
- To practice data preprocessing, model evaluation, and result interpretation in an academic machine learning context.

## Dataset

The dataset used in this project is stored in:

```text
main.csv
```

The dataset contains structured health-related records used for model training, testing, and evaluation.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Project Structure

```text
AIPROJECT/
│
├── Health.ipynb   # Main notebook containing data analysis and machine learning implementation
├── main.csv       # Dataset used in the project
└── README.md      # Project documentation
```

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/nazavalente/AIPROJECT.git
```

2. Open the project folder:

```bash
cd AIPROJECT
```

3. Open the notebook file:

```text
Health.ipynb
```

4. Run the notebook cells sequentially using Jupyter Notebook, JupyterLab, or Google Colab.

## Methodology

The project follows these main stages:

### 1. Data Preparation

The dataset was loaded, checked, cleaned, and prepared before model development. This stage helped ensure that the data could be used properly for classification tasks.

### 2. Exploratory Data Analysis

The dataset was explored to understand its structure, feature distribution, and possible patterns related to age, hypertension, and diabetes.

### 3. Model Development

Several classification models were implemented and tested, including:

- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Tree

Each model was used to compare how well it could classify the target variable based on the available health-related features.

### 4. Model Evaluation

The models were evaluated and compared based on their classification performance. The purpose of this stage was to identify which model was the most suitable for the dataset and classification objective.

### 5. Conclusion and Comparison

The final comparison showed that Decision Tree and KNN produced the strongest results for this dataset. These models performed better than Naive Bayes in this case.

## Evaluation

The models were compared based on their classification performance. Based on the project result, Decision Tree and KNN achieved the strongest performance, with an accuracy of approximately:

```text
0.732240
```

This result indicates that Decision Tree and KNN were more suitable than Naive Bayes for the given dataset and classification objective.

## Team Contribution

This project was completed as an academic group assignment. The main documented contributions were:

### Adhyatma Chrysostomos Davu

- Developed the data preparation and evaluation code.
- Prepared the presentation materials for the data preparation and evaluation section.
- Prepared the presentation materials for the Decision Tree section.

### Nazario Jose Valente da Cruz

- Developed the Naive Bayes algorithm implementation.
- Prepared the presentation materials for the Naive Bayes and KNN sections.
- Contributed to the conclusion and model comparison.
- Helped identify that Decision Tree and KNN were the most suitable models based on the evaluation results.

## My Contribution

My main contribution in this project was developing the Naive Bayes implementation and preparing the presentation materials for the Naive Bayes and KNN sections. I also contributed to the final model comparison and conclusion, where Decision Tree and KNN were identified as the strongest-performing models for this case.

## Results

The comparison showed that Decision Tree and KNN achieved the best performance in this project, with an accuracy of approximately **0.732240**.

This result indicates that Decision Tree and KNN were more suitable than Naive Bayes for the given dataset and classification objective.

## What I Learned

Through this project, I strengthened my understanding of:

- Basic machine learning workflow
- Data preparation and exploration
- Classification model implementation
- Naive Bayes algorithm
- Model comparison and evaluation
- Technical presentation and result interpretation

## Future Improvements

Several improvements can be made in future development, including:

- Adding more detailed data visualization.
- Improving feature selection and preprocessing.
- Testing additional classification models.
- Applying hyperparameter tuning to improve model performance.
- Providing a clearer explanation of each evaluation metric.
- Adding confusion matrix and classification report visualization for each model.

## Author

Nazario Jose Valente da Cruz  
Informatics Student  
Telkom University

## Repository

This repository contains the notebook, dataset, and documentation for the Health Data Analysis machine learning project.
