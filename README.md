# Ensemble Learning applied to Water Demand Time Series

The repository reports some applications of ensemble learning methods to water demand time series. 

The applications aims to show how ensemble learnig methods may be used to combine multiple machine learning techniques to improve the solution of regression and classification problems, with practical applications to a real case study, using high resolution water-flow measures. 

<a name="Applications"></a>
## Applications
The applications refers to:
* **BOOTSTRAPPING**
* **BAGGING**
* **RANDOM FOREST** *(regression and classification)*



<a name="Data"></a>
## Data

For the applications reported in this repository, IT has been used the dataset WEUSEDTO-Data vailable at this public repository: https://github.com/AnnaDiMauro/WEUSEDTO-Data 

The *water_usages* dataset used is a list of records provided as a CSV (Comma Separated Values). Each record characterizes the occurrence of a water usage and is described by the following parameters:
*	*start_date_time*: long [sec] it is the starting date-time of the usage as unix epoch
*	*duration*: int [ms], how long lasts the usage
*	*liters*: int [ml], how many liters of water have been consumed
*	*month*:int, month of occurrence
*	*hour*:int, hour of the day 
*	*day*: int, day of the week {0,…,6}
*	*max_flow*: int [ml/sec], maximum flow rate measured during the usage
*	*av_flow_rate*: float [ml/sec], the average flow rate calculates for the usage
*	*ec_from_midnight*: int, the number of seconds after the midnight
*	*fixture*: string, the lable that identifies the fixture (e.g. shower, washbasin, ...)
*	*num_fixture*: int, an integer that identifies the fixture (e.g. 0: shower, 1: washbasin, ...)
