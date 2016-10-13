# aemet-hourly-data
Tool to get hourly meteo data from the Spanish National Meteorology Agency weather stations.
This is a rewrite in Python to of my original shell script to get the hourly data from the spanish AEMET automatic weather stations. 

Herramienta para obtener los datos de las estaciones metereologicas automáticas de la AEMET
Reescritura en Python de mi herramienta original en shell script

## Files:

* station.id: List of all AEMET stations in format [province];[station_id];[station_location] as of commit date

## Usage

./aemet-get.py {number of most recent values to be retrieved}

### TO-DO

Implement a way to get data only from one or a subset of stations. 

#### TO-DO one day: 

Implement external configuration file

