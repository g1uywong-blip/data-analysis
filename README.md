# Data Analysis Project

This repository contains an R project for analyzing economic data using Excel and the `tidyverse`. The main focus is cleaning, transforming, and visualizing data from the `dataanlytics.xlsx` dataset.

## Dataset

The dataset `dataanlytics.xlsx` contains economic indicators for various sectors from 2007 to 2017.  

**Important:** You **do not need to download the file manually** — the R script downloads it directly from GitHub.

## R Script

The main script is `read_data_github.R`. It performs the following steps:

1. Load required libraries: `tidyverse`, `readxl`, `lubridate`.  
2. Download the Excel file directly from GitHub.  
3. Clean the dataset by removing unnecessary rows and columns.  
4. Rename columns for clarity.  
5. Parse the date column and add `Year` and `Month`.  
6. Convert numeric values to proper numbers.  
7. Filter the data for years 2007 to 2017.  





