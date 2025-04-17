# Titanic-EDA-Project
# Task 1 – Exploratory Data Analysis (EDA) on Titanic Dataset

## Objective:
To perform exploratory data analysis on the Titanic dataset and identify important patterns and relationships, especially in terms of survival.

## Dataset:
The dataset contains information about Titanic passengers such as:
- Passenger ID
- Age
- Fare
- Sex
- SibSp (Siblings/Spouses aboard)
- Parch (Parents/Children aboard)
- Pclass (Passenger class)
- Embarked
- Survived (Target variable)

## Steps Followed:
1. Loaded and explored the dataset
2. Removed unnecessary columns and fixed column names
3. Handled missing values (none in this case)
4. Created visualizations to explore relationships in the data

## Visualizations:
### Survival Count
![Survival Plot](count.png)

### Survival by Gender
![Gender Plot](Gender.png)

### Correlation Heatmap
![Heatmap](Heatmap.png)

## Observations:
- More males died, more females survived.
- 1st class passengers had better survival rates.
- Socioeconomic status and gender affected survival chances.

Task 2: Sentiment Analysis – IMDB Dataset
Objective:
Build a model to classify IMDB movie reviews as positive or negative using Natural Language Processing (NLP).

Key Steps:
Text cleaning: removed punctuation, stopwords, and applied lemmatization
Vectorization using TF-IDF
Used Logistic Regression to classify sentiments


Model Evaluation:
Accuracy: ~85–90%
F1-score: Balanced between positive and negative classes

Task 3: Fraud Detection – Credit Card Transactions

Objective:
Detect fraudulent transactions from a dataset with highly imbalanced classes.

Key Steps:
Explored the Class column: 0 (normal), 1 (fraud)
Used Logistic Regression to classify frauds
Applied train-test split with stratified sampling


Model Evaluation:
High recall is crucial for fraud detection

Confusion matrix helped visualize performancel

Task 4: House Price Prediction – Boston Dataset

Objective:
Predict the price of a house using regression techniques on the Boston Housing Dataset.

Key Steps:

Handled missing values with fillna

Used Linear Regression

Evaluated model with MAE, MSE, and R² Score


Model Evaluation:

MAE: ~3.2

MSE: ~21.5

R² Score: ~0.74

Scatter plot between actual and predicted prices created for visualization
