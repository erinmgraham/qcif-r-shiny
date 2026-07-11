---
title: Setup
---

## Data Sets

The [csv file used in this lesson](episodes/data/bcc_occupation_count_2041.csv) lesson was generated from data from an [Employment Projection Model](https://data.brisbane.qld.gov.au/explore/dataset/occupation-employment-by-usual-resident-employment/information/): A set of employment forecasts which reflect the Brisbane City Council view of the likely SEQ Regional Employment patterns in the period between 2011 and 2041. They were prepared by the National Institute of Economic and Industrial Research.

We chose two of the datasets "Occupation employment by usual resident employment" and "Industry employment by usual resident employment" and retained only the variables describing region (SA4_Name), suburb (SA2_Name), occupation/industry (Name_2), and projected employment in 2041 (SC2_2041). To create a smaller dataset suitable for teaching, the top three occupations and industries within each region-suburb combination were selected and included in the final dataset.


## Software Setup

This lesson assumes you have `R` and `RStudio` installed on your computer.

- Download and install the [latest version of R](https://cran.r-project.org/).
- Download and install [RStudio](https://posit.co/downloads/).
- Install R Packages:
  - [shiny](https://cran.r-project.org/web/packages/shiny/index.html)
  - [bslib](https://cran.r-project.org/web/packages/bslib/index.html)
  - [tidyverse](https://cran.r-project.org/web/packages/tidyverse/index.html)
