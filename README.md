# Training-state-detection-using-heart-rate-prediction

## Project Overview : 
This aimed to develop a detection model of training state in cycling based on a prediction of the heart rate response in a training session.

## Project Step : 

- Build a pipeline to retrieve data of cycling session using Strava or/and Garmin API
- Create a dataset of these session, probably build new metric in order to improve accuracy of the model
- Build a classification model to classify session in different category based on session summary (tss, IF, NP...)
- Build a model to predict heart rate in session (Neural Network ?) based on other metrics (power, cadence, temperature, work done previuolsy in session...), determine an interval of confidence
- Compare predicted heart rate to actuel heart rate and detect when the actual heart rate is not in the confidence interval previously build.
- Probably train different model with different training set (last week, last month, last 3 month) to compare the prediction and conclude to a fatigue/overtraining state or a progression compare to previous sessions.
