# matplotlib_challenge

# Pymaceuticals Analysis

## Background

Analyzed data from an animal study by Pymaceuticals, Inc. to compare the effectiveness of various drug regimens, including Capomulin, for treating squamous cell carcinoma (SCC) in mice. The study involved 249 mice over 45 days.

The current analysis looks into the relationship between mouse weight and average tumour volumn for the drugs, especially Capomulin regimen. The several plots including the linear regression finds a positive correlation between weight and tumour volumn under the campulin drug. They also exhibit that heavier mice tend to have larger tumor volumes.

## Setup

1.  Created a repository called `pymaceuticals-analysis`.
2.  Cloned the repository and added data files and analysis script.
3.  Pushed changes to GitHub/GitLab.

## Instructions

### Data Preparation

-   Merged `mouse_metadata` and `study_results` DataFrames.
-   Removed duplicate mouse IDs.

### Summary Statistics

-   Calculated mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen.

### Bar and Pie Charts

-   Created bar charts showing total data points for each drug regimen using Pandas and Matplotlib.
-   Created pie charts showing gender distribution using Pandas and Matplotlib.

### Quartiles, Outliers, and Box Plot

-   Calculated final tumor volume for Capomulin, Ramicane, Infubinol, and Ceftamin.
-   Identified outliers.
-   Generated a box plot of final tumor volumes for each treatment group.

### Line and Scatter Plots

-   Created a line plot of tumor volume vs. time for a mouse treated with Capomulin.
-   Created a scatter plot of mouse weight vs. average tumor volume for Capomulin.

### Correlation and Regression

-   Calculated correlation coefficient and linear regression between mouse weight and average tumor volume for Capomulin.
-   Plotted linear regression on scatter plot.

## Skills Acquired

-   Pandas for data manipulation
-   Matplotlib for data visualization
-   Statistical analysis
-   Data cleaning and merging
-   Plot creation (bar, pie, line, scatter, box)
-   Correlation and regression analysis
-   Git and GitHub/GitLab workflow
