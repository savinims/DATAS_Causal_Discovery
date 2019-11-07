# Causal Discovery Tools for Time Series Applications - A Collection of Tutorials

* Tutorials written with a focus on atmospheric science applications as part of the Data Analysis Tools for Atmospheric Scientists (DATAS) Gateway. DATAS - https://datasgateway.colostate.edu/
* The methods explained in this repository are focused on observational studies where controlled experiments (e.g., targetted modelling studies in climate) are not performed to identify causes and effects. These methods allow you to identify 'potential' relationships that need to be further validated with our existing knowledge of a specific application domain. 
* Created by Savini M. Samarasinghe, Colorado State University, Fort Collins, CO.

 ### (1) Bivariate Granger causality test
 This is the most commonly used approach to find cause-effects in climate science to date.
 * Built using Python 3. Requirements: **numpy, pandas, matplotlib, scipy, statsmodels**.
 * Use nbviewer to preview notebook https://nbviewer.jupyter.org/github/savinims/DATAS_Causal_Discovery/blob/master/Bivariate_Granger_Causality/Granger_causality.ipynb
 

### (2) Time series extension of the PC stable algorithm
PC stable algorithm can be used to learn a probabilistic graphical model representation of data where the variables of interest are presented as nodes of a graph and the stochastic relationships between the variables are presented as graph edges.

About the files and requirements:
  * `PC_stable_for_time_series.ipynb` is the main tutorial. This notebook provides a simple example of how the PC stable algorithm can be used to find potential cause-effect relationships between a set of time series variables. 
  * `Seasonal_data_extraction.ipynb` gives an example of how to extract seasonal data. This notebook uses data from `sample_data.mat` 
  * Built using Python 3. Requirements: **numpy, pandas, matplotlib, scipy, graphviz**.
  * Graphviz installation instructions: https://pypi.org/project/graphviz/
  * Use nbviewer to preview notebooks https://nbviewer.jupyter.org/github/savinims/DATAS_Causal_Discovery/tree/master/PC_Stable/
  

