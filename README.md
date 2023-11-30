# Overtraining State Detection Using Heart Rate Prediction

## Project Overview:

This project aims to develop a model for detecting the training state in cycling based on predicting the heart rate response during a training session.

## Project Steps:

- **Build a Data Retrieval Pipeline:**
  - Develop a pipeline to retrieve data from cycling sessions using Strava and/or Garmin API.
  - Preprocess the data and create a dataset, exploring the creation of new metrics to enhance model accuracy.

- **Session Classification or Clustering:**
  - Build a classification or clustering model to categorize sessions based on summary metrics such as TSS, IF, NP, etc.
  - If necessary, manually label a training set for activities (e.g., endurance, home trainer endurance, interval training) to aid classification.

- **Heart Rate Prediction Model:**
  - Develop a model, possibly a neural network, to predict heart rate during sessions based on various metrics (power, cadence, temperature, previous work done).
  - Determine a confidence interval for the predictions.

- **Comparison and Anomaly Detection:**
  - Compare predicted heart rate with actual heart rate and detect deviations outside the confidence interval.
  - Evaluate model performance using relevant metrics (accuracy, precision, recall).

- **Long-Term Analysis:**
  - Train different models with distinct training sets (last week, last month, last 3 months) for comparative analysis.
  - Draw conclusions about fatigue, overtraining, or progression based on the comparison results.

