# Maternal Healthcare Analysis and SDG Index Score Prediction
## Project Overview
This project analyzes maternal healthcare indicators across different countries and their relationship with the Sustainable Development Goals (SDG) Index Score. Using multiple linear regression, we predict the SDG Index Score based on three key maternal healthcare indicators:

1. Skilled Birth Attendant Coverage
2. Service Coverage
3. Maternal Mortality Rate
## Data Sources
Country Indicators: This dataset includes various demographic and healthcare indicators for countries worldwide.
SDG Index Scores: This dataset contains the SDG Index Scores for various countries, representing their progress toward achieving the Sustainable Development Goals.
## Files and Folders
country_indicators.csv: Contains various healthcare and demographic indicators for multiple countries.
sdr_fd5e4b5a.csv: Contains the SDG Index Scores for various countries.
country_codes.csv: Contains the ISO-alpha3 country codes and their respective regions and sub-regions.
analysis.Rmd: The R Markdown file with code and analysis.
README.md: This file, providing an overview of the project and instructions on how to run the analysis.
## Analysis Workflow
1. Data Cleaning and Preparation:

-Load and clean the country_indicators.csv file, selecting relevant columns and renaming them for clarity.
-Merge the maternal healthcare data with SDG Index Scores using the country codes as keys.

## Multiple Linear Regression:

-A multiple linear regression model is fitted to predict the SDG Index Score using the selected maternal healthcare indicators as independent variables.
-The regression model provides insights into how these indicators influence the SDG Index Score.
Visualization:

-Scatter plots with fitted regression lines for each independent variable against the SDG Index Score.
-Residuals vs. Fitted Values plot to assess model assumptions.
-Histograms to visualize the distribution of each indicator against the SDG Index Score.

## How to Run the Project
-Ensure you have R and RStudio installed on your system.
-Install the required R packages:
R
Copy code
'install.packages(c("tidyverse", "ggplot2"))'
-Open the analysis.Rmd file in RStudio.
-Click the Knit button to generate the HTML, PDF, or Word output of the analysis.

## Project Output
-Model Summary: Provides detailed coefficients, p-values, and R-squared values for the regression model.
-Plots: Visualizations include scatter plots with regression lines, residual plots, and histograms showing the distribution of healthcare indicators against the SDG Index Score.

## License
This project is open-source and available under the MIT License.
