# Comparing Surface PM2.5 Measurements with Satellite-Derived Estimates using GRASP

Introduction

This project uses the GRASP algorithm outputs to compare surface station measurements of PM2.5 with satellite-derived estimates from the PARASOL/POLDER instruments. The goal is to assess the accuracy and reliability of the satellite-based PM2.5 product by evaluating its performance against ground-based observations.

Data Sources

    Satellite Data: The satellite data used in this project is obtained from the GRASP official dataset given by Anton. This dataset contains the PARASOL/POLDER Level 1 (data could be additionally filtered) GRASP product, which provides estimates of PM2.5 concentrations derived from satellite observations. 
    Surface Data: The surface station measurements of PM2.5 are obtained from CETESB monitoring network. This dataset provides ground-based hourly observations of PM2.5 concentrations at various locations in Sao Paulo.
    
Methodology

    Satellite Data Preprocessing:
        The closest satellite grid point was identified for each surface station location to extract the corresponding PM2.5 estimates.
    Surface Data Preprocessing:
        The hourly surface data was aggregated to daily values by selecting the measurements closest to the satellite overpass time for each day (around 17UTC).
    Comparison Analysis:
        The daily satellite-derived PM2.5 estimates were compared with the corresponding daily surface station measurements. Additionally, scatter plots are presented here. 
