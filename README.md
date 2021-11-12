# MatPlotLib_Challenge - The Power of Plots

## Background

![Laboratory](Images/Laboratory.jpg)

# Objective

Generate tables and figures needed for a technical report of a study of 249 mice identified with squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance the drug Capomulin, versus the other treatment regimens. 

## Instructions

* Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.

* Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculate the final tumor volume of each mouse across four regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

* Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

* Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

* Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. 

# Observations

* Capomulin & Ramicane tested more mice than the other drug regimens and have the lowest average & median tumor volume. 
* Capomulin showed good results in reducing tumor volume - see chart on Mouse ID m601. 
* Weight is a negative factor related to Tumor Volume shrinking.


### Copyright
Trilogy Education Services © 2020. All Rights Reserved.


