# Airline Ticket Price Prediction

## Project Overview
This project was developed for CIS 4321: Data Mining at California State Polytechnic University, Pomona.

The objective was to predict airline ticket prices using machine learning techniques and compare the performance of different regression models.

## Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Google Colab
- GridSearchCV

## Dataset
The analysis used a dataset of 1,200 airline flight observations, with features including airline, departure and destination cities, number of stops, flight duration, travel class, and days remaining before departure.

## Machine Learning Models
Three regression models were developed and evaluated:

1. Linear Regression
2. Decision Tree Regression
3. K-Nearest Neighbors (KNN) Regression

Model performance was evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R².

## Results

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 4,580 | 6,813 | 0.91 |
| Decision Tree | 3,305 | 6,177 | 0.93 |
| KNN (k=15) | 10,178 | 13,768 | 0.65 |

The Decision Tree model achieved the strongest predictive performance among the three models tested.

## Key Takeaways
- Applied machine learning techniques to a real-world pricing problem.
- Compared regression models using multiple evaluation metrics.
- Used GridSearchCV to optimize Decision Tree performance.
- Developed practical experience with data preprocessing, predictive modeling, and model evaluation.
