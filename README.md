# Project Title: Population Visualization Using World Bank Data

## Problem Definition
This project involves creating visualizations such as bar charts and histograms to understand the distribution of a population-related variable. We used population data across different countries to gain insights from the year 2021.

## Dataset
- The dataset was obtained from the World Bank official site.
- It contains data such as country names, country codes, indicator names and codes, and yearly population figures.

## Tools & Libraries
- Python
- Pandas for data handling
- Matplotlib and Seaborn for visualization
- Jupyter Notebook as the working environment

## Data Collection
- The CSV file was loaded using Pandas.
- The dataset was structured with metadata in the first few rows, so those were skipped while loading.
- Initial inspection was done to preview the first few rows and understand the column layout.

## Data Visualization

### Bar Chart of Top 15 Countries in 2021
- The data was filtered to keep only the population column for the year 2021.
- Missing values were removed to avoid errors.
- The countries were sorted by population in descending order.
- The top 15 countries were selected.
- A bar chart was created to visualize and compare their population sizes.

### Histogram of Population Distribution in 2021
- A histogram was created using all country population data from 2021.
- The x-axis represented population ranges, and the y-axis represented the number of countries falling into each range.
- The distribution showed positive skewness, indicating that most countries have relatively lower populations, while a few have very large populations.

## Observations
- The bar chart clearly highlighted the most populated countries in the world.
- The histogram revealed a skewed distribution, suggesting unequal population sizes among countries.
- These visualizations helped in understanding global population patterns for the selected year.

