# Predictive Modelling Challenge

This project was developed as part of a university prediction challenge focused on solving multiple real-world estimation and forecasting problems using statistical analysis and machine learning techniques.

## Project Structure

```text
.
├── prediction_championship.ipynb
├── README.md
├── requirements.txt
├── data/
│   ├── F1.csv
│   └── forecast_data.csv
└── images/
    └── lake_area.png
```


## Project Overview

The project includes several independent problems requiring different approaches:

- Time series forecasting of an econometric variable
- Area estimation from an image (lake shape analysis)
- Functional estimation from limited observations
- Strategic prediction scenarios (e.g. auctions)
- Experimental estimation problems
- Sports outcome prediction

Each task required selecting an appropriate modelling strategy, analysing data, and justifying the assumptions made.

## Datasets

The following datasets are included:

- `forecast_data.csv`: Time series dataset used for forecasting
- `F1.csv`: Dataset used for prediction tasks

## 1. Econometric Time Series Forecasting

In this section, the objective was to predict the future value of an econometric variable using historical data from forecast_data.csv.

The work included:

Loading and cleaning temporal data
Exploring historical trends
Visualizing the evolution of the variable over time
Applying time series forecasting models
Testing ARIMA-based approaches
Improving the model with SARIMAX to capture seasonal patterns
Interpreting the forecast and its limitations

This part focused on understanding how past observations can be used to estimate future values, while taking into account trend and seasonality.

## 2. Lake Area Estimation from Image

In this section, the goal was to estimate the real-world area of a lake from a black-and-white image.

The work included:

Processing the image as visual data
Identifying the lake shape from the image
Estimating the number of pixels corresponding to the lake
Using scale information to convert pixels into real-world area
Approximating the final area based on image analysis

This problem required combining image interpretation, proportional reasoning and numerical estimation.

## 3. Functional Estimation from Limited Observations

This section focused on estimating the behaviour of an unknown function using limited available information.

The work included:

Analysing the given observations
Identifying possible trends or mathematical relationships
Testing different assumptions about the function
Estimating missing or future values
Justifying the selected approach

This part was especially focused on reasoning under uncertainty and selecting a plausible model with incomplete data.

## 4. Strategic Prediction Scenario

This section involved a prediction problem where the result depended not only on data, but also on the decisions of other participants.

The work included:

Analysing the rules of the strategic scenario
Considering possible behaviours from competitors
Estimating optimal or competitive values
Balancing risk and expected outcome
Making a final prediction based on rational assumptions

This part introduced game-theoretic reasoning and strategic decision-making.

## 5. Experimental / Physical Estimation Problem

This section required estimating the result of a physical or experimental situation.

The work included:

Understanding the variables involved in the experiment
Applying mathematical and statistical reasoning
Making assumptions where direct data was limited
Estimating the expected result
Discussing possible sources of error

This problem highlighted the importance of translating real-world situations into quantitative models.

## 6. Sports Result Prediction

This section used the F1.csv dataset to make predictions related to Formula 1.

The work included:

Loading and analysing structured sports data
Exploring relevant variables
Identifying patterns that could influence the prediction
Applying data-driven reasoning to estimate the final outcome
Interpreting the result based on available historical information

This part focused on applying predictive analytics to sports data.

Main Learning Outcomes

Through this project, I improved my ability to:

- Approach open-ended prediction problems
- Select appropriate methods depending on the type of data
- Work with time series, structured datasets and visual data
- Apply statistical and machine learning techniques
- Justify assumptions and modelling decisions
- Communicate results clearly in a notebook format

## Notes

This project was developed for academic purposes as part of the Data Science and Artificial Intelligence degree at Universidad Politécnica de Madrid.
## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Jupyter Notebook

