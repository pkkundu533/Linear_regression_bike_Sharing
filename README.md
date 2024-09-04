# Bike Demand Prediction for BoomBikes

> A multiple linear regression model to predict the demand for shared bikes in the American market for BoomBikes, a bike-sharing service provider.

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- **Project Background**: BoomBikes, a US-based bike-sharing service provider, has experienced significant revenue loss due to the COVID-19 pandemic. As part of its recovery strategy, the company aims to predict the demand for shared bikes in the post-pandemic market. Understanding the factors affecting bike rentals can help BoomBikes optimize its operations, improve customer satisfaction, and maximize profits.
- **Business Problem**: The company wants to understand which factors influence bike demand, so they can adjust their services accordingly. By predicting demand, BoomBikes can ensure availability during peak times and manage resources effectively.
- **Dataset**: The dataset contains daily records of bike rentals and includes variables such as weather conditions, temperature, humidity, wind speed, and whether it was a working day or holiday. The target variable is the total number of bike rentals (`cnt`), which is a combination of casual and registered users.

## Conclusions
- **Conclusion 1**: Higher temperatures and favorable weather conditions significantly increase bike demand.
- **Conclusion 2**: Bike demand is seasonal, with the highest demand in the summer and fall.
- **Conclusion 3**: Year-over-year growth in demand suggests an increasing trend in bike rentals.
- **Conclusion 4**: Adverse weather conditions (rain, snow) have a negative impact on bike rentals.

## Technologies Used
- **Python** - 3.8
- **Pandas** - 1.3.3
- **NumPy** - 1.21.2
- **Matplotlib** - 3.4.3
- **Seaborn** - 0.11.2
- **scikit-learn** - 0.24.2
- **statsmodels** - 0.12.2

## Acknowledgements
- This project was inspired by an UpGrad machine learning assignment to build a multiple linear regression model for demand prediction.
- The dataset was provided by BoomBikes for the purpose of this analysis.
- Based on concepts covered in [this course](https://www.upgrad.com/).

## Contact
Created by [@githubusername] - feel free to contact me!
