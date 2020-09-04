# Data Science - United-States-Senate-Elections-2018

Performed exploratory data analysis and created different regression, classification and clustering to predict the number of votes received for each party in each county and classified the counties based on the elected party.

## Dataset
This project uses the dataset that is the compilation of 2018 U.S. Census Demographic Data. 
This dataset provides ample numerical and categorical variables that can be utilized as predictors for our regression and classification models. 
Such predictors include race, gender, household income, unemployment rate, education and so forth. 
 

## Part 1 (Data Preparation & Hypothesis Testing)

### Dependencies:
If there are issues running the code for task #10, check to see if pyshp, plotly, shapely, and geopandas packages are properly installed. <br>
Otherwise run the following commands using the command line interface of your choosing:
```
$ conda install -c anaconda pyshp
$ conda install -c anaconda plotly
$ conda install -c anaconda shapely
$ conda install -c anaconda geopandas
```
### Instructions to Run Code: 

*  Download zip file 
*  Make sure the folder contains three csv files (demographics_train.csv, election_train.csv, and State_codes.csv).  
*  Open the python file in Jupyter Notebook or JupyterLab and run the code segments.


## Part 2 (Precditive Modeling - Machine Learning Algorithms)

### Dependencies
Currently, there is known issue that matplotlib version 3.1.1 does not properly display the heatmap on macOS. If there is an issue doing so, please downgrade to matplotlib version 3.1.0 upgrade to matplotlib 3.1.2.
https://github.com/matplotlib/matplotlib/issues/14675


If there are issues running the code for task #06, check to see if pyshp, plotly, shapely, and geopandas packages are properly installed. Otherwise run the following commands using the command line interface of your choosing:

```
$ conda install -c anaconda pyshp
$ conda install -c anaconda plotly
$ conda install -c anaconda shapely
$ conda install -c anaconda geopandas
```

### Instructions to Run Code 
* After downloading the zip file, make sure that the following csv files are present <br>
```
	- merged_train.csv 
	- demographics_test.csv
	- output.xlsx
```
* Open the python file in Jupyter Notebook or JupyterLab and run the code segments
