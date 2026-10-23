# ✈️ Malaga Airport Analytics

**Flight Routes Analysis: September 2026**

A personal data analysis project exploring flight routes, origins, and destinations at **Málaga-Costa del Sol Airport (AGP / LEMG)** using real aviation data.

The goal is to discover the most frequent flight connections between Málaga and other airports while practicing data analysis with Python.

## Project Objectives

- Identify the most frequent flight destinations from Málaga.
- Discover which airports send the most flights to Málaga.
- Explore connections between Málaga and different countries.
- Analyze real flight data using Pandas.
- Visualize results with Matplotlib.

## Datasets

This project uses:

**Flight List — OpenSky Network**

Flight records from September 2026, including:

- Flight dates
- Departure and arrival airports
- Aircraft identifiers and models

**Airport Codes — OurAirports**

Airport reference data containing:

- Airport names
- ICAO airport codes
- Countries and locations

**Data sources:**
- [OpenSky Network](https://opensky-network.org/)
- [OurAirports](https://ourairports.com/data/)

## Technologies

- **Python** Data analysis
- **Pandas** Data exploration, filtering, grouping and merging
- **Matplotlib** Data visualization
- **Jupyter Notebook** Analysis and documentation
- **Parquet / CSV** Data storage

## Analysis

The Jupyter notebook includes:

1. **Data Loading** Importing the datasets.
2. **Dataset Overview**  Exploring columns, data types and dimensions.
3. **Data Quality**  Checking missing values and duplicates.
4. **Malaga Airport Flights**  Filtering departures and arrivals.
5. **Top 10 Destinations**  Most frequent destinations from Málaga.
6. **Top 10 Origins**  Most frequent origins of flights arriving in Málaga.

Additional analysis and visualizations may be added as the project develops.

## View the Analysis

Open [analysis.ipynb](analysis.ipynb) to explore the Python code, tables and visualizations directly on GitHub.

The notebook contains saved outputs, so visitors can review the analysis without running Python locally.

## Data Limitations

- The current analysis focuses on September 2026.
- Results represent flight records available in the source dataset, not necessarily all airport operations.
- Flight counts do not represent passenger numbers.
- Missing airport information may affect some results.

## Project Status

**In progress** This project is being developed as part of my learning journey in Artificial Intelligence and Big Data.

Future improvements may include additional months of flight data, country-level analysis and more visualizations.