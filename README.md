# Exploration of San Francisco Crime Dataset with Spark

### Data
[sf_data.csv](https://data.sfgov.org/Public-Safety/sf-data/skgt-fej3/data): 8964 reported incidents during the time between 07/11/2017 and 07/31/2017 from the SF Police Department

### Required Frameworks/Libraries
- ``Spark`` environment 
- ``pyspark``
- ``matplotlib``
-  ``seaborn``

### Methods and Results
We load the csv file to a Spark RDD object and then convert it to a data frame. We perform data exploration and visualization in four parts:     
- count the number of incidents for each category
- count the number of incidents at each district
- count the number of incidents each Sunday at SF downtown
- visualize the spatial distribution of incidents and run a ``KMeans`` clustering algorithm

All the codes and explanations are shown in [crime.ipynb](crime.ipynb).