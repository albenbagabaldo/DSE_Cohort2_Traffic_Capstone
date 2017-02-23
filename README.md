DSE Cohort 2 - Traffic Capstone Project
====

Traffic modeling and prediction is a field that has been researched and studied for many years. With the 
introduction of large data sets taken from sensor stations throughout California, and a myriad of other data sources 
available contributing to traffic metrics collection, opportunities for analysis into traffic modeling and the factors 
causing traffic are ever expanding. 
 
In this Capstone overview, we describe how traffic volume can be modeled utilizing Principal Component Analysis 
(PCA), additionally how easily and effectively it can be visualized to assist in the detection of traffic patterns and 
volume for further analysis. In addition, our work experiments with identifying different traffic behaviors exhibited 
throughout the week utilizing the KMeans++ clustering algorithm. A cursory examination into determining the 
factors that contribute to traffic volume is explored using Elastic Net Regression. The purpose of this work is to 
inform business decision makers and the general public of traffic patterns that exist in California, with the hope 
being that additional insight can guide solutions to address high traffic volume. 

Group Members
* Miki Hardisty
* Josh Duclos
* CJ Stevens
* Chris Sanders
* Abe Hart

Advisor:
* Yoav Freund

Reports
---------
| Location      | Description   
| ------------- | -------------  
| cohort2/documents/final_report.pdf | Final Report
| cohort2/documents/final_report.? | Final Presentation      

Buckets
---------
| Location      | Description   
| ------------- | -------------  
| s3://dse-team2-2014/dse_traffic | Directory containing original downloaded traffic files for 2008 to 2015
| s3://dse-team2-2014/pivot_output_#{year} | Directory containing Pivot Output Files from parsing downloaded traffic files      
| s3://dse-team2-2014/regression | Directory containing files used for Elastic Net Regression      
| s3://dse-team1-2015/dse_traffic | Directory containing original downloaded traffic files for 2016

Source Code
------------
| Location      | Description   
| ------------- | -------------  
| cohort1/ml/scala/traffic | Maven Project for Machine Learning, Pivoting Scala Code
| cohort1/traffic/vis/stations | Traffic GIS Map Visualization - HTML/Javascript Source Code      
| cohort1/final/eigenvector_analysis.py | Eigenvector Analysis Visualiation - Bokeh Python Source Code
| cohort1/traffic/src/scraper.py | Web Scraper Python Source Code
| cohort1/traffic/jsg_test | Directory Containing CloverETL graphs, transformers for Postgres DB ETL
| cohort1/traffic/traffic_etl_spark.py | PySpark Job to extract traffic data from S3 into Postrgres DB

Directory Structure: See Wiki for more information:
---------------------------------------------------
| Path | Description
| cohort1/ | Cohort 1's Efforts
| cohort2/exploration/ | collection of exploratory notebooks, visualizations, etc. first word_ in name signifies effort area
| cohort2/data/ | directory to hold smaller datasets
| cohort2/documents/ | directory to hold documents
| cohort2/trafficpassion/ | directory for python code related to final presentations, papers, and other files not related to exploration. Things considered final project
| cohort2/config | directory for virtualenv configurations, anaconda environments, etc
