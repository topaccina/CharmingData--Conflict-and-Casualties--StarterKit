# CharmingData--Conflict-and-Casualties--StarterKit
Highlight civilian casualties in violent conflicts  -Data Prep, EDA , test features - Starter Kit for Charming Data July project 2024.
Jupyter notebooks and input data to prepare the final dataset. Data from Uppsala Conflict Data Program. Focus on 2024 Jan-May data only.
1. notebooks/DataPrep.ipynb
   1. Data retrieval from the web ([https://ucdp.uu.se/downloads/](https://ucdp.uu.se/downloads/index.html#candidate))
   2. Data cleansing
   3. Enrich the dataset with extra-features helpful for the analysis/vizs design  
2. notebooks/EDA_vizs2.ipynb 
   1. prototype of Plotly maps vizs for the final Dash app. World view mapbox choropleth w/and w/o animation and mapbox scatter examples
3. notebooks/country_story.ipynb (COMING SOON)
   1. basic implementation of Retrieval Augmented Generation (RAG) usign Chroma db. Data about 2024 conflicts collected from the web and stored. A chat with memory implemented. Reference datasource here: [acled conflicts watchlist 2024](https://acleddata.com/conflict-watchlist-2024/)
   1. protoype of the final Dash app AI assisted feature.
4. data/data_2024.csv
   1.output from DataPrep.ipynb. Final dataset for the analysis.
5. data/world_country.json
   1. dataset with countries geometries and standard iso-code. Info helpful for map vizs. Original data source from Kaggle.
6. data/world-country_latitude_and_longitude.csv
   1. countries gps location to assign center GPS coordinates for each country  ---> [original data source from kaggle](https://www.kaggle.com/datasets/paultimothymooney/latitude-and-longitude-for-every-country-and-state). Info helpful for map vizs.
