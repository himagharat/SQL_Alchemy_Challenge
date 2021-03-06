# SQL Challenge

![surfs-up.png](Images/surfs-up.png)

## Objective:
To use Python and SQLAlchemy to do basic climate analysis and data exploration of a climate database. 

### Precipitation Analysis

* Designed a query to retrieve the last 12 months of precipitation data.

* Loaded the query results into a Pandas DataFrame and set the index to the date column.

* Sorted the DataFrame values by `date`.

* Ploted the results using the DataFrame `plot` method.

  ![precipitation](Images/precipitation.png)

* Used Pandas to print the summary statistics for the precipitation data.

### Station Analysis

* Designed a query to calculate the total number of stations.

* Designed a query to find the most active stations.

* Designed a query to retrieve the last 12 months of temperature observation data (TOBS).

    ![station-histogram](Images/station-histogram.png)

### Climate App

After completing the initial analysis, the next step was to design a Flask API based on the queries just developed.

  * Convert the query results to a dictionary using `date` as the key and `prcp` as the value.

  * Return the JSON representation of your dictionary.

## Technologies:

* SQL Alchemy
* Jupyter Notebook
* Python
` 
