# Stellar Flare Detection in TESS Mission Data
This repository contains my work used for my project in STA2453. My project focuses on the detection of stellar flares in TESS misson data using a form of Density Based Clustering (i.e., DBSCAN) and Outlier Detection using Interquantile Range (IQR). I also implement time series analysis to remove noise and deterministic trends from the data. The dataset utilized in my paper is `0131799991.csv`, capture various astrophysical properties concerning the star TIC 0131799991. 

### Repository Structure

- **`Code/`**: Contains Jupyter notebooks for:
  - Data preprocessing: `data_preprocessing.ipynb`
  - Clustering analysis using DBSCAN: `dbscan.ipynb`
  - Outlier detection via IQR: `iqr.ipynb`

- **`Data/`**: Includes raw and processed datasets:
  - `0131799991.csv`: Original dataset
  - `cleaned_tess_data.csv`: Processed TESS data
  - `detected_flares_tuned.csv`: Final detected flares

- **`EDA/`**: Contains an exploratory data analysis script:
  - `STA2453_EDA.Rmd`: Provides initial insights into the dataset


