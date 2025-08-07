# AICTE-Group-2-Cycle2-2025-26---EV-Vehicle-Demand-Prediction

You can view the detailed project presentation by downloading the [PowerPoint file here](Week_3_Project_PPT_Template1.pptx).


# 🚗 EV Vehicle Demand Prediction

A project submitted as part of **AICTE Group 2 – Cycle 2 (2025–26)**.  
This project aims to **forecast electric vehicle (EV) adoption trends** using historical registration data and machine learning models, helping governments and industries make data-driven infrastructure decisions.

---

## 📊 Project Overview

Electric vehicle adoption is a rapidly evolving domain influenced by policy, environmental awareness, and market dynamics.  
This project focuses on:

- Analyzing historical EV registration data across counties
- Forecasting future EV demand using machine learning models
- Building a user-friendly app interface to visualize predictions

---

## 🧠 Key Features

- 📈 **Time Series Forecasting** of EV demand
- 🧹 **Data Preprocessing** pipeline for large-scale public datasets
- 🔍 **Exploratory Data Analysis (EDA)** and trend visualization
- 🧪 Trained & Serialized **ML model (`.pkl`)**
- 🌐 Lightweight **Flask app** for demo/deployment

---

## 📁 Project Structure

```bash
.
├── EVAdoptionForecasting.ipynb           # Jupyter notebook for data processing and modeling
├── app.py                                # Flask app to serve predictions
├── Electric_Vehicle_Population_By_County.csv  # Raw dataset
├── preprocessed_ev_data.csv              # Cleaned dataset used for modeling
├── forecasting_ev_model.pkl              # Trained model (Pickle file)
├── requirements.txt                      # Python dependencies
├── ev-car-factory.jpg                    # Visual asset used in the app/README
└── README.md                             # Project documentation 
```

## 🚀 Live Demo

Check out the live EV Demand Forecasting web app powered by Streamlit:

🔗 [Click here to view the live app](https://evdemandprediction.streamlit.app/)

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://evdemandprediction.streamlit.app/)

