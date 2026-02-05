# Comparative Precipitation Analysis: Buffalo vs. San Diego (1940–2025)

# Overview

This project analyzes long-term annual precipitation patterns for Buffalo, NY and San Diego, CA using airport station data from 1940–2025. The cities were selected to contrast precipitation behavior across distinct climate regimes and to demonstrate how statistical analysis can support environmental planning and risk-informed decision-making.

# Data

Variables: Annual precipitation (inches) for Buffalo and San Diego

Time period: 1940–2025

Format: CSV imported into R as a data frame

# Methods

The analysis was conducted in R using a reproducible, script-based workflow:

Imported and explored precipitation data using summary statistics and descriptive measures

Visualized precipitation distributions with histograms and fitted normal probability density curves to assess variability and uncertainty

Created an indicator variable to separate early (1940–1982) and late (1983–2025) periods

Subset the data by time period for each city

Performed two-sample t-tests (Welch and equal-variance) to evaluate whether mean annual precipitation differed significantly between historical and recent periods

# Key Findings

Buffalo shows higher mean precipitation and greater interannual variability than San Diego.

Distributional plots highlight fundamentally different precipitation regimes across the two cities.

Hypothesis testing provides statistical evidence for evaluating whether observed changes in precipitation over time are significant, illustrating how uncertainty must be accounted for in climate-related analyses.

# Outputs

Reproducible R script (Exercise1.R)

Precipitation histograms with fitted normal curves

Summary statistics and hypothesis test results

# Skills Demonstrated

Environmental data analysis, statistical inference, uncertainty visualization, R programming, and reproducible analytical workflows.


