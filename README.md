# Rainfall-prediction
Data Science and Machine Learning projects with source code.
# Rainfall Prediction Project

## Overview
This project focuses on predicting rainfall using historical weather data from Austin. The dataset is cleaned and preprocessed to remove unnecessary features and handle missing values before applying predictive modeling techniques.

## Dataset
- **Source:** `austin_weather.csv`
- **Preprocessing Steps:**
  - Dropped unnecessary columns like `Events`, `Date`, and `SeaLevelPressureAvgInches`.
  - Replaced missing values and anomalies (`T`, `-`) with appropriate numerical values.
  - Saved the cleaned dataset as `austine_weather_final.csv`.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Open the `Rainfall_prediction.ipynb` notebook in Jupyter Notebook.
3. Run all the cells sequentially to preprocess the data and perform analysis.

## Results
- The project identifies patterns in weather data.
- The cleaned dataset can be used for further predictive modeling.



