# lc_county_water_district

A project with the county water district to consolidate, develop functions to clean reports, visualize with ArcGIS, and analyze various sources of water data.
Analysis of the surface water levels leveraged existing data (publicly available through Montana Bureau of Mines and Geology) to inform future decision making of the office.  The research includes the average percent difference of water levels per well, per time period, per season and its visualization with ArcGIS.  A  word document of the exact methods is included in lc_county_water_district folder.  Much of the files include the manipulation of time-series and spatial data. 

The following is a description of each file:

research folder - Includes the water data used, research methods (READ ME File), and the sampling and analysis .ipynb files with notes.

research_ArcGIS_visualization - Visualization of the resulting distrubutions for each season and a map of the surface water levels in the county 

data_flow.pdf/er_diagram.pdf - visualization of the er diagram for final database and dataflow 

dlcleaning_function.ipynb- Creating cleaning fuction to clean and analyze raw data from a device used to measure stream flow in the county 

dldischarge_merge_clean.ipynb - Creating and merging data to compare to manually collected data.

ind_merge_master/(2)/(3)- merging individual reports from various sources (independent labs and programs)

wq_merging.ipynb/ wq_merging2.ipynb - Creating cleaning function to merge and create a master dataframe for future reports to be added to a geodatabase in ArcGIS

stream_report.ipynb - annual reports of the average cfs per day for  2 local usgs gauges using NWIS API

surface_ground_merge.ipynb - combing and cleaning two dataframes
