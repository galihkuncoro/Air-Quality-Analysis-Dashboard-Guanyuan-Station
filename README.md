# Data Analysis Project: Air Quality Guanyuan

## Live Dashboard
https://air-quality-analysis-dashboard-guanyuan-station-uf2zqwxyxn44od.streamlit.app/

## Project Overview
This project, which is a submission for Dicoding's "Learn Data Analysis with Python" course, centers on the analysis of air quality data, specifically emphasizing PM2.5 concentrations gathered from the Wanshouxigong station. The primary aim is to reveal patterns, seasonal fluctuations, and the influence of diverse weather conditions on air quality.


## Table of Contents
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Libraries Used](#libraries-used)
- [Key Insights](#key-insights)
- [About Me](#about-me)

## Introduction
The aim of this project is to examine data related to air quality, particularly focusing on the levels of PM2.5 pollutants, and comprehend their associations with diverse environmental elements. The analysis involves recognizing patterns over time, seasonal variations, and connections with different weather conditions.

## Data Source
The data utilized for this project comprises measurements of air quality obtained from the Wanshouxigong station. The primary emphasis is on PM2.5 levels, along with additional correlated environmental information.

## Libraries Used
- Streamlit
- Pandas
- Matplotlib
- Seaborn
- NumPy
- SciPy
- Statsmodels

## Key Insights
The primary observations include fluctuations in PM2.5 levels throughout different seasons, displaying elevated concentrations during colder months. Additionally, a correlation exists between PM2.5 levels and weather elements such as temperature and humidity. Furthermore, discernible trends and patterns are evident from the time series analysis.

## How to Run the Dashboard

To run the Air Quality Analysis Dashboard, follow these steps:

### Setup Environment

1. **Create and Activate a Python Environment**:
   - If using Conda (ensure [Conda](https://docs.conda.io/en/latest/) is installed):
     ```
     conda create --name airquality-ds python=3.11
     conda activate airquality-ds
     ```
   - If using venv (standard Python environment tool):
     ```
     python -m venv airquality-ds
     source airquality-ds/bin/activate  # On Windows use `airquality-ds\Scripts\activate`
     ```

2. **Install Required Packages**:
   - The following packages are necessary for running the analysis and the dashboard:
     ```
     pip install pandas numpy scipy matplotlib seaborn streamlit statsmodels
     ```

     or you can do
     ```
     pip install -r requirements.txt
     ```
### Run the Streamlit App

1. **Navigate to the Project Directory** where `dashboard.py` is located.

2. **Run the Streamlit App**:
    ```
    streamlit run dashboard.py
    ``` 


## About Me
- **Name**: Galih Kuncoro Jati
- **Proyek Akhir** : Analisis Data
- **Kelas** : Belajar Analisis Data dengan Python
