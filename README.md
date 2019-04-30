# Python-Toolbox
### NRS568 Python for ArcGIS - Final Project
#### By. Deky Rahma Sukarno
This Python toolbox was created as a final project for the 2019 Python for GIS Spring class the University of Rhode Island. This toolbox was prepared by Deky Rahma Sukarno from the University of Rhode Island, and is an application of learning obtained from this course under the guidance of Professor Andrew Davis.

Please download PythonToolbox-Deky.zip in this repository, and extract this zip file in the folder of your choice. This zip file contains the python toolbox (Python Deky.pyt Toolbox) and sample data for each tool.

![Banner Image](/image/Picture1.png?raw=true)

Please add "Python Deky.pyt Toolbox" to the ArcGIS toolbox to use it.

![Banner Image](/image/Picture2.png?raw=true)

This Python toolbox contains three tools:

##### 1. Flooded Structure Analysis
This tool will analyze buildings that are flooded for each type of building based on flood area data.
For this analysis the data needed are: 1) Distribution of structures (point, * .shp); 2) Flood area (polygon, * .shp); and delineation of area (polygon, * .shp).
The output of the analysis is: 1) the distribution of buildings is flooded based on its type; 2) Heatmap is the number of buildings flooded per square kilometer; and 3) summary of the number of flooded buildings in the form of excel tables.

![Banner Image](/image/Picture3.png?raw=true)

##### 2. Fetch Analysis
This tool will analyze the fetch that is formed from a location by considering the condition of the coastline in a waters.
For this analysis the data needed is: 1) point location (point, * .shp); and polygons of waters with coastlines (polygon, * .shp).
The output of the analysis is: 1) fetch line; and 2) fetch summary with length information and standard deviation in the form of excel tables.

![Banner Image](/image/Picture4.png?raw=true)

##### 3. Heatmap Analysis
This tool will analyze the distribution of biota location by species in the form of heatmap.
For this analysis the data needed is a distribution table of biota locations in the form of * .csv.
The output of this analysis is heatmap per species (polygon, * shp)

![Banner Image](/image/Picture5.png?raw=true)

Please see the example input file for detailed format and the required array of attributes before you use it to input other files.
