# CMP7005

Overview

This project focuses on analysing air pollution in Beijing by handling real-world environmental data, performing exploratory data analysis (EDA), building predictive models, and developing a graphical user interface (GUI) application. The application is designed to assist users in understanding pollutant trends and forecasting PM2.5 concentration levels using machine learning models.


Objectives

    To handle and preprocess air quality and meteorological data from multiple sites.

    To perform comprehensive EDA to uncover key insights.

    To build and evaluate machine learning models for PM2.5 prediction.

    To design and implement a multipage desktop GUI using Python’s Tkinter framework.

    To demonstrate version control practices using Git and GitHub.

CMP7005_PRAC1/
│
├── data/
│   ├── raw/                       # Original datasets (csv)
│   └── processed/                 # Cleaned and merged data
│
├── src/
│   ├── eda.py                     # Functions for data exploration
│   ├── modelling.py               # ML model training and evaluation
│   └── preprocessing.py           # Data cleaning and feature engineering
│
├── gui/
│   ├── main.py                    # Main GUI launcher
│   ├── page_overview.py           # GUI Page 1: Data Overview
│   ├── page_eda.py                # GUI Page 2: EDA Visualisations
│   └── page_prediction.py         # GUI Page 3: Prediction Module
│
├── figures/                       # Output plots and charts
├── README.md                      # Project documentation
├── CMP7005_Report.ipynb          # Main notebook (all tasks)
└── requirements.txt              # List of Python libraries used








Key Components
1. Data Handling

Data from four station types (urban, suburban, rural, industrial) were selected and merged. Preprocessing steps included:

    Missing value imputation

    Feature extraction (timestamp features)

    Data cleaning and normalisation

2. Exploratory Data Analysis (EDA)

EDA was conducted using:

    Summary statistics and distribution plots

    Correlation heatmaps

    Seasonal and temporal visualisations

3. Modelling

Three regression models were developed:

    Linear Regression

    Random Forest Regressor

    XGBoost Regressor
    The Random Forest model achieved the highest accuracy based on R², MAE, and RMSE scores.

4. GUI Application

A multipage GUI was implemented with Tkinter, providing:

    Page 1: Dataset overview with pollutant trends

    Page 2: Interactive EDA visualisations

    Page 3: PM2.5 prediction based on user inputs

5. Version Control

All work was version-controlled using Git. The repository contains:

    Clean commit history

    Modular code development

    Feature branches for testing
