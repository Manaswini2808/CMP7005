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
