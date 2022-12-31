# lc_county_water_district

A project with Lewis and Clark county to consolidate, develop functions to clean reports, visualize with ArcGIS, and analyze various sources of water data.
Analysis of the surface water levels leveraged existing data to inform future decision making of the office.  The research includes the average
percent difference of water levels per well, per time period, per season and its visualization with ArcGIS.  A  word document of the exact methods is included in 
lc_county_water_district folder.  Much of the files include the manipulation of time-series and spatial data. 

The following is a description of each file:

research folder - Includes the water data used, research methods, and the .ipynb files with notes.

research_ArcGIS_visualization - Visualization of the resulting distrubution and a map of the surface water levels in the county 

dlcleaning_function.ipynb- Creating cleaning fuction to clean and analyze raw data from a device used to measure stream flow in the county 

dldischarge_merge_clean.ipynb - Creating and merging data to compare to manually collected data.

wq_merging.ipynb - Creating cleaning function to merge and create a master dataframe for future reports to be added to a geodatabase in ArcGIS
