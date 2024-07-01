# Comparing Surface PM2.5 Measurements with Satellite-Derived Estimates using GRASP

Introduction
This project aims to compare surface station measurements of PM2.5 with satellite-derived estimates from the PARASOL/POLDER instruments using the GRASP algorithm. The goal is to assess the accuracy and reliability of the satellite-based PM2.5 product by evaluating its performance against ground-based observations.

Data Sources
    Satellite Data: The satellite data used in this project is obtained from the ICARE Data and Services Center. This dataset contains the PARASOL/POLDER Level 2 GRASP product, which provides estimates of PM2.5 concentrations derived from the satellite observations. The tile used for Sao Paulo Brazil is 382.
    Surface Data: The surface station measurements of PM2.5 are obtained from the Fatima. This dataset provides ground-based observations of PM2.5 concentrations at various locations in Sao Paulo.

Methodology

    Satellite Data Preprocessing:
        For each surface station location, the closest satellite grid point was identified to extract the corresponding PM2.5 estimates.
    Surface Data Preprocessing:
        The hourly surface data was aggregated to daily values by selecting the measurements closest to the satellite overpass time for each day.
    Comparison Analysis:
        The daily satellite-derived PM2.5 estimates were compared with the corresponding daily surface station measurements.
