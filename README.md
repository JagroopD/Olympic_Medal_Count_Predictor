# 🏅 Olympic Medal Count Predictor 

## Project Overview

The Olympic Medal Count Predictor is a machine-learning project aimed at analyzing Olympic data from 1960 
onwards to predict the number of medals a country might win at a future Summer Olympic Games. 
I identified key factors contributing to medal counts and built a predictive model around them. 

## Data
The datasets included in this project:
- **athlete_events.csv:** Obtained from Kaggle dataset, includes athletes (ID, Name, Sex, Age, Height, Weight, Country, Sport, Event, etc.)
- **teams.csv:** Obtained from manipulating athlete_events.csv to group data by country and year

### Data Analysis
- **Correlation Analysis** → Found strong correlations between medal count and:
  - Previous medals (0.92)
  - Number of athletes (0.84)
  - Number of events (0.77)
- **Visualization:** Scatter plots and regression lines highlight linear relationships between features and medals won.

## Machine Learning Model 
Outline used for implementing machine learning model:
1. Explore data and find correlations
2. Reshape/Clean data for ML
3. Pick an error metric
4. Split dataset
5. Train model

**Model Used:** Linear Regression, used to predict medal counts based on past data.



## 🚀 Future Improvements
- Implement more advanced models (e.g., Random Forest, Neural Networks).
- Include economic & funding data for better predictions.
- Improve handling of smaller countries with limited historical data.


## Acknowledgements
- **Data**: [120 years of Olympic history: athletes and results](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
