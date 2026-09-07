# Austin Transit Accessibility Analysis

This project examines the relationship between public transit accessibility and median household income across census tracts in Travis County, Texas.

Using CapMetro transit data, GTFS service frequency, U.S. Census tract boundaries, and ACS household income data, the analysis measures transit accessibility based on nearby transit stops and service frequency. Spatial analysis and regression models are then used to explore how transit accessibility varies across neighborhoods with different income levels.

## Methods

- Cleaned and processed spatial and tabular datasets
- Calculated transit service frequency using GTFS data
- Created 800-meter buffers around transit stops
- Performed spatial joins between transit stops and census tracts
- Constructed a transit accessibility index
- Conducted OLS and quadratic regression analysis
- Created static and interactive maps for visualization

## Tools

Python, GeoPandas, ArcPy, Pandas, NumPy, Statsmodels, Matplotlib, Contextily, and Folium

## Data Sources

- CapMetro transit stop data
- CapMetro GTFS data
- U.S. Census Bureau Census Tract boundaries
- American Community Survey (ACS) household income data
