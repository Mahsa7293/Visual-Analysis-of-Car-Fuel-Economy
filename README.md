# Visual-Analysis-of-Car-Fuel-Economy
## Dataset Description
This dataset contains test data used to evaluate fuel economy. The information is derived from vehicle testing conducted at EPA's National Vehicle and Fuel Emissions Laboratory in Ann Arbor, Michigan, as well as from data submitted by vehicle manufacturers to the EPA. The dataset comprises 832 rows and 13 features, detailing various properties of car models from 2018. Key features include fuel type, the number of engine cylinders, wheel drive configuration, vehicle class, and more.

## Summary of Findings
During the exploration of the dataset, several notable relationships among the variables were observed:

- Engine Displacement & Fuel Economy:
There is a strong negative correlation between engine displacement (displ) and both city MPG and highway MPG.
- Displacement & Environmental Impact:
A negative correlation exists between engine displacement and the greenhouse gas score.
- Greenhouse Gas Score Relationships:
Positive correlations were found between the greenhouse gas score and both city MPG and highway MPG.
- Engine Cylinders:
A higher number of engine cylinders is associated with lower city MPG, lower highway MPG, and, to some extent, a lower greenhouse gas score.
- Wheel Drive Configurations:
While both 2WD and 4WD vehicles exhibit similar air pollution scores, 4WD vehicles tend to have a lower greenhouse gas score compared to 2WD.
- Vehicle Class Trends:
The standard SUV class recorded the lowest ratings across all numeric variables, with other classes generally showing an upward trend in these metrics.

## Key Insights for Presentation
For the presentation, the analysis focuses on the relationships between numeric variables and ordinal variables—particularly how the air pollution score, greenhouse gas score, and fuel type influence vehicle performance and environmental impact. The approach includes:

- Frequency Analysis:
Histograms for numeric variables and count plots for ordinal variables to illustrate the distribution of key features.
- Comparative Analysis:
Violin plots and box plots to compare engine cylinders and wheel drive configurations against all numeric variables.
- Bivariate Exploration:
Specific comparisons such as:
Air pollution score vs. city MPG across different vehicle classes and fuel types.
Greenhouse gas score vs. engine displacement across vehicle classes and fuel types.

This analysis provides valuable insights into the factors influencing fuel economy and environmental performance, guiding future decisions in vehicle design and production.
