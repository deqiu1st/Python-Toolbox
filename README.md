# Python-Toolbox
### NRS568 Python for ArcGIS - Final Project - Spring 2019
#### By Deky Rahma Sukarno
This Python toolbox was created as a final project for NRS568 - Python for GIS. This toolbox was prepared by Deky Rahma Sukarno, and is an application of learning obtained from this course under the guidance of Andrew J. Davis from  the University of Rhode Island. All tools are released under the MIT License.

Please download PythonToolbox-Deky.zip in this repository, and extract this zip file in the folder of your choice. This zip file contains the python toolbox (Python Deky.pyt Toolbox) and sample data for each tool.

![Banner Image](/image/Picture1.png?raw=true)

Please add "Python Deky.pyt Toolbox" to the ArcGIS toolbox to use it.

![Banner Image](/image/Picture2.png?raw=true)

This Python toolbox contains three tools:

#### 1. Flooded Structure Analysis
This tool will analyze buildings/structures that are flooded based on flood area data.
- The input data needed are: 1) Distribution of buildings/structures (point, *.shp); 2) Flood area (polygon, *.shp); and delineation of area/town (polygon, *.shp).
- The output are: 1) the distribution of flooded buildings/structures based on its type; 2) Heatmap is the number of buildings/structures flooded per square kilometer; and 3) summary of the number of flooded buildings/structres in the form of excel tables, located in output folder.

<img src="https://github.com/deqiu1st/Python-Toolbox/blob/master/image/Picture3.png" width="500">

#### 2. Fetch Analysis
This tool will analyze the fetch that is formed from a location by considering the condition/shape of the coastline.
- The input data needed are: 1) point location (point, *.shp); and 2) polygon of waters with coastlines (polygon, *.shp).
- The output are: 1) fetch line; and 2) fetch summary with length information and standard deviation in the form of excel tables, located in output folder.

<img src="https://github.com/deqiu1st/Python-Toolbox/blob/master/image/Picture4.png" width="500">

#### 3. Heatmap Analysis
This tool will analyze the distribution of biota location by species in the form of heatmap.
- The input data needed is a table of biota locations in the form of *.csv.
- The output is heatmap per species (polygon, *.shp), located in output folder.

<img src="https://github.com/deqiu1st/Python-Toolbox/blob/master/image/Picture5.png" width="500">


***Please see the example input file for detailed format and the required array of attributes before you use it for other input files.***
