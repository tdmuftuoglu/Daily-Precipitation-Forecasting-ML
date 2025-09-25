# Daily Precipitation Forecasting with Machine Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KULLANICI_ADINIZ/Daily-Precipitation-Forecasting-ML/blob/main/DailyPrecipForecastML.ipynb)

A comprehensive machine learning pipeline to forecast daily precipitation using the NASA POWER dataset. This project was developed by **Dr. Tevfik Denizhan Müftüoğlu**.

---

## About the Project

This repository contains the complete code and data for a study on daily precipitation forecasting. The project implements a systematic workflow that includes:
1.  **Independent Statistical Analyses**: Gumbel Return Period analysis and Theil-Sen trend analysis on extreme weather events.
2.  **Automated Feature Selection**: An XGBoost-based method to identify the most predictive features from meteorological data.
3.  **Comprehensive Model Competition**: A head-to-head comparison of 11 different time-series and machine learning models to identify the best performer.
4.  **In-depth Visualization**: Generation of performance charts, time-series comparisons, and architectural diagrams.

The primary tool used is a Google Colab notebook (`.ipynb`), which ensures a fully reproducible and environment-independent analysis.

## Features

- **Data Analysis**:
  - Gumbel Distribution for return period analysis of extreme precipitation.
  - Mann-Kendall / Theil-Sen analysis for trend detection in extreme events.
- **Machine Learning Models Implemented**:
  - **Tree-based**: XGBoost, LightGBM, Random Forest
  - **Statistical**: SARIMAX, Prophet
  - **Neural Networks**: ANN (Artificial Neural Network), LSTM, GRU
  - **Ensemble Methods**: Stacking Ensemble, Hybrid (Prophet + XGBoost)
- **Outputs**: The script automatically generates and saves performance tables, comparison plots, and model architecture diagrams.

## How to Run

This project is designed to be run in Google Colab, which requires no local setup.

**Prerequisites:**
- A Google Account.
- The dataset file: `NASAPOWERDATASET.csv`.

**Steps:**

1.  **Open the Notebook**: Click the "Open in Colab" badge at the top of this README.
2.  **Upload Data**: When the code prompts for a file upload in the second step (`STEP 2`), select the `NASAPOWERDATASET.csv` file from your local machine.
3.  **Run the Code**: In Colab, go to the "Runtime" menu and select "Run all".

The notebook will handle all library installations, data processing, model training, and visualization, downloading the results directly to your browser.

## Dataset

The dataset used is `NASAPOWERDATASET.csv`, which is sourced from the [NASA POWER Project](https://power.larc.nasa.gov/). It contains daily time-series data for various meteorological parameters.

## How to Cite

If you use the code, data, or methodology from this project in your research, I kindly ask that you cite the software archive directly using its Zenodo DOI. This ensures that the work is properly credited and allows others to find your exact version of the code.


*Please check this repository for any future updates regarding related academic publications.*

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.
