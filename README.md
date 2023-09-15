# CO2 INTENSITY ELECTRICITY ANALYSIS

<h2>Import necessary libraries:</h2>

pandas for data manipulation and analysis.

datetime for working with dates (although it's not used in this code snippet).

altair for creating interactive visualizations.

numpy for numerical operations.

matplotlib.pyplot and seaborn for data visualization.

io (not used in this snippet).

Read the data from the '2017_CO2_IntensEL_EEA.csv' file into a Pandas DataFrame and print the first few rows and data information.

<h2>Procedure:</h2>

Convert the 'Year' column to a string data type.

Create a list of unique countries and print the unique years in the 'Year' column.

Find the row with the maximum value in the 'ValueNumeric' column and print it.

Create a list of Mediterranean countries and filter the data for each country into a dictionary called df_medit.

Create an Altair chart to visualize CO2 intensity data over time for Mediterranean countries.

Calculate the average CO2 values for each country and create a DataFrame df_mean. Add a column 'IsMediterranean' to mark whether a country is Mediterranean or not.

Create a Seaborn scatterplot to visualize the average CO2 values of countries, distinguishing between Mediterranean and non-Mediterranean countries.

Filter the DataFrame to include only data for the years 1990 and 2017. Pivot the data, and create a horizontal bar chart to show the change in CO2 intensity between 1990 and 2017 for each country.

Customize the appearance of the bar chart, including coloring, annotations, legends, and labels.

Display the bar chart with relevant information about the data source.

<h2>Result:</h2>

This code appears to be a comprehensive analysis and visualization of CO2 intensity data for European countries, focusing on Mediterranean countries and changes over time. If you have any specific questions or need further explanations about any part of the code, please feel free to ask.




