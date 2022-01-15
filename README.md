# Geospatial Analysis and Representation for Data Science
This repository stores the project developed for the course “Geospatial Analysis and Representation for Data Science” (University of Trento, 2021/2022).

## Task
The main purpose of this project is to study AirBnB in the province of Trento and how they distribute on the territory in relation to the main Points of Interest (PoI). The analysis has been developed following the steps below:
1.	Identify AirBnB and PoI in the Province of Trento
2.	Highlight the areas of greatest concentration of AirBnB and of PoI
3.	Evaluate which are the cheapest AirBnB structures and define the services and touristic attractions nearby 
4.	Draw a trajectory leading from the cheapest structure to the desired touristic attraction
5.	Consider position, price, time, and desired points to visit, and draw the optimal route
6.	Verify if there exist a relation between location and AirBnB price
All the analysis and the comments can be found in the Notebooks collected in this repository.
Steps from 1 to 5 are contained in the `InsideAirBnB.ipynb` notebook, while the last point can be found inside `SpatialStatisticalAnalysis.ipynb`.

## Data
For this project, the following data sources have been used:
-	[InsideAirBnB](http://insideairbnb.com/get-the-data.html), for the AirBnB data of Trentino 
-	[Open Data Trentino](https://dati.trentino.it/dataset/punti-di-interesse-del-trentino), for the data concerning the main points of interests in the Province 

## Main references 
-	[Course notes](https://napo.github.io/geospatial_course_unitn/)
-	[Osmnx examples](https://github.com/gboeing/osmnx-examples)
-	[Geographic Data Science with Python](https://geographicdata.science/book/intro.html)
-	[Travelling Salesperson Problem](https://mlrose.readthedocs.io/en/stable/source/tutorial2.html)
