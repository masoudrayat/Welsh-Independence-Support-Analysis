# Welsh Independence Support Analysis

![R](https://img.shields.io/badge/language-R-blue)
![RStudio](https://img.shields.io/badge/RStudio-IDE-blue)

<img src="https://www.r-project.org/logo/Rlogo.png" alt="R Logo" width="100" height="100">

This project aims to analyse survey data from Welsh residents to identify key factors influencing their support for Welsh independence, with a focus on demographic characteristics and Welsh language proficiency. The project is implemented using the R programming language.

## Table of Contents
- [Data Preparation and Cleaning](#data-preparation-and-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Statistical Analysis](#statistical-analysis)
- [Predictive Modelling](#predictive-modelling)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Run the Analysis](#run-the-analysis)

## Data Preparation and Cleaning
- Loaded and cleaned the dataset to ensure it only included current residents of Wales.
- Handled missing and invalid values, ensuring data validity and integrity.

## Exploratory Data Analysis
- Analysed support levels for Welsh independence across different regions (North vs. South Wales).
- Visualised data distributions and relationships between support for independence and Welsh language proficiency.

## Statistical Analysis
- Conducted hypothesis testing to compare support for Welsh independence between North and South Wales, finding a significant difference in mean support levels.
- Explored linear correlations between support for independence and various measures of Welsh language proficiency, identifying significant positive relationships.

## Predictive Modelling
- Developed simple linear regression models to predict support for Welsh independence based on Welsh language proficiency.
- Analysed the impact of language proficiency on support levels, revealing that listening and writing abilities are strong predictors.

The project provided valuable insights into the demographic and linguistic factors influencing support for Welsh independence.

## Project Structure

The project is organized into the following directories and files:

- `data/`: Contains the dataset used for analysis.
  - `contents.csv`: The main dataset with survey data.
- `docs/`: Contains the generated report.
  - `Welsh_Independence_Support_Analysis_Report.pdf`: The PDF report summarising the findings and analysis.
- `scripts/`: Contains the R Markdown script for the analysis.
  - `Welsh_Independence_Support_Analysis.Rmd`: The main R Markdown script that performs the analysis and generates the report.

## Prerequisites

- [R](https://www.r-project.org/)
- [RStudio](https://www.rstudio.com/)

## Run the Analysis

Knit the `Welsh_Independence_Support_Analysis.Rmd` file in RStudio to generate the report. This will execute all code chunks and produce results and visualisations.

This setup ensures a structured approach to analysing support for Welsh independence, allowing for reproducibility and ease of understanding for future reference.
