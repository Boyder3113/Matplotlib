This repository contains two raw data cvs's and a jupyter notebook file. 

The jupyter notebooks file imports the csv with the intent of providing visual breakdowns of the effects of drug regimens on tumors in mice.

Using pandas and matplob lib we provide four breakdowns of the drug regimen data.
First, we create a bar chart showing the total number of mice per drug regimen, basically, how many mice are taking each drug regimen. Second, we provide a pie chart showing the gender breakdown of the mice by number and percentage. Third, we take four of the most promising drug regimens and create a box and whisker plot to identify any possible outliers for the regimens with the best results. Finally, we take one drug regimen, Capomulin and we look for coorelation between mouse weight and tumor size for one mouse on that regimen (Mouse ID: x401). After we get the coorelation we create a linear regression model between mouse weight and tumor volume for the Capomulin regimen using mouse x401. 
