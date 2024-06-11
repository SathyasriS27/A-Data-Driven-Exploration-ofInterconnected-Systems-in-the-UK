# Transport Data Science 🛣️

## Transportation Networks, Population Distribution and Air Quality: A Data Driven Exploration ofInterconnected Systems in the UK  🚂

### Introduction 🇬🇧
The United Kingdom has a diverse and dynamic population distribution and intricate transportation networks for bothrailways and roadways. This report aims to comprehend the many transport networks, identify thebusiest hubs, ascertain the population density in these locations, and establish a connection between them and the airquality in that region.

This analysis is structured as follows: we first look into an overview of the different transportation networks, populationdistribution and air quality. Following this different data exploratory analysis is done to understand the data better andcome up with findings to conclude the analysis.

### Datasets and Shapefiles used 🗺️
Different Data files that are used in this analysis are:
- Stations - This .csv dataset was got from Github. It contains information on the different stations present in the UK and their locations. 
- pass_data — This .xlsx dataset, obtained from the Office of Rail and Road Transport in the UK, contains information on the number of journeys made by passengers in the UK by train. 
- passenger_count- This .xlsx dataset, obtained from the Office of Rail and Road Transport, contains information on the total number of entries and exits for all stations in the UK.
- UK_popden - This .xls dataset, obtained from the Office of National Statistics, contains information on the population count in each location across the UK. 
- UK_Air_2022 - holds information on air pollution in the UK in 2022, obtained from the open-air dataset.
- UK_roads_data—A .csv dataset obtained from the Department of Transport UK database contains information on the number of vehicle movements per road in the UK. 
- poll_air_gg  - This .xlsx dataset was obtained from the Department of Transport UK database, which contains information on the different greenhouse gases present in the atmosphere. 
The based_trans — This .xlsx dataset was obtained from the Department of Transport UK database, which contains information on the greenhouse gases emitted by different transportation systems in the UK. 
- UK_poll_LAD — This .csv dataset was from the Department of Transport UK database, which contains information on the greenhouse gas emissions by each Local authority district in the UK.

Different shape files that are used in this analysis are:
- UK - The shapefile from IGISMap contains the UK's boundaries or main outline. 
- UK_railroads - shapefile from OSDataHub contains information on the rail route for the entire UK. 
- London_roads - shapefile from London Datastore contains the London road map of all the major and minor roads. 
- London_tube - shapefile got from Cornell Bower University's Database, contains London's subways rail route.
- UK_lad - shapefile from ONS contains boundary data of the local authority districts in the UK. 
- UK_major_roads - shapefile got OS OpenRoads, containing a route map containing all the major roads in the UK.

### Methodology followed 🗂️
1. Importing the required Datasets and Shapefiles
2. Data Cleaning and Data Transformations
3. Exploratory Data Analysis and Discussions
   * Understanding the number of Train journeys over the years in the UK
   * Understanding the population density and the Tickets sold in that place
   * Network Analysis on the Train ticket data to understand the busiest hubs in the UK
   * Understanding the different air pollutants in the air and the roadways across the UK
   * Understanding the amount of greenhouse gases produced and how different transports have contributed
   * Greenhouse Gas Emission based on LAD comparison with the population density and the road traffic

### Built Using 🛠️
* R

### Packages used are 📦
* ggplot2
* maps
* osmdata
* sf
* tidyverse
* ggmap
* giscoR
* dbplyr
* sp
* openair

### Documentation 📚
In order to get the complete analysis and conclusion, please refer to this documentation.
