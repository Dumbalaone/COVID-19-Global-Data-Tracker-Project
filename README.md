# COVID-19-Global-Data-Tracker-Project

## Project Overview  
This project focuses on *analyzing and visualizing COVID-19 case trends* using data from *Our World in Data (OWID). The goal was to generate **insightful visualizations* that help interpret global case distribution.  

## Features  
- *Data Source:* OWID COVID-19 dataset (owid-covid-data.csv)  
- *Data Processing:*  
  - Filtered country-level data (iso_code)  
  - Aggregated total_cases to remove redundancy  
- *Visualizations:*  
  - *Choropleth Map* (Plotly Express) – Geographic case distribution  
  - *Line Charts* (Seaborn & Matplotlib) – Case trends over time  
  - *Heatmaps* (Seaborn) – Identifying peak infection periods  

## Technologies Used  
- *Python*  
- *Pandas* (for data processing)  
- *Plotly Express* (for choropleth mapping)  
- *Seaborn* (for trend visualization)  
- *Matplotlib* (for custom plots)  
- *Jupyter Notebook* (for execution)  

## Setup Instructions  
1. Install dependencies:  
   ```bash
   pip install pandas plotly seaborn matplotlib
