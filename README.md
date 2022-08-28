# TMDB Box Office Prediction

# Introduction
The purpose of this project is to estimate revenue of movies by implementing advanced prediction models and machine learning. The dataset is provided by Kaggle, which involves a training data with 3000 rows and a test data set with 7398 rows. Both of them consist of 22 features which include budget, popularity,runtime, tagline, orignial language etc. The goal is to minimize the difference between prediction and the ground truth.

Data Download Link: https://www.kaggle.com/competitions/tmdb-box-office-prediction/data

# Attributes
| Column ID |         Column Name        | Data type |
|:---------:|:--------------------------:|:---------:|
|     0     |           id               |   int64   | 
|     1     |   belongs_to_collection    |   object  |
|     2     |          budget            |   int64   | 
|     3     |          genres            |   object  |
|     4     |          homepage          |   object  | 
|     5     |          imdb_id           |   object  |
|     6     |     original_language      |   object  | 
|     7     |      original_title        |   object  |
|     8     |         overview           |   object  | 
|     9     |        popularity          |  float64  |
|     10    |        poster_path         |   object  |
|     11    |    production_companies    |   object  | 
|     12    |    production_countries    |   object  | 
|     13    |       release_date         |   object  | 
|     14    |          runtime           |   float64 |
|     15    |      spoken_languages      |   object  |
|     16    |          status            |   object  |
|     17    |          tagline           |   object  |
|     18    |          title             |   object  | 
|     19    |         Keywords           |   object  | 
|     20    |          cast              |   object  |
|     21    |          crew              |   object  |
|     22    |         revenue            |   int64   |


# Methodology
<li> Exploratory Data Analysis
<li> Data Pre-Processing
<li> Modeling
<li> Training and Testing
<li> Evaluation

# Library Used
<li> sklearn
<li> xgboost
<li> lightgbm
<li> numpy
<li> pandas
<li> matpoltlib
<li> re
<li> datetime

# Algorithms Used
<li> Linear Regression
<li> Random Forest
<li> XGBoost (eXtreme Gradient Boosting)
<li> Light GBM
