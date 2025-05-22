# DSA210-Term-Project

# Project Overview

## Motivation

Global “happiness” scores are now widely used by governments and NGOs as a shorthand for quality of life, yet the drivers of national well being are still debated. By combining the latest World Happiness Report data with basic labour market information (unemployment rates) we aim to quantify which socioeconomic factors most strongly track a country’s average life satisfaction and highlight levers that policy makers can realistically pull.


## Data & Analysis Pipeline

Dataset includes 135 countries, 10 variables: 
- Happiness score (target)
- GDP per capita, social support
- Healthy life expectancy
- Freedom of choice
- Generosity
- Perceived corruption
- Unemployment rate

Exploration produced by distribution plots, and a correlation heat map.



## Key Findings

- Economic strength dominates GDP per capita shows the highest positive correlation with happiness (r ≈ 0.81).

- Health matters almost as much healthy life expectancy (r ≈ 0.80) rivals GDP as a predictor.

- Community counts social support (r ≈ 0.75) and freedom of choice (r ≈ 0.55) are strong secondary drivers.

- Generosity is surprisingly weak correlation is mild (r ≈ 0.16) and perceptions of corruption sit mid pack (r≈ 0.45).

- Joblessness erodes well-being. Unemployment rate is the only factor with a clear negative link (r ≈ -0.20).

- Cluster analysis reveals four broad “happiness archetypes,” separating high income/high support nations from low income, high unemployment peers.


## Limitations & Future Work

- Single year results capture correlation, not causation, and ignore year to year dynamics.

- Omitted variables like education quality, environmental metrics, inequality, and cultural factors could refine the picture.

- Next steps could be to expand to a 10 year panel, test causal paths with fixed effects models or instrumental variables, and build an interactive dashboard that lets users explore “what if” policy scenarios.

- This overview sets the stage for a data driven conversation about how economic and social policies translate into everyday well being. 


# Source

My source of datasets are here :

https://www.kaggle.com/datasets/sougatapramanick/happiness-index-2018-2019

https://www.kaggle.com/datasets/pantanjali/unemployment-dataset


