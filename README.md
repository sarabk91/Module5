# Module5 Homework Summary:

In this homework assignment, we performed a comprehensive analysis of a dataset related to cancer treatment in mice. The tasks involved preparing the data, generating summary statistics, creating bar charts and pie charts, calculating quartiles and identifying outliers, creating line plots and scatter plots, and calculating correlation and regression.

We started by merging two dataframes, mouse_metadata and study_results, into a single dataframe. We then displayed the number of unique mice IDs and checked for any mouse ID with duplicate time points. The data associated with the duplicate mouse ID was removed, and the updated number of unique mice IDs was displayed.

Next, we generated summary statistics by creating a dataframe with mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

We created bar charts to visualize the total number of rows (Mouse ID/Timepoints) for each drug regimen. Both Pandas DataFrame.plot() and Matplotlib's pyplot methods were used to create identical bar charts. Similarly, we created pie charts to represent the distribution of female versus male mice in the study using both Pandas DataFrame.plot() and Matplotlib's pyplot methods.

We then focused on four promising treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin) to calculate quartiles, identify potential outliers, and create a box plot to visualize the distribution of the final tumor volume for each treatment group.

In addition, we selected a mouse treated with Capomulin and generated a line plot of tumor volume versus time point for that specific mouse. Furthermore, we created a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.

To conclude, we calculated the correlation coefficient and performed linear regression analysis between mouse weight and average observed tumor volume for the Capomulin treatment regimen. We visualized the linear regression model by overlaying it on the scatter plot. The correlation coefficient and the linear regression line were displayed to provide insights into the relationship between mouse weight and tumor volume.

Overall, this homework assignment allowed us to gain a deeper understanding of the dataset through data preparation, descriptive statistics, visualization, and statistical analysis.
