# Surface Water Quality Data Analysis

## Overview
This project focuses on analyzing surface water quality data collected from various monitoring stations in Baltimore, USA. The dataset provides information on parameters such as copper, fecal coliform, lead, oil & grease, zinc, conductivity, dissolved oxygen, ammonia-nitrogen, pH, and water temperature, among others. The analysis aims to gain insights into trends, variations, and factors affecting water quality.

## Data Source
The data is sourced from [Baltimore City's Open Data Portal](https://data.baltimorecity.gov/datasets/surface-water-quality-data-1995-through-present/about).

## Package Installation and Import
Necessary packages including Pandas, Matplotlib, and Seaborn are imported for data manipulation, visualization, and analysis.

## Loading the Dataset
The dataset is loaded using Pandas' `read_csv` function. A quick glimpse of the data reveals its structure and content.

## Data Preparation and Cleaning
Null values are dropped, and data types are converted to their appropriate formats. Columns containing GPS coordinates and datetime are converted to numeric and datetime formats, respectively.

## Analysis Outcomes
- Line plot: Shows a slight decrease in water quality over the years based on mean values.
- Scatterplot: Indicates variations in water quality results across different parameters and locations.
- Map: Visualizes monitoring stations and their average water quality results.
- Bar plots: Display the top 10 stations with the highest and lowest water quality results.
- KDE plot: Represents parameter-wise distribution of water quality results.
- Histogram: Illustrates sample counts for each parameter.
- Heatmap: Highlights trends of water quality parameters over time.
- Comparative plot: Shows changes in water quality from 2000 to 2022 for top 10 stations with the highest improvement and deterioration.

## Inferences and Conclusion
- Variation in water quality across different monitoring stations.
- Certain stations consistently show higher water quality.
- Some parameters have higher average water quality results, indicating their significance.
- Variation in sample counts for different parameters.

## References and Future Work
### References:
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Pandas Documentation](https://pandas.pydata.org)
- [Matplotlib Documentation](https://matplotlib.org)

### Future Work:
- Building predictive models to forecast water quality levels.
- Incorporating additional factors such as weather conditions for more accurate predictions.

