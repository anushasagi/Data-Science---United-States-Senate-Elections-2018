Group Information 


Name		NetID	  UIN
Fatima Kahack	fkahac2	  678151700
Lydia Tse	ltse5	  665801910
Anusha Sagi	ssagi2	  653773832
	
______________________________________


Table of each person’s contribution 

Tasks					Contributor	Status

1(Partition the merged dataset)   	Anusha Sagi     Completed
2Standardize the training/
validation set)				Anusha Sagi	Completed
3(Build linear regression models )	Anusha Sagi	Completed
4(Build classification models)		Anusha Sagi	Completed
5(Build clustering models)		Fatima Kahack	Completed
6(Create map of Democratic/Republican)	Lydia Tse	Completed
7Predict votes cast for each county) 	Anusha Sagi	Completed
Finalizing Code & Deliverable Prep	Lydia Tse	Completed


Instructions to Run Code 
1. After downloading the zip file, make sure that the following csv files are present
	- merged_train.csv
	- demographics_test.csv
	- output.xlsx
2. Open the python file in Jupyter Notebook or JupyterLab and run the code segments



Notes: 
Currently, there is known issue that matplotlib version 3.1.1 does not properly display the heatmap on macOS. If there is an issue doing so, please downgrade to matplotlib version 3.1.0 upgrade to matplotlib 3.1.2.
https://github.com/matplotlib/matplotlib/issues/14675


If there are issues running the code for task #06, check to see if pyshp, plotly, shapely, and geopandas packages are properly installed. Otherwise run the following commands using the command line interface of your choosing:


$ conda install -c anaconda pyshp
$ conda install -c anaconda plotly
$ conda install -c anaconda shapely
$ conda install -c anaconda geopandas