# MA304 Final Project: Exploratory Data Analysis of Law Enforcement Activities

## Project Overview

The "MA304 Final Project" involves analyzing a dataset related to law enforcement activities, particularly focusing on incidents of use of force. The analysis aims to uncover patterns, correlations, and insights from the data, which can be useful for understanding various aspects such as officer injuries, subject offenses, incident rates, and their distributions over time and location.

## Analysis Components

### Data Loading and Preparation

- The project begins with loading necessary libraries and reading the dataset (`37-00049_UOF-P_2016_prepped.csv`) using R's `read.csv` function.
- Initial data preprocessing steps involve converting date and time formats, extracting relevant features like incident month, hour, and day, and grouping the data for further analysis.

### Descriptive Statistics

- Descriptive statistics are presented through a table (`Top 5 offences`) showing the top 5 offenses by frequency, providing quick insights into the most common offenses.

### Visualization

- **Bar Plots:** Analyze the relationship between officer race/gender and injuries sustained by officers or subjects during incidents.
- **Box Plot:** Examine the incident rate trends across different subject races over months.
- **Pie Chart:** Display the distribution of offenses across different subject races.
- **Matrix Correlation and Heatmap:** Explore correlations between different features like sector, beat, street number, and analyze crime counts across officer races and months.
- **Scatter Plot:** Investigate the relationship between subject offenses and whether subjects were arrested, colored by the type of officer injury.
- **Time Series:** Illustrate the variation in incident counts over hours of the day.
- **Density Plot:** Visualize the distribution of incident rates, providing insights into their frequency and spread.
- **Map:** Display the geographic distribution of reported crimes using latitude and longitude coordinates.

### Interpretation

- Each visualization is accompanied by an interpretation that helps understand the patterns, correlations, and insights derived from the data.
- Interpretations are clear and concise, enabling stakeholders to grasp the key findings of the analysis easily.

## Conclusion

In conclusion, the "MA304 Final Project" effectively utilizes exploratory data analysis techniques to uncover meaningful insights from a law enforcement dataset. The combination of descriptive statistics, visualizations, and interpretations provides a comprehensive understanding of various aspects related to officer-involved incidents, which can inform decision-making processes and strategies in law enforcement agencies.
