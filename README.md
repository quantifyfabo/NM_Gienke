# Disaster Occurrence and Media Coverage: Evidence from Tagesschau

Replication repository and data pipeline for the empirical analysis of natural disaster reporting in German public broadcast news (*Tagesschau*, 2024–2025).

## Pipeline Structure

Execute the scripts in sequential order:

1. `00_TS_API.Rmd` – Tagesschau archive data scraping / API extraction
2. `01_DataWrangling.R` – Text cleaning, preprocessing, and filtering
3. `02_Dictionary.R` – Dictionary-based classification of natural disasters
4. `03_Countries.R` – Geographic entity extraction and country matching
5. `04_Analyze.R` – Econometric modeling (EM-DAT & V-Dem integration)
6. `05_Plots.R` – Visualizations, descriptive figures, and regression output

## Requirements
* R (>= 4.3)
* Key packages: `tidyverse`, `quanteda`, `countrycode`

## Data
Raw and processed data files are located in `/Datasets`.
