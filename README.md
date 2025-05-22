### DSA210-Term-Project

## Project Overview
# Motivation
Global “happiness” scores are now widely used by governments and NGOs as a shorthand for quality of life, yet the drivers of national well-being are still debated. By combining the latest World Happiness Report data with basic labour-market information (unemployment rates) we aim to quantify which socioeconomic factors most strongly track a country’s average life satisfaction and highlight levers that policy-makers can realistically pull.

# Data & Analysis Pipeline

Dataset – 135 countries, 10 variables: Happiness score (target) plus GDP per capita, social support, healthy-life expectancy, freedom of choice, generosity, perceived corruption, and unemployment rate.
Pre-processing – handled two missing unemployment entries with mean imputation, verified ranges, normalised quantitative features.
Exploration – produced descriptive statistics, distribution plots, and a correlation heat-map.
Modelling – ran (i) multiple linear regression to estimate marginal effects, (ii) Random-Forest regression to rank feature importance, and (iii) K-means clustering (k=4) to group countries with similar well-being profiles.
Validation – 10-fold cross-validation for regression models; silhouette score to confirm cluster stability.

# Key Findings

Economic strength dominates – GDP per capita shows the highest positive correlation with happiness ( r ≈ 0.81 ).
Health matters almost as much – Healthy-life expectancy ( r ≈ 0.80 ) rivals GDP as a predictor.
Community counts – Social support ( r ≈ 0.75 ) and freedom of choice ( r ≈ 0.55 ) are strong secondary drivers.
Generosity is surprisingly weak – correlation is mild ( r ≈ 0.16 ); perceptions of corruption sit mid-pack ( r ≈ 0.45 ).
Joblessness erodes well-being – unemployment rate is the only factor with a clear negative link ( r ≈ -0.20 ).
Cluster analysis reveals four broad “happiness archetypes,” separating high-income/high-support nations from low-income, high-unemployment peers.

# Limitations & Future Work

Single year results capture correlation, not causation, and ignore year to year dynamics.
Omitted variables like education quality, environmental metrics, inequality, and cultural factors could refine the picture.
Next steps could be to expand to a 10 year panel, test causal paths with fixed effects models or instrumental variables, and build an interactive dashboard that lets users explore “what-if” policy scenarios (e.g., how a 2 % drop in unemployment might lift national happiness).
This overview sets the stage for a data-driven conversation about how economic and social policies translate into everyday well-being. 


# Objectives
Main aim of my project is demonstrate what is most important to be happy.

# Dataset
My dataset includes:


# Source

My source of datasets are here :


