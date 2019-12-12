# Volvo Truck Analytics

### Team Members with Tasks: 
- [Ioannis Batsios](https://github.com/IBatsios)
    - External Temperature vs. Turbospeed Analysis.
    - Component Degradation from Temperature Analysis.
    - Component Degradation Regression.
    
- [Bill Downs](https://github.com/WilliamWallaceKildFiftyMen)
    - APU Analysis & Regression.
    - APU Component Correlation.
    - Main Ambassador with Volvo.
- [Wahab Ehsan](https://github.com/WahabEhsan)
    - Removal of Invalid Rows & Columns
    - Outlier Detection & Removal.
    - Displaying Data by Day.
    - Oil Temperature Analysis & Regression.
- [James Polk](https://github.com/methos237)
    - CPU Load Analysis & Regression.
    - Time Series Analysis.
    - Component Analysis & Weighted Averaging.
- [Christopher Thacker](https://github.com/Kozmocha)
    - Column Renaming.
    - GPS Speed vs. Wheel-Based Speed Analysis.
    - Truck 2 GPS Speed Value Predictions / Corrections.
    - Main Repository Manager.

## Volvo Data Description 
 
Our group has been given data on two different Volvo Vehicles (Trucks). These trucks have been equipped with many different sensors that log data on everything from transmission oil temperature to the time the driver spends on the accelerator for that given vehicle. One of the main areas that is in question surrounds a new power unit called the "APU". It does not depend on power from the motor, and general assumptions would say that would call for better efficiency and longevity of the truck's motor. Using time series manipulations on the data given should provide insight on whether these assumptions are true. These trucks are based in areas with variations in elevation, so the outcome should be interesting.  
 
 ## Goals
 
 - Analyze Volvo vehicle long haul and short haul data.
 - Use time series to aid in visualizations for analysis.
 - Determine if different metrics logged by sensors make a difference in relation to an "APU" module that is not dependent on power from the motor. 
 - Report any discovered anomalies detected by data manipulations.
 
 ## Requirements
 #### Pre-requisites:
 - [Python 3.7.5](https://www.python.org/downloads/release/python-375/)
 - A Python Package Manager (we recommend [pip](https://pip.pypa.io/en/stable/installing/))
 - [Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html) (Run ```pip install jupyter``` on CLI)
 #### Dependencies:
 - [Numpy](https://numpy.org/) ```pip install numpy```
 - [Pandas](https://pandas.pydata.org/) ```pip install pandas```
 - [Matplotlib](https://matplotlib.org/) ```pip install matplotlib```
 - [SciPy](https://scipy.org) ```pip install scipy```
 - [Scipy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html) ```pip install scipy.stats```
 - [Seaborn](https://seaborn.pydata.org/) ```pip install seaborn```
 - [StatsModels](https://www.statsmodels.org/0.9.0/install.html) ```pip install statsmodels```
 
 ## Objectives:
 
 The following are the main areas that Volvo is interested in our group looking into:

- Cleaning the data.
- Removing unused rows or columns.
- Comparing vehicles on multiple components to determine how effective the APU is.
- Identifying commonality in features with or without APU unit.
- Performing anomaly detection.
- Visualizing data trends and results.  

## Contributing
In order to maintain a healthy Master branch, please follow the [Git Guide](https://github.com/UNCG-CSE/Volvo_Truck_Analytics/wiki/Git-Guide).
