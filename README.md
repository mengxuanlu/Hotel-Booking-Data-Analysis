# Hotel-Booking-Data-Analysis

## Project Overview

The goal of this project is to predict the hotel booking demand, specifically if the booking will be cancelled. The source of the data is from https://www.kaggle.com/jessemostipak/hotel-booking-demand, which includes booking information from two different hotels from 2015 to 2017, with 119390 rows and 32 columns. The programme language I used is python.

## Exploratory Data Analysis

The dataset contains data from two different hotels, one is resort hotel, the other is city hotel. I conducted exploratory data analysis by answering below ten questions.

1) Where do guests come from?<br />
2) Where do the bookings come from?<br />
3) What is the ADR by booking channels?<br />
4) What is the ADR per month for each hotel?<br />
5) What is the customer type for each hotel?<br />
6) How long do guests stay on average at each hotel?<br />
7) Do guests tend to cancel their bookings if they booked earlier?<br />
8) Do guests booked directly tend to cancel?<br />
9) Do guests who paid no deposit tend to cancel?<br />
10) Do guests tend to cancel if they cancelled before?<br />

## Evaluate Feature Importance

By evaluating feature importance, I successfully narrowed down the features to a limited number, which helped the prediction in the following step.

## Predict Cancellation

Cancellation prediction plays a crucial role in forecasting demand and improving sellout efficiency, thus maximizing hotel revenue. I tried four models, which are random forest, decision trees, logistic regression and XGBoost, and compared their performances. After the evaluation, random forest model gave the best performance.

