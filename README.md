
# Spotify Song Popularity Prediction

This project analyzes a Spotify songs dataset and builds a model to predict the popularity score of songs based on audio features.

## Data Analysis & Modeling Pipeline

The end-to-end pipeline followed in this analysis is:

### Data Loading & Inspection

- Load the `spotify_songs.csv` dataset
- Inspect data types, null values, duplicates etc.
- Fix issues like missing values
- Create new features like year, month etc. from album release date

### Exploratory Data Analysis

- Distribution of songs across release years 
- Music trends over decades analyzing attributes like acousticness, liveness, tempo
- Analysis of songs and artists across music genres
- Finding top artists by popularity and number of songs
- Correlation analysis between different audio features

### Data Preprocessing

- Handle outliers in features like loudness
- Select most relevant features using statistical tests 
- Standardize features for modeling  

### Model Building

- Split data into train and test sets
- Train a Linear Regression model
- Evaluate model performance using RMSE
- Train a Random Forest Regressor as an alternate model

### Model Usage

The trained models can be used to make predictions on new songs. The audio features of a song can be passed as input to the model to generate predicted popularity score.

## Libraries Used

- Pandas - For data manipulation
- Matplotlib & Seaborn - For visualization
- Scikit-Learn - For model building

## Future Improvements

Some ways to further improve the analysis:

- Try more advanced regression algorithms like XGBoost
- Optimize hyperparamaters of models through grid search 
- Incorporate text content of songs like lyrics to improve predictions
- Deploy model via API for easier usage

## References

The Spotify song dataset is taken from Kaggle.

## Author  
@Jigyansu Rout

