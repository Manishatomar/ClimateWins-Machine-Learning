# Weather Conditions & Climate Change with ClimateWins
Implementing optimization techniques, including gradient descent, and employing supervised machine learning algorithms such as K-Nearest Neighbor (KNN), Decision Tree, and Artificial Neural Networks (ANN) to determine the most effective method for predicting daily weather conditions conducive to outdoor activities and everyday comfort, commonly referred to as "pleasant" weather.
# Context
ClimateWins, a nonprofit organization, is dedicated to tackling the challenges of climate change, with a focus on the rise of extreme weather events across mainland Europe over the past 10 to 20 years. The organization recognizes the potential of advanced tools like machine learning in predicting and mitigating the impacts of these weather extremes. By analyzing weather data spanning the past century, ClimateWins aims to build a predictive model to provide valuable insights into future weather patterns and improve preparedness.
Key Questions
* How is machine learning used in weather forecasting?
* What ethical concerns surround the use of ML and AI?
* What are the historical extremes in temperature?
* Can machine learning be employed to predict weather conditions on specific days?
# Data Source
The [dataset](https://github.com/Manishatomar/Dataset/blob/main/Dataset-weather-prediction-dataset-processed.csv) comprises weather observations from 18 weather stations across Europe, covering the period from 1960 to 2022. It includes near-daily recordings of variables such as temperature, wind speed, snowfall, global radiation, and more, collected by the [European Climate Assessment & Dataset project](https://www.ecad.eu/). Additionally, a [supplementary dataset](https://github.com/Manishatomar/Dataset/blob/main/Dataset-Answers-Weather_Prediction_Pleasant_Weather.csv) was utilized to train the machine learning models, categorizing each day as either 1 (pleasant weather) or 0 (unpleasant weather).
# Project Hypotheses
* Europe has experienced a statistically significant rise in average annual temperatures over the past two decades.
* Machine learning models trained on historical data demonstrate high accuracy in predicting future extreme weather events.
* Supervised learning models are especially effective in forecasting the likelihood of pleasant weather conditions on a given day.
# Project Folder Structure
The project files are organized into the following folders:

* 01 Project Management: includes the Project Brief.
* 02 Data: divided into two subfolders:
  * Original Data: unscaled weather data + pleasant weather prediction data
  * Prepared Data: scaled weather data 
* 03 Scripts: contains Jupyter notebooks with the corresponding code.
* 04 Analysis/Visualizations: holds relevant visuals.
* 05 Sent to Client: contains a [pdf presentation](https://github.com/Manishatomar/Dataset/blob/main/Manisha%20Achievement%201-Task%201.6.pdf) to ClimateWins stakeholders.
