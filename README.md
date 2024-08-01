# Titanic Survival Analysis Project

![](https://media-exp1.licdn.com/dms/image/C5612AQFutMYjrIM-gg/article-cover_image-shrink_720_1280/0/1601702195306?e=2147483647&v=beta&t=MIW3C0KsviPh937da_MtQswn9Clz3b2q4PPJQuKHrS0)


The aim of this project is to analyze the factors influencing the survival of passengers aboard the Titanic using machine learning techniques. The project involves loading the Titanic dataset, exploring and preprocessing the data, visualizing various features to understand their impact on survival, and selecting the most relevant features for the predictive model. The data is then split into training and testing sets, and a machine learning model is trained to predict the survival of passengers. Finally, the model's performance is evaluated and is done in the file [`Titanic_survival_analysis.ipynb`](https://github.com/Anuraghaldar/Python-Data-Analysis/blob/main/Titanic_survival_analysis.ipynb) using the dataset of Titanic Survival [`Titanic_survival_dataset.csv`](https://github.com/Anuraghaldar/Titanic-Survival-Analysis/blob/main/Titanic_survival_dataset.csv).

## Process Steps

### 1. Import Essential Libraries
Import necessary libraries for data manipulation, visualization, and machine learning such as :
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn


### 2. Loading the Data
Load the Titanic dataset [`Titanic_survival_dataset.csv`](https://github.com/Anuraghaldar/Titanic-Survival-Analysis/blob/main/Titanic_survival_dataset.csv).

### 3. Data Exploration
Display the first few rows and get an overview of the dataset.

### 4. Data Cleaning and Preprocessing
- Handle missing values.
- Convert categorical variables into numerical values.
- Drop irrelevant columns.

### 5. Data Visualization
Visualize the distribution of features and their relationship with the target variable.

### 6. Feature Selection
Select relevant features for the model and create feature matrix `X` and target vector `Y`.

### 7. Splitting the Data
Split the dataset into training and testing sets.

### 8. Model Building and Training
Train the model using a chosen algorithm.

### 9. Model Evaluation
Predict on both training and testing sets and calculate accuracy.
