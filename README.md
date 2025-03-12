# Impact of Socioeconomic Factors on Literacy Rates Across Countries

## Overview
This project examines the relationship between key socioeconomic indicators and literacy rates across 217 countries, using publicly available data from the World Bank. The analysis focuses on three primary predictors:

- GDP (economic development)
- Government expenditure on education
- Urban population size

## Key Findings
- Economic development (GDP) shows the strongest relationship with literacy rates, with a 1-unit increase in log GDP associated with a 10.69 percentage point increase in literacy rate
- Regional analysis reveals significant disparities in literacy achievement, with Europe and North America showing consistently high rates while Africa displays greater variability
- The multiple regression model explained 22.1% of the variance in literacy rates (R² = 0.221)
- Substantial missing data (84% missing literacy observations) presents a significant limitation to the analysis

## Methodology
The analysis employs the following statistical techniques:
- Data cleaning and transformation
- Exploratory data analysis
- Correlation analysis
- Multiple linear regression
- Data visualization

## Data
The data used in this analysis were obtained from the World Bank's World Development Indicators database:
- Literacy rate, adult total (% of population aged 15 and above)
- GDP (current US$)
- Government expenditure on education (% of government expenditure)
- Urban population

## Project Structure
- `literacy_rate_analysis.R`: Main R script containing all analysis code
- `data/`: Directory containing raw and processed data files
- `figures/`: Directory containing generated visualizations

## Limitations and Future Directions
The primary limitation of this study was the substantial missing data, especially for the outcome variable of literacy rates. Future research should seek to obtain more complete literacy data, potentially by incorporating other data sources or imputation methods.

## Author
Hashirr Lukmahn

## Acknowledgments
This project was completed as part of the STAT4000-001 course at the University of Colorado Boulder.
