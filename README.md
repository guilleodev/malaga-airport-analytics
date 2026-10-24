<p align="center">
  <img src="images/malaga_airport_image.jpg" alt="Málaga Airport" width="40%">
</p>

<h1 align="center">✈️ Malaga Airport Analytics</h1>

<p align="center">
  <strong>Exploring real-world aviation data with Python and Pandas</strong>
</p>

<p align="center">
  Flight Routes | Airport Traffic | Seasonal Trends
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Matplotlib-11557C" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white" alt="Jupyter">
</p>


A personal **Exploratory Data Analysis (EDA)** project investigating flight activity, routes, origins, and destinations at **Málaga-Costa del Sol Airport (AGP / LEMG)** using real-world aviation data.

## 📊 Project at a Glance

| 🌍 Global Flight Data | ✈️ Málaga Records | 📅 Period |
|:---:|:---:|:---:|
| **~13.5M estimated** | **146,638** | **9 months** |
| Worldwide flights | Málaga-related records | Jan–Sep 2026 |

The project processes large-scale aviation datasets stored in **Parquet format**, filtering worldwide flight records to analyze airport activity in Málaga.

## 🗂️ Data Sources

- **[OpenSky Network](https://opensky-network.org/)** - Worldwide flight records stored in monthly Parquet files, containing millions of observations.
- **[OurAirports](https://ourairports.com/data/)** - Airport names, ICAO codes, countries, and geographical information.

## 📓 Analysis Notebooks

| Notebook | Analysis |
|---|---|
| 📗 [January–September 2026](notebooks/analysis_2026.ipynb) | Extended analysis, monthly trends, route evolution and visualizations |
| 📘 [September 2026](notebooks/analysis_sep2026.ipynb) | Data exploration, flight routes, top destinations and origins |

## 📈 Data Visualization

<p align="center">
  <img src="images/flights_cities.png" alt="Monthly Flight Activity" width="40%">
</p>

<p align="center">
  <em>Top 10 Origin Cities for Flights to Málaga</em>
</p>
<br>
<p align="center">
  <img src="images/daily_flight.png" alt="Monthly Flight Activity" width="40%">
</p>

<p align="center">
  <em>Daily Arrivals and Departures at Málaga Airport</em>
</p>

<p align="center">
  <em>and more...</em>
</p>

## 🔍 Key Findings

- **146,638** Málaga-related flight records analyzed.
- **July:** Highest recorded activity with **22,065 flights**.
- **January:** Lowest recorded activity with **5,803 flights**.
- Recorded flight activity generally increased toward the summer months.

> **Note:** Results reflect available OpenSky records and may not represent all airport operations. Global record volume is estimated, not yet verified.

## 📌 About This Project

Personal project developed while studying **Artificial Intelligence & Big Data**, focusing on Python, Pandas, data processing, and visualization.

<br>
<div align="center">
  <i>Made by</i>
  <br>
  <a href="https://github.com/guilleodev">
    <img src="https://raw.githubusercontent.com/guilleodev/guilleodev/main/guilleODEVWhite-transparent.png" alt="guilleODEV" width="125">
  </a>
</div>