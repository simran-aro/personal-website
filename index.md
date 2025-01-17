## Quick Look at Projects

[Factors Affecting Bike Trip Generation in Philadelphia & Boston](https://simran-aro.github.io/MUSA-550-Trip-Generation-Comp/) | [Visualizing Philadelphia's Crash Data](https://simran-aro.github.io/visualizing-philly-district-crashes/) | [Exploring Origin-Destination Demographics for University City, Philadelphia](https://simran-aro.github.io/O-D-university-city-phl/)

## About Me

---

Master of City Planning candidate with three years of professional experience in urban design, planning and project management. Recent internship experience in demographic, economic & real estate analysis and geospatial data development. Interested in application of data science and urban technologies for building safer and liveable cities, and looking for opportunities in the transportation planning, economic development and urban analytics industries. 

As a planner, urbanist and former architect, I have always enjoyed using maps for storytelling. While studying city planning, I learnt tools like ArcGIS and programming languages that strenghtened my skillset and helped me form narratives to tell stories about people, places and systems. I am currently seeking full-time job opportunities- contact me at **arorasim@upenn.edu**, or connect with me on <a href="https://www.linkedin.com/in/simran-arora-88814015a/">LinkedIn</a> to chat!

### Education

**University of Pennsylvania**, Master of City Planning, _expected May 2023_

**Academy of Architecture**, University of Mumbai, Bachelor of Architecture, _2013-2018_

---

### Recent Work Experience

**U3 Advisors**, Graduate Intern, _May 2022 - Current_

**PolicyMap**, Data Development Intern, _May 2022 - August 2022_

**StudioPOD**, Architect, _May 2018 - July 2021_

---

### Skills

**Transportation Planning** R (STPLANR) , VISUM & VISSIM 

**Geospatial Data Analysis** ArcGIS , Python , R , SQL , JavaScript , ESRI Business Analyst & Field Maps

**Design Software** AutoCAD , SketchUp , Adobe Suite (InDesign, Photoshop, Illustrator) , Rhino , Lumion

**Urban Design** Street Design , Plaza + Public Parks , Waterfront Design , Design Programming

**Other**  Writing , Graphic Design 


Following is some of my geospatial data science work, covering topics from transportation to housing. Click on every title to check out their separate project pages.

![bandra]({{ site.url }}{{ site.baseurl }}/images/hillroadd.PNG)

---

### [Factors Affecting Bike Trip Generation in Philadelphia & Boston](https://simran-aro.github.io/MUSA-550-Trip-Generation-Comp/)

[GitHub Repo](https://github.com/MUSA-550-Fall-2022/final-project-bike-trip-generation-comparison)

Philadelphia and Boston are often ranked in the top 20 bike-friendly cities in the US. Both have bikeshare systems, called Indego and BlueBikes respectively. This project looks at bike share data from both these cities, to explore trip data, demographic data, and which factors affect trip generation in both cities. These are then compared between Philadelphia and Boston to see the similarities and differences. The factors that are of importance in both the cities can be studied further— and used in strategies for bike planning in other places.

This project is divided into three sections:
The first explores demographic data in a map format. These maps are compared to bike trips marked spatially to see the correlation between the two. The second explores weather data, and distances from various amenities. The article mentions the importance of bike shops, thus, I wanted to specifically add this as a varible. The third uses the random forest machine learning algorithm from Scikit-Learn to see which factors affect trip generation, and their importance. This is compared between the two cities.

**Skills used: Python (geopandas, hvplot, OSMnx, cenpy, datashader, carto2gpd, sklearn), GitHub Pages (html)**

#### Distances of bike stations from various amenities in Philadelphia and Boston

![dist]({{ site.url }}{{ site.baseurl }}/images/bike-distances-01.jpg)

#### Indego System Trips, 2020 and 2021

![phl-gif]({{ site.url }}{{ site.baseurl }}/images/bike_trips_month.gif)

---

### [Visualizing Philadelphia's Crash Data](https://simran-aro.github.io/visualizing-philly-district-crashes/)

[GitHub Repo](https://github.com/MUSA-550-Fall-2022/final-project-bike-trip-generation-comparison)

PennDOT collects and shares data on crashes for every year to increase education and awareness around safety. This data can be found [here](https://www.penndot.pa.gov/TravelInPA/Safety/pages/crash-facts-and-statistics.aspx). In this project, data from PennDOT was analyzed for three Philadelphia districts: North, Central and South. This project aims to create spatial components for this data to visualize where crashes are happening, and to create a crash index. This was done with the help of several packages developed for geospatial analysis in Python including OSMnx and folium, along with other packages like matplotlib, geopandas and altair to create charts.

![crash]({{ site.url }}{{ site.baseurl }}/images/crashdat.PNG)

To create the crash index, the number of crashes per street was divided by the lenght of the street. This number was log transformed and then normalized into an index. The lower the number the more dangerous the street is. The frequency of the index is visualized in the graphs below, for every district.

![crashind]({{ site.url }}{{ site.baseurl }}/images/crashind.PNG)

**Skills used: Python (geopandas, hvplot, OSMnx, altair, folium), GitHub Pages (html)**


---

### [Exploring Origin-Destination Demographics for University City, Philadelphia](https://simran-aro.github.io/O-D-university-city-phl/)

[GitHub Repo](https://github.com/simran-aro/O-D-university-city-phl)

[STPLANR](https://cran.r-project.org/web/packages/stplanr/vignettes/stplanr.html) is a package that can be used for travel behavior analysis using spatil data. An example of travel behavior is looking at **who** is travelling to where jobs are. This can answer several questions and help plan for public transit, demand and so on. This project looks at origin-destination data of Pennsylvania from 2017, and visualizes the demographics of travellers.

For this project the study area is University City, a neighborhood in West Philadelphia consisting of University of Pennsylvania (Penn), Drexel University as well as hospitals associated with Penn and housing, restaurants and other amenities. The unit of analysis was by census tract level. The census tracts used for this study are shown in the map below, and include the entire neighborhood of University City, with some extending beyond. Census Tract 42101980000 has a large boundary that includes Fairmount Park, but was used in this analysis since it captures the northeast part of University City. Additionally, a small number of households (if at all) are in Fairmount Park, thus too many outliers are not expected by including it.

![ct]({{ site.url }}{{ site.baseurl }}/images/ct.png)

![pa_od]({{ site.url }}{{ site.baseurl }}/images/pa_OD.png)

**Skills used: R (STPLANR, tidycensus, dplyr), GitHub Pages (html)**

