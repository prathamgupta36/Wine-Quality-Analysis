# Wine Quality Analysis

## Contents
- [Red Wine](#red-wine)
  - [Introduction](#introduction)
  - [Data Source](#data-source)
  - [Data Exploration and Cleaning](#data-exploration-and-cleaning)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Model Training and Evaluation](#model-training-and-evaluation)
- [White Wine](#white-wine)
  - [Introduction](#introduction-1)
  - [Data Source](#data-source-1)
  - [Data Exploration and Cleaning](#data-exploration-and-cleaning-1)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda-1)
  - [Model Training and Evaluation](#model-training-and-evaluation-1)

## Red Wine

### Introduction
In this project, we analyze the physicochemical properties of red wine to predict its quality using linear regression. The dataset used is from P. Cortez et al.'s study on modeling wine preferences through data mining. The goal is to understand the correlation between different features and the quality of red wine.

### Data Source
The dataset for red wine is obtained from the following source:
- [Wine Quality Data](https://raw.githubusercontent.com/prathamgupta36/Wine-Quality-Analysis/main/Data/winequality-red.csv)

### Data Exploration and Cleaning
We begin by loading the dataset and inspecting its structure. Null values are checked, and none are found. The column names are standardized for better readability.

### Exploratory Data Analysis (EDA)
EDA includes box plots to visualize the distribution of features and a pair plot to examine relationships between features, colored by wine quality. Heatmaps are used to identify feature correlations.

### Model Training and Evaluation
A linear regression model is trained using the sklearn library. The model is then evaluated using Mean Squared Error (MSE) and the Ordinary Least Squares (OLS) principle. The evaluation results provide insights into the model's performance.

## White Wine

### Introduction
Similar to the red wine analysis, this project aims to predict the quality of white wine based on physicochemical properties using linear regression. The dataset is from the same source as the red wine data.

### Data Source
The dataset for white wine is obtained from the following source:
- [Wine Quality Data](https://raw.githubusercontent.com/prathamgupta36/Wine-Quality-Analysis/main/Data/winequality-white.csv)

### Data Exploration and Cleaning
The white wine dataset is explored and cleaned similarly to the red wine dataset, ensuring no null values are present.

### Exploratory Data Analysis (EDA)
EDA for white wine includes box plots, pair plots, and heatmaps to visualize feature distributions, relationships, and correlations, respectively.

### Model Training and Evaluation
The linear regression model is trained and evaluated for white wine, mirroring the process for red wine. Performance metrics and analysis results are provided.

---

*Note: The code and results provided above are summaries for documentation purposes. For the full code and interactive visualization, refer to the Jupyter Notebook or script in the respective project directories.*

---
*Disclaimer: The data used in this analysis is sourced from P. Cortez et al.'s study, referenced above. Any analysis or predictions made are based on the available data and the assumptions of the linear regression model. Users are encouraged to interpret the results critically and consider the limitations of the dataset.*
