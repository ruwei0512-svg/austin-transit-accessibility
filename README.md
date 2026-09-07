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

## Data Sources

- CapMetro transit stop data
- CapMetro GTFS data
- U.S. Census Bureau Census Tract boundaries
- American Community Survey (ACS) household income data

## Output Visualizations

The main output maps and visualizations are included directly in this repository and can be viewed without running the notebook.

For the complete workflow, including data cleaning, spatial analysis, regression modeling, and visualization, see `Austin_Transit_Accessibility_Project.ipynb`.

## Run the Project

To run the analysis on your own computer:

1. Download `AustinTransitAccessibilityProjectData.zip`.
2. Extract the ZIP file to a local folder.
3. Download `Austin_Transit_Accessibility_Project.ipynb` and place it inside the extracted data folder.
4. Open Jupyter Notebook or JupyterLab from that folder.
5. Open `Austin_Transit_Accessibility_Project.ipynb` and run all cells.

The notebook uses the current working directory to locate the source data and automatically creates folders for analysis outputs during execution.

> Note: Part of the analysis uses ArcPy, so ArcGIS Pro and its Python environment are required to run the complete notebook.
