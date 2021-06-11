# Matplotlib Homework - The Power of Plots

## Background

For this homework assignment I've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego where I was born. Pymaceuticals Inc. specializes in anti-cancer pharmaceuticals. In our most recent efforts, we began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, I've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

## Analysis

* Before beginning the analysis, we must check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.
* With our clean data we:

- * Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
- * Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of measurements taken for each treatment regimen throughout the course of the study.
- * Generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.
- * Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculated the quartiles and IQR and quantitatively determined if there are any potential outliers across all four treatment regimens.
- * Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlighted any potential outliers in the plot by changing their color and style.
- * Selected a mouse that was treateded with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.
- * Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
- * Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Lastly we plotted the linear regression model on top of the previous scatter plot.
