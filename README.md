#AGOL Template: DCFinder
Customization of Esri Finder template available at https://github.com/Esri/local-government-online-apps 

##Requires:
* An appid or mapid
* configuration on ArcGIS Online

##Features:
* Mobile responsive
* DC Branded to match opendata.dc.gov
* Autosuggest
* Load with search parameter

##Here are some tests of the template as deployed, using the real property map.

###Base Url – displays map and tools:
* Using Redirect: http://geospatial.dcgis.dc.gov/realestate/
* As-is: http://geospatial.dcgis.dc.gov/testing/agol/finder/s2.html?app=apps2/DCFinder&webmap=dac0435251824da8abc96a18bfd1f2ca&

###SSL Search:
* Using Redirect: http://geospatial.dcgis.dc.gov/realestate/search/property/0939%200049
* As-is: http://julietest.dc.gov/dcfinder/s2.html?app=apps2/DCFinder&webmap=dac0435251824da8abc96a18bfd1f2ca&searchtype=property&searchvalue=0939%200049

###CONDO SSL Search:
* Using Redirect: http://geospatial.dcgis.dc.gov/realestate/search/property/1805%202390
* As-is: http://geospatial.dcgis.dc.gov/testing/agol/finder/s2.html?app=apps2/DCFinder&webmap=dac0435251824da8abc96a18bfd1f2ca&searchtype=property&searchvalue=1805%202390

###Long/lat coordinate search:
* Using Redirect: http://geospatial.dcgis.dc.gov/realestate/search/coordinates/-77.017829,38.896437
* As-is: http://geospatial.dcgis.dc.gov/testing/agol/finder/s2.html?app=apps2/DCFinder&webmap=dac0435251824da8abc96a18bfd1f2ca&searchtype=coordinates&searchvalue=-77.017829,38.896437
