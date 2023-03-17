# LiDAR Uncertainty at NEON Sites
The purpose of this repository is to compare LiDAR canopy height data with insitu tree heights at the [SJER](https://www.neonscience.org/field-sites/sjer) and [SOAP](https://www.neonscience.org/field-sites/soap) NEON sites. The code downloads the lidar and in-situ datasets, calculates the mean and max tree height, and plots the lidar against the in-situ mean and max values to compare the relationship.


You can download the data from earthpy using: et.data.get_data('spatial-vector-lidar'

You can install the environment needed to run the code using the environment installation instructions on earthdatascience.org/: https://www.earthdatascience.org/workshops/setup-earth-analytics-python/setup-python-conda-earth-analytics-environment/
