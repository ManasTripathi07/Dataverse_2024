# Dataverse

## CO2 Emission Analysis

### Project Overview

This project is focused on data analysis of CO2 emission from various countries and different industries from the period of 1995 up to 2018. The aim will be to clean and visualize this dataset to further understand the trends in emissions, the distribution of global emission among different countries, and gain deeper insight into emission patterns around the world.

### Dataset Description

The dataset contains CO2 emissions across various countries and industries over a range of years. Key columns in the dataset include:

	•	Country: Represents the name of the country.
	•	Industry: Represents various industries producing CO2 emissions.
	•	F1995 to F2018: CO2 emission values for each year from 1995 to 2018.

Note: The column Indicator was removed as it was a duplicate.

### Preprocessing Steps

	1.	Removing Duplicate Columns: The column Indicator was dropped as it was redundant.
	2.	Filtering Unnecessary Rows: Rows containing CO2 Emissions Multipliers and CO2 Emissions Intensities under CTS_Name were dropped.
	3.	Handling Missing Values:
	•	Dropped the F2003 column due to all values being null.
	•	Remaining missing values in specific year columns were filled with 0.
	4.	Handling Negative Values: Negative CO2 emission values were replaced with 0, since CO2 emissions cannot be negative.
	5.	Final Dataset: The cleaned dataset was used for further analysis.

## Analysis and Visualizations

### CO2 Emissions by Country

The total CO2 emissions for each country were calculated for the year 2012. A bar plot was generated to visualize the total CO2 emissions across all countries.

### CO2 Emissions by Industry

Industries producing CO2 emissions in 2012 were analyzed, and their total CO2 emissions were visualized using a bar plot.


### Top 10 Countries & Industries

For a more focused analysis, the top 10 countries and industries with the highest total CO2 emissions in selected years were visualized.

	•	Top 10 Countries: CO2 emissions were visualized for the top 10 countries in 2012, and a comparison was made between the years 2012 and 2013.
	•	Top 10 Industries: Industries with the highest CO2 emissions from 1995 to 2018 were plotted.

## Results

Key findings include:

	•	Certain countries and industries are major contributors to global CO2 emissions.
	•	CO2 emissions have varied across years, with some industries showing increasing trends over time.

## Technologies Used

	•	Pandas: Data manipulation and cleaning.
	•	Seaborn & Matplotlib: Data visualization.
	•	NumPy: Handling numerical operations.
	•	Jupyter Notebook: Development environment.
