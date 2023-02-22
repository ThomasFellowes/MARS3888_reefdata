# Welcome to MARS3888 

# Tutortials - Finding and Finding and Using Online Datasets

## First let's have alook at eReefs:

+ https://ereefs.org.au/ereefs

The eReefs research project is a collaboration between the Great Barrier Reef Foundation, CSIRO, the Australian Institute of Marine Science, Bureau of Meteorology, and Queensland Government. 

The project has developed a platform that provides a picture of what is currently happening on the reef, and what will likely happen in the future. eReefs combines modelling systems spanning the catchments, estuaries, reef lagoon and the open ocean portions of the Great Barrier Reef. 
The results of the models provide information on physical processes, sediment transport, biogeochemistry and ocean colour, and the delivery of those results supports enhanced monitoring, operational modelling, the development of new data standards and information system architectures, and cutting-edge reporting and data visualisation. 

## The two main models include:

+ eReefs Hydrodynamic Model (1 km - September 2010 onwards; 4 km December 2014 onwards)
+ eReefs BioGeoChemical Model (4 km resolution)

![image](https://user-images.githubusercontent.com/29109874/220499794-5bfd0029-26ca-4efa-b96f-5b0a8e554661.png)

Model grid and bathymetry for the 4km (left) and 1km (right) resolution model.
*This material is from the eReefs.org.au website and the eReefs Research from CSIRO*

## How to access eReefs data:

There are three ways to access eReefs data, each of which is intended for different types of users:
1.	Visualisation Portal 
2.	Data Brokering Layer (DBL) API 
3.	Direct from Source

For now, we will use the Visualisation Portal as it is the simplest method for most users (we will look at the Direct from Source method later). The portal provides access to any dataset which is connected to the eReefs Data Brokering Layer.

+ [https://portal.ereefs.info/](https://portal.ereefs.info/map)

## Visualisation Portal Method:

1.	Once you have read the information on previous page you can access the portal here and start exploring! 
2.	Start by adding a data layer to the map. Let’s click the “Browse Data” button at the top and select “eReefs Region Model Results” then “eReefs GBR1 hydrodynamic v2.0” and then find ‘Temperature (temp)’ and click “Show More”. This will give you information on the dataset at well as available web services to download the data directly. This will be important later. Now click “Add to Map”.
3.	Have a look at the Dataset tile (top right) and get familiar with the settings. 
4.	Now let’s add a location marker to the map (see Marker pin symbol on left) and place it at One Tree Island (-23.508, 152.091) or another reef of interest. Tip: you can adjust the Opacity of the Data Layer to 50% by pressing the cog symbol on the dataset tile and using the slider.
5.	Click on your One Tree Island Marker. A box will appear at the bottom of the screen. Click ‘Timeseries’ and adjust the date range from 1/12/2014 to now (or closest date). “Select 50 data points (faster)” and click “Build Plot”. NB: this should take less than 30 seconds. 
6.	Have a go at adding more Markers to the map from different locations along the GBR. For example, add one from the central reef and northern reef. The Timeseries plot will update and now have multiple lines. Make a note of the name of the location and co-ordinates of your Markers.
7.	You can also try adding more data points. Select “250 data points (slower)” and see what happens. Tip: run your mouse along the line to see the temperatures at each location. NB: this might take a few minutes. 
8.	On the right-hand side of the time series plot you will see a downward facing arrow. Click this and save the data as a .csv

Why might it be good to look at temperature for multiple locations? Are there higher peaks in the data at some locations? If so, when and what stressors or climate conditions might cause extreme conditions?

9.	Now have a go at adding different types of data to this map including shapefiles and remote sensing data and additional data from the GBR models (e.g., GBR1 and GBR 4 Hydrodynamics v2.0, GBR1 BioGeoChemistry and Sediments v3.2) in the Data Catalog window. Follow the steps above to produce timeseries and export the data as a .csv. NB: not all data is timeseries and remember to change back to “Select 50 data points (faster)” at first to view the data and then increase the temporal resolution before exporting the data.

What are the most important or more influential stressors to coral reefs?

## Direct Method:

We will be accessing the data using Binder in a Jupyter Notebook and NetCDF files. 

# Access this Binder by clicking the blue badge above or at the following URL:

![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ThomasFellowes/MARS3888_reefdata/main) 

https://mybinder.org/v2/gh/ThomasFellowes/ThomasFellowes-MARS3888_reefdata/mainClick on the icon [to open your virtual phython.

Work through the 4 Notebooks.
![image](https://user-images.githubusercontent.com/29109874/220500576-4a80dc5a-55bd-4a8e-99ef-400de4a6e640.png)
