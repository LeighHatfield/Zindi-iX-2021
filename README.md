# Zindi
Zindi Internship- Fire hotspots 
by Leigh Hatfield, Matthew Grant, and Anthony Tatarka

TASK:

We were tasked with forecasting the burn area from fires in the Democratic Republic of Congo (DRC) for the next five years, using data from Google Earth Engine (GEE).
This project is based on the Zindi UmojaHack #3: Hotspots Competition, which asked competitors to find a model to predict wildfires. For reference: https://zindi.africa/hackathons/umojahack-3-hotspots

Data Collection:

We had many issues getting the most recent data from GEE, but eventually found a way to get the most recent burn area.
This code can be found in the 'Data Collection GEE API' Jupyter Notebook.
(NOTE: This notebook uses the training data from Zindi UmojaHack #3: Hotspots Competition, which is not uploaded on this repository, 
but it can be found at: https://zindi.africa/hackathons/umojahack-3-hotspots/data )

Modeling/Forecasting:

We researched many forecasting models, but ended up using a SARIMA model due to the ease of use and the seasonality of the burn data. 
This code can be found in the 'Modeling (SARIMA Model) and Forecast' Jupyter notebook.

Forecasting App:

We created a dashboard to visualize the burn area in the DRC over the next 5 years. 
This code can be found in the 'Forecast Visualization' Jupyter Notebook.
