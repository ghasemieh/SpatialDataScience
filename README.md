# SpatialDataScience

Spatial data science allows analysts to extract deeper insight from data using a comprehensive set of analytical methods and spatial algorithms, including machine learning and deep learning techniques [1]. This course explores the application of spatial data science to uncover hidden patterns and improve predictive modeling. You'll work with powerful analytical tools in QGIS, GeoDa software and learn how to integrate popular open data science packages in Python, R and Big Data Tools [1].

## Spatial Data and QGIS 
### Spatial Data
- Spatial phenomena can generally be thought of as either discrete objects with clear boundaries or as a continuous phenomenon that can be observed everywhere, but does not have natural boundaries [2]. 

- Discrete spatial objects may refer to a river, road, country, town, or a research site. Examples of continuous phenomena, or “spatial fields”, include elevation, temperature, and air quality [2].

- Spatial objects are usually represented by vector data.  For example, a vector data set may describe the borders of the countries of the world (geometry), and also store their names and the size of their population in 2015; or the geometry of the roads in an area, as well as their type and names. These additional variables are often referred to as “attributes”. 
- Continuous spatial data (fields) are usually represented with a raster data structure [2]. 

We would be more focussed on the vector type data. you can look at [GeoDa Software website](https://geodacenter.github.io/data-and-lab//).

### QGIS 

QGIS is a free and open-source cross-platform desktop geographic information system application that supports viewing, editing, and analysis of geospatial data. It supports the creation, editing, visualisation, analyses and publishing the  geospatial information on Windows, Mac, Linux, BSD [3]. 

The first step of the this course is to start working with QGIS and using the data from GeoDa[2]. This would is make you aware of spatial data elements and getting hands dirty in PyQGIS (scripting in QGIS). PyQGIS bindings depend on SIP and PyQt4. Python bindings for Qt (PyQt) are done also using SIP and this allows seamless integration of PyQGIS with PyQt. There are several ways how to use Python bindings in QGIS desktop, they are covered in detail in the following sections:

- Automatically run Python code when QGIS starts
- Issue commands in Python console within QGIS
- Create and use plugins in Python
- Create custom applications based on QGIS API



## Refernces
- [1] https://www.esri.com/training/catalog/5d76dcf7e9ccda09bef61294/spatial-data-science%3A-the-new-frontier-in-analytics/
- [2] https://www.rspatial.org/raster/spatial/2-spatialdata.html
- [3] https://qgis.org/en/site/forusers/download.html
