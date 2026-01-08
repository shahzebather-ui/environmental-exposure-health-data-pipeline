# Environmental Exposure & Health Data Pipeline

## Overview
Python data pipeline integrating environmental exposure, socioeconomic, and health outcome datasets into analysis-ready county-level panels for longitudinal analysis.

## Data Sources
- EPA air quality metrics (e.g., PM2.5 exceedance)
- American Community Survey (ACS) socioeconomic indicators
- CDC PLACES health outcomes

## Approach
- Clean and standardize multi-source datasets
- Merge across geography (county) and time (longitudinal panels)
- Engineer features for downstream statistical analysis and visualization

## Project Structure
- **Notebook (main)**: end-to-end data prep workflow  
  `notebooks/environmental_exposure_health_pipeline.ipynb`
- **Data notes**: sources and exclusions  
  `data/README.md`

## Tools
Python, Pandas, NumPy, Jupyter
