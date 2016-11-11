About the Local Data
========

This folder contains:

* Councils data cleaning.ipynb - Jupyter Notebook producing the local.csv
* ABS_ERP_LGA2015_08112016155122158.csv - national LGA population data provided by ABS for 2015
* tascouncillors.csv - a list of councillers in Tasmania provided by the local government association there
* qldpop.csv - load counts of councillors per LGA manually collected from http://results.ecq.qld.gov.au/elections/local/LG2016/groupIndex.html
* wacouncillors.csv - WA data scraped from http://walga.asn.au/About-Local-Government/LG-Directory.aspx by WA Council Scraper.ipynb
* WA Council Scraper.ipynb - WA council scraper
* sacounts.csv - counts of councillors by LGA in SA provided by local government association
* nswreg.csv - counts of NSW councillors, scraped from the local government directory: https://www.olg.nsw.gov.au/local-government-directory
* NSW Councils scraper.ipynb - scraper for NSW councillors
* nswcsvfromgeojson.csv - csv extracted from the geojson (using Qgis) on the strongercouncils.nsw.gov.au website which notes which councils are being merged
* viccounts.csv - counts of councillors provided by Victorian local government association
* folder 1270055003_lga_2015_aust_shape - shapefile of LGA 2015 boundaries downloaded from http://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.003July%202015?OpenDocument
* lgageo.csv - csv extracted from boundaries, including the area of each LGA
* local.csv - csv with local government data

Notes:

* This data EXCLUDES any councils subject to mergers in NSW - confirmed, pending, or in process
* Lots of notes in the Jupyter Notebook
* For councils in short-term administration (like Geelong), the number of councillors prior to the adminstration has been used