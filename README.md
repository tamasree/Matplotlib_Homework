# Matplotlib - The Power of Plots

![Laboratory](Images/Laboratory.jpg)

## Following steps were followed for this study:

* Checking the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

* Using the cleaned data for the remaining steps.

* Generating a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generating a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

* Generating a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.


* Calculating the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

* Selecting a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

* Generating a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

* Calculating the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

