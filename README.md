# Project Overview

This project analyzes the role of intangible assets in Canada's economic productivity. Using data from Statistics Canada, it examines how the composition of capital—specifically the shift from tangible to intangible assets—is changing over time and impacting labor productivity across various industries.

The project is structured around two main components:
1. Analysis of Canadian Industry Balance Sheets: This section explores long-term trends in tangible and intangible assets using data from Statistics Canada Table 33-10-0499-01. It includes time-series visualizations to highlight the growing importance of intangible assets.
2. Replication of Academic Findings: This section replicates and visualizes key findings from the Statistics Canada research paper, "Data, Intangible Capital and Economic Growth in Canada," by Allen, Gu, and Macdonald (2025). The goal is to provide a visual breakdown of how different factors—tangible capital, intangible capital, labor composition, and multifactor productivity (MFP)—contribute to overall labor productivity growth by industry.

The R Markdown (.Rmd) file contains all the code and analysis, producing a comprehensive report that includes data cleaning, data visualization, and a summary of key insights.



# Data Sources

The analysis relies on two primary data sources from Statistics Canada:

## Balance Sheet Data:

Source: Statistics Canada, Table 33-10-0499-01, "Balance sheet, income statement and taxation statistics with selected financial ratios, by financial industries."

DOI: https://doi.org/10.25318/3310049901-eng

## Productivity Data:

Source: Allen, R., Gu, W., & Macdonald, R. (2025). "Data, Intangible Capital and Economic Growth in Canada." Statistics Canada Analytical Studies Branch Research Paper Series.

Link: https://www150.statcan.gc.ca/n1/pub/11f0019m/11f0019m2025003-eng.htm

        Note: The data used for replication is extracted from the tables and charts within this paper and stored in a separate Excel file.



# Repository Structure

Data_Assets_and_Intangible_Capital_in_Canadian_Productivity.Rmd: The main R Markdown script containing all code, analysis, and visualizations.

Data_Assets_and_Intangible_Capital_in_Canadian_Productivity.html: Output file
Data_Assets_and_Intangible_Capital_in_Canadian_Productivity.pdf: Output file



# Dependencies

This project requires several R packages, which are managed using pacman::p_load. All dependencies are automatically loaded at the beginning of the R Markdown file.

    tidyverse

    ggplot2

    dplyr

    readxl

    knitr

    kableExtra

    modelsummary

    patchwork

    ggpubr

    ...and other packages as listed in the setup chunk of the .Rmd file.


# How to Run the Project

To replicate the analysis and generate the report, follow these steps:

1. Clone the Repository: (mainly all you need is the Rmd file. follow the links to the data from that file.
2. Set Up the Environment: Ensure you have R and RStudio installed. The project uses a local .Renviron file to manage the data path. You'll need to update the project_path variable to point to the data/ directory.
3. Run the R Markdown File: Open the .Rmd file in RStudio and click the "Knit" button. This will execute the code and generate the final report in your desired format (PDF and HTML). The knitted files will be saved in the repository's root directory or the outputs/ folder if you've configured it.


    
