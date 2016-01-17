# Ill-Dept-of-Transp-Accidents
Data mining/modeling of Vehicular Accident Data in Chicago, specifically those that relate to Pedestrian and Pedacyclist.

# Thanks to Steven Vance https://github.com/stevevance for the data.

This takes a look at the characteristics and patterns that are present in the data for accidents that are either Pedestrian or Pedacyclists,
in the years 2012 thru 2014.

Much of the front end ETL and data munging is in Python. Flat files are loaded and Python's Geopy is used to create distances between accidents 
and relevant points. City of Chicago data is also used: includes the Traffic Estimate data (speed metric), and Liquor license data. : 'Python ETL' folder.

Some modeling is done in R, using supervised frequentist methods. TO DO. add some Bayesian inference.
