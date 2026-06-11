# Spotify Track Analytics

## Overview

What makes a song a hit?

This project explores the audio and musical characteristics that contribute to a song's success on Spotify. Using machine learning techniques, I analyzed Spotify track data and built predictive models to classify songs as hit or non-hit tracks based on their audio features.

The project combines exploratory data analysis, feature engineering, statistical preprocessing, and machine learning to uncover patterns behind commercially successful music.

---

## Problem Statement

The music industry generates thousands of songs every day, but only a small percentage become widely popular.

The objective of this project is to:

* Analyze audio characteristics of Spotify tracks
* Identify factors associated with successful songs
* Build machine learning models capable of predicting whether a track will become a hit
* Compare model performance across multiple classification algorithms

---

## Dataset

The dataset contains Spotify tracks with audio features and metadata including:

| Feature Category      | Examples                                     |
| --------------------- | -------------------------------------------- |
| Audio Features        | Danceability, Energy, Loudness, Acousticness |
| Musical Properties    | Key, Mode, Tempo, Time Signature             |
| Track Characteristics | Duration, Chorus Hit Score, Sections         |
| Engagement Target     | Hit / Non-Hit Classification                 |

### Key Features

* Danceability
* Energy
* Loudness
* Speechiness
* Acousticness
* Instrumentalness
* Liveness
* Valence
* Tempo
* Duration
* Chorus Hit Score
* Number of Sections

---

## Project Workflow

### 1. Data Exploration

* Performed exploratory data analysis (EDA)
* Examined feature distributions
* Identified outliers and anomalies
* Analyzed correlations among audio features
* Investigated relationships between features and song success

### 2. Data Preprocessing

* Missing value validation
* Feature transformation
* Feature scaling and normalization
* Outlier treatment
* Train-test splitting

### 3. Feature Engineering

* Statistical feature analysis
* Correlation-based insights
* Feature importance evaluation
* Dimensionality understanding

### 4. Machine Learning Models

The following classification models were evaluated:

* Logistic Regression
* Decision Tree
* Random Forest
* AdaBoost
* Gradient Boosting
* XGBoost

### 5. Hyperparameter Tuning

* GridSearchCV optimization
* Cross-validation
* Model performance comparison
* Best parameter selection

---

## Technologies Used

### Programming

* Python

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-learn
* XGBoost

### Model Evaluation

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC

---

## Key Findings

* Audio characteristics such as energy, loudness, danceability, and valence showed strong relationships with song popularity.
* Ensemble learning methods consistently outperformed traditional classification techniques.
* Random Forest emerged as the strongest overall model after hyperparameter tuning.
* Feature importance analysis revealed the most influential attributes contributing to hit song prediction.

---

## Project Structure
```
Spotify-Track-Analytics/
│
├── data/
│   ├── 70s.csv
│   ├── 80s.csv
│   ├── dataset-of-00s.csv
│   ├── dataset-of-10s.csv
│   ├── dataset-of-60s-selected-columns.csv
│   ├── dataset-of-90s.csv
│   └── spotify_all_combined.xlsx
│
├── spotify_all_combined.xlsx
│
├── notebook/
│   └── spotify_track_analytics.ipynb
│
└── README.md
```

## Future Improvements

* Incorporate artist popularity metrics
* Include Spotify streaming statistics
* Build a recommendation engine
* Deploy the model as a web application
* Experiment with deep learning approaches

---

## Results

The project demonstrates that machine learning can effectively identify patterns associated with successful songs and provides insights into the musical attributes that influence audience engagement.

While predicting music success remains challenging due to external factors such as marketing, artist influence, and cultural trends, audio features alone provide meaningful predictive power.

---

## Author
**Hariharan Nadanasabapathi**
