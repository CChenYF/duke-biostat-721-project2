# BIOSTAT 721 Project 2: Durham Air Quality

This project processes and explores daily air-quality measurements to support a study of air pollution and sickle cell disease in Durham County, North Carolina. It cleans repeated and erroneous measurements, summarizes annual concentration ranges, and visualizes monthly patterns in carbon monoxide (CO), fine particulate matter (PM2.5), and ozone (O3).

## Data source

The data are raw daily measurements from the U.S. Environmental Protection Agency air-pollution monitor at RDU Airport. The files cover 2018, 2019, and January through April 2020.

## File structure

- `data/` contains the three source CSV files: `AQ_2018.csv`, `AQ_2019.csv`, and `AQ_2020.csv`.
- `Project2.qmd` contains the documented cleaning function, annual summary tables, plots, and interpretation.
- `README.md` describes the project and how to reproduce the report.

## Reproduce the analysis

1. Open the repository as an R project or set the repository root as the working directory.
2. Install R 4.4 or later and the required packages: `tidyverse`, `lubridate`, and `flextable`.
3. Install Quarto if it is not already available.
4. Render `Project2.qmd` to create the Word report. From a terminal in the repository root, run `quarto render Project2.qmd`.

The source CSV files must remain in the `data/` folder so the relative file paths used in the report continue to work.

## Author and date

Yifei Chen<br>
November 22, 2026
