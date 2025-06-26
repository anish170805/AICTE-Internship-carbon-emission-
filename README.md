# AICTE Internship

## Prediction of CO2 emissions from country-specific data

Week 1

This project analyzes country-specific data and develops machine learning models to predict CO2 emissions based on various country parameters. The dataset used is the Climate Change Data from the World Bank Group, which includes data on:

- Greenhouse gas emissions (CO2, CH4, N2O, etc.)
- Population parameters (population count, urban population, growth, etc.)
- Economic indicators (GDP, GNI, Foreign Direct Investment, etc.)
- Land-related parameters (cereal yield, agricultural land, protected areas, etc.)
- Climate data (precipitations, national disasters, etc.)
- Energy use
- Health infrastructure
- And more

The project is divided into two stages:

1. Data cleaning and preparation
2. Data exploration and predictive analysis

The data cleaning and preparation stage is implemented in the Jupyter Notebook `1_data_preparation.ipynb`.

Week 2

The `2_data_exploration.ipynb` notebook is where we begin to dig into and learn about the cleaned data.

1. Loading the Clean Data: The notebook first loads the cleaned dataset developed in the last step.

2. Summary Statistics: It computes and prints simple statistics (such as averages, minimums, and maximums) for every feature, and this allows us to get a feel for the range of the data and the typical values.

3. Visualizations: It generates various forms of graphs and charts (histograms, bar charts, and scatter plots) to visualize the data distribution and identify patterns or outliers.

4. Exploring Relationships: It examines how various features correlate with one another. For instance, it may demonstrate the correlation between CO2 emissions and population, GDP, or energy consumption using correlation matrices or scatter plots.

5. Trends Over Time: The notebook may plot how certain features (like CO2 emissions) change over the years for different countries, helping us see trends or shifts.

6. Preparing for Prediction: If the notebook includes predictive analysis, it may show how to select important features, split the data into training and testing sets, and build simple machine learning models to predict CO2 emissions based on other country parameters.
