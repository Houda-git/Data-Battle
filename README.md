# 🌩️ Lightning Event End Prediction

## Project Overview

This repository contains the complete **data science pipeline** developed during a hackathon to analyze lightning activity around airports and build models capable of **predicting the end of a thunderstorm lightning event**.

Currently, airport safety procedures require waiting **30 minutes after the last detected lightning strike** before declaring the end of a lightning event. The objective of this project is to use historical lightning data to **predict earlier when an event is likely to end**, potentially helping airports reduce unnecessary operational delays while maintaining safety.

The dataset contains detailed records of **lightning strikes detected within a 30 km radius around several airports**, including temporal, spatial, and physical characteristics of each lightning event.

---

## Repository Structure

This repository contains the different stages of the data science workflow:

- **Exploratory Data Analysis (EDA)**  
  Initial data inspection, understanding variable distributions, identifying missing values, and analyzing the structure of lightning events.

- **Data Cleaning**  
  Handling missing values, correcting data types, and ensuring consistency with the dataset documentation.

- **Feature Engineering**  
  Creation of temporal, spatial, and event-based features to better capture the dynamics of lightning activity.

- **Modeling**  
  Development and evaluation of machine learning models to predict the **end of lightning alert sequences**.

- **Evaluation and Validation**  
  Assessing model performance and comparing predictions with existing operational rules.

---

## Dataset Description

The dataset contains **over 500,000 lightning events** recorded over multiple years around five airports. Each observation describes a lightning strike with information such as:

- timestamp of the lightning event
- geographic coordinates (longitude and latitude)
- lightning intensity and polarity
- localization error
- distance and direction relative to the airport
- lightning type (cloud-to-ground or intra-cloud)
- airport alert identifiers

Some variables are only available for lightning events occurring within **20 km of an airport**, which explains the presence of missing values in certain columns.

---

## Objective

The goal of this project is to develop predictive models capable of identifying **when a lightning event is about to end**, rather than relying solely on the traditional rule of waiting 30 minutes after the last detected lightning strike.

Such predictions could contribute to **improving airport operational efficiency while maintaining safety constraints**.

---

## Technologies Used

The project relies primarily on the following tools:

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## Status

🚧 Work in progress — the repository will progressively include the full pipeline from **data exploration to predictive modeling**.
