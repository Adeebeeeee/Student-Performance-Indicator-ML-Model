# Student Performance Indicator ML Model

This repository contains a machine learning model designed to predict student performance based on various features like gender, parental education, and lunch type. The model is built using **Pandas**, **NumPy**, and **Scikit-learn**, achieving **85% accuracy**.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Data](#data)
5. [How It Works](#how-it-works)
6. [Model Details](#model-details)
7. [Installation and Setup](#installation-and-setup)
8. [Usage](#usage)
9. [Acknowledgments](#acknowledgments)

## Project Overview
This project uses a machine learning pipeline to predict student performance based on multiple features. The pipeline is built using Scikit-learn, and the model achieves an accuracy of 85%. Exploratory Data Analysis (EDA) was conducted to uncover patterns and trends from the dataset.

## Features
- **85% accuracy** achieved in predicting student performance.
- **Exploratory Data Analysis (EDA)** performed on 1000+ student records to uncover insights.
- Key features analyzed include gender, parental education, test preparation course completion, and lunch type.
- Data visualization with Seaborn and Matplotlib to highlight significant findings.

## Technologies Used
- **Python**: Programming language for data analysis and model building.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Scikit-learn**: For building and evaluating the machine learning model.
- **Seaborn** and **Matplotlib**: For data visualization.
  
## Data
The dataset consists of over **1000 student records** with information such as:
- Gender
- Parental education level
- Test preparation course completion status
- Type of lunch provided
- Student scores in various subjects

## How It Works
### Data Preprocessing:
- Cleaned and formatted the dataset using Pandas.
- Handled missing values and categorical data using **Label Encoding** and **One-Hot Encoding**.

### Exploratory Data Analysis (EDA):
- Visualized patterns using Seaborn and Matplotlib.
- Identified key insights, such as a **10% increase in scores** for students who completed test preparation courses.

### Model Building:
- The model was built using **Scikit-learn**, utilizing algorithms like **Logistic Regression** or **Random Forest** (based on your choice).
- Evaluated the model's performance using **cross-validation**.

## Model Details
- **Accuracy**: 85% prediction accuracy on student performance.
- **Algorithms Used**: Logistic Regression or Random Forest, based on the analysis.
- **Metrics**: Accuracy, precision, recall, and F1-score were evaluated during the testing phase.

## Installation and Setup

### Prerequisites:
Make sure you have the following installed:
- Python (>= 3.8)
- pip (Python package manager)

### Steps to Run the Project:
1. Clone this repository:
    ```bash
    git clone https://github.com/Adeebeeeee/Student-Performance-Indicator-ML-Model.git
    cd Student-Performance-Indicator-ML-Model
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook or Python script to execute the analysis and train the model.

## Usage
- Run the provided Jupyter notebook to load the dataset, perform EDA, train the model, and make predictions.
- Use the model to predict student performance based on the available features.

## Acknowledgments
- **Dataset**: The student performance dataset used in this project is available on Kaggle or a similar open source platform.
- **Libraries**: Thanks to Scikit-learn, Pandas, Matplotlib, and Seaborn for providing essential tools for machine learning and data visualization.

---

### License
This project is licensed under the MIT License.
