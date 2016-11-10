About the Federal Data
========

This folder contains:

* erp_2001-2015_ced2016.txt - federal electorate populations based on ASGS 2016, direct request from ABS, minor tweaks to five electorate names to help with merge
* areas.csv - federal electorate areas downloaded from http://www.aec.gov.au/profiles/Index.htm
* folder 1270055003_ced_2016_aust_shape - shapefile of federal electorates, downloaded from http://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.003July%202016?OpenDocument
* Federal - data cleaning.ipynb - Jupyter Notebook which runs through the process matching populations to areas and producing federal.csv
* federal.csv - csv file with code,name,population and area for each electorate

Notes:

* The population figures are projected figures for 2015
* All boundaries used are from ASGS 2016