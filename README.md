# AI-Driven Smart Grid Net Demand Forecasting

## Overview

This project implements an **AI-driven smart grid forecasting system** using Machine Learning and Deep Learning models.
The system predicts **electricity net demand** by integrating renewable energy generation and performing forecasting with advanced algorithms.

Net demand is calculated as:

Net Demand = Load − Solar Generation − Wind Generation

The project demonstrates how AI can support **modern smart grids** in improving demand forecasting, renewable integration, and energy management.

---

## Features

* Data preprocessing and feature engineering
* Renewable energy integration (Solar + Wind)
* Machine learning forecasting using **Random Forest**
* Deep learning forecasting using **LSTM networks**
* 24-hour future electricity demand prediction
* Smart grid economic dispatch optimization
* Visualization of electricity load and renewable generation
* Automatic saving of model prediction results

---

## Technologies Used

* MATLAB
* Machine Learning Toolbox
* Deep Learning Toolbox
* Optimization Toolbox

---

## Project Structure

```
AI-SmartGrid-Forecasting
│
├── main.m
├── README.md
├── data
│   └── (dataset should be placed here)
└── results
    ├── random_forest_prediction.csv
    └── lstm_prediction.csv
```

---

## Dataset

The dataset used in this project contains **hourly electricity demand and renewable generation data**.

Due to GitHub file size limits, the dataset is not included in this repository.

Download the dataset from:

https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption

After downloading, place the dataset file in:

```
data/time_series_60min_singleindex.csv
```

---

## How to Run

1. Open the project in **MATLAB**.
2. Place the dataset inside the **data/** folder.
3. Run the main script:

```
main
```

---

## Output

The system generates:

* Net demand forecasting graphs
* Deep learning prediction results
* 24-hour future demand forecast
* Renewable energy visualization
* Optimization results
* Prediction files stored in the **results/** folder

---

## Example Visualizations

The project produces several visual outputs including:

* Random Forest net demand forecast
* LSTM deep learning forecast
* Renewable generation plots (Solar & Wind)
* Future electricity demand prediction

---

## Author

**S.E. Tamil Selvan**
Electrical Engineer | Smart Grid & Power Systems | AI for Energy Systems

---

## License

This project is released under the **MIT License**.
