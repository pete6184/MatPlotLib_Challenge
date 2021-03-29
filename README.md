# Matplotlib Homework - The Power of Plots

## Requirements & Summary
This challenge requires Jupyter Notebook and running the cells in order from the top down to run properly.

This assignment taught me to expand on the python code we have been writing and the dataframes we have been creating. The new element to this challenge was to create visual charts to present the results I created through my dataframes. As you can see in the notebook, I created bar, pie, scatter, box & whisker, and line plot graphs.

I enjoyed this assignment and the different elements of creating and cleaning the data and then plotting the information. This seems especially useful for presenting findings to end users. The analysis also gave me a good exercise on reading the information to extract useful takeaways.


## Background
We were given access to the complete data from our company's most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. We were tasked by the executive team to generate all the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

#### We were tasked with the following:

Before beginning the analysis, we checked the data for any mouse ID with duplicate time points and removed any data associated with that mouse ID. After cleaning the dataset, we performed the following analysis:

- Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
- Generated a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.
- Generated a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
- Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
- Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
- Generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlighted any potential outliers in the plot by changing their color and style.
- Selected (at random) a mouse that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.
- Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
- Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.
- Plotted the linear regression model on top of the previous scatter plot.

### Observations & Analysis

#### Observation 1

When we generated the scatter plots to correlate the data for Average Tumor Volume vs. Mouse weight (when treated with Capomulin), I noticed that there was a strong correlation between the two data points. This observation leads to the conclusion that the Total Volume of the tumor is related to the weight of the mouse and the volume of the tumor increases as the mouse's weight does.

#### Observation 2

Capomulin and Ramicane appear to have the highest success rates in reducing tumor sizes. In some samples I pulled, there was a consistent decrease in tumor volume over time. In addition, these two drugs had significantly lower average and median tumor sizes than the other drugs used in the trial. Both drugs had an average tumor volume around 40mm whereas the other 8 drugs had average volumes around 52-55mm.

#### Observation 3

The gender of the mouse did not seem to play any role in the data's outcome. I ran a quick scatter plot (not included) of average tumor volume and gender of the mice and there was no correlative data provided that would tell us that the tumor size was larger in one of the genders.
