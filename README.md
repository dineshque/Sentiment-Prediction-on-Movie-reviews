# Sentiment-Prediction-on-Movie-reviews


## Introduction

The "Sentiment Prediction on Movie Reviews" competition, hosted by IITM on Kaggle, challenged participants to build a machine learning model capable of predicting the sentiment of movie reviews. The competition ran from May 24, 2023, to August 14, 2023, and attracted:

- **1,273 entrants**
- **977 participants**
- **13,985 submissions**

## Notebook 
  Link :- https://colab.research.google.com/drive/1qJ8tc3uhDsnyo8uq1uos6toz_75Iks7J?usp=sharing

### Objective
- **Primary Goal**: Accurately classify the sentiment of review texts as positive, negative, or neutral.

### Dataset
- **Content**: The dataset included movie titles, descriptions, genres, durations, directors, actors, user ratings, review texts, and reviewer names.

### Approach
1. **Data Loading**: Imported the dataset and loaded it into a pandas DataFrame.
2. **Data Preprocessing**:
   - Removed duplicates and joined data.
   - Separated features and labels.
   - Split data into training and testing sets.
   - Modified the 'Boxoffice' column and handled missing values.
   - Converted data types as necessary.
3. **Exploratory Data Analysis (EDA)**:
   - Visualized the preprocessed data.
   - Analyzed data mathematically and checked for correlations between columns.
   - Identified and handled outliers.
4. **Feature Engineering**:
   - Applied feature scaling and encoded categorical features.
   - Combined transformed columns into a single DataFrame.
   - Selected features using Chi-squared (Chi2) test.
5. **Model Selection and Training**: Experimented with various machine learning models and trained them on the dataset.
6. **Model Evaluation**: Evaluated model performance using appropriate metrics.
7. **Hyperparameter Tuning**: Used RandomizedSearchCV to optimize model hyperparameters.

### Results
- **Best Score**: 0.81701
- **Private Score**: 0.81701
- **Accuracy**: Achieved an accuracy score of 81.7% on the test set.
