# Stellar-Flare-Detection-in-TESS-Mission-Data
This repository contains my work used for my project in STA2453. My project focuses on the detection of stellar flares in TESS misson data using a form of Density Based Clustering (i.e., DBSCAN) and Outlier Detection using Interquantile Range (IQR). I also implement time series analysis to remove noise and deterministic trends from the data. The dataset utilized in my paper, 0131799991.csv, capture various astrophysical properties concerning the star TIC 0131799991. 

The repository is structured as follows:
Code/: Contains Jupyter notebooks for data preprocessing (data_preprocessing.ipynb), clustering analysis using DBSCAN (dbscan.ipynb), and outlier detection via IQR (iqr.ipynb).
Data/: Includes raw and processed datasets, such as 0131799991.csv (original dataset), cleaned_tess_data.csv (processed TESS data), and detected_flares_tuned.csv (final detected flares).
EDA/: Contains an exploratory data analysis script, STA2453_EDA.Rmd, which provides initial insights into the dataset.

