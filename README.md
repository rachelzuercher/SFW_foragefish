<!-- badges: start -->
<!-- badges: end -->

## Seafood Watch Forage Fish Identification

This repository includes data and analysis scripts for the white paper:

**Roos, Marjoleine, M.H. (2024). Forage species: Who is key? Monterey Bay Aquarium Seafood Watch.** [ADD URL ONCE AVAILABLE]

---
## Collaborators:
*Marjoleine M.H. Roos, Quantitative Marine Ecologist (LEAD AUTHOR)*

*Santi Roberts, Monterey Bay Aquarium*

*Sam Wilding, Monterey Bay Aquarium*

*Andre Boustany, Monterey Bay Aquarium*

*Rachel Zuercher, Monterey Bay Aquarium*


---
## Description:
[Add Executive Summary here once report is finalized]

--- 
## In the repository:
The data/raw folder of .xlsx files and two .R scripts are needed to replicate these analyses.

The folder contains two types of .xlsx files:

`diet.xlsx` -- diet matrix data file with all species used in the project

`groupdata.xlsx` -- data file containing all species groups used in the project (rows) 
and the following information for each: B, QB, ED, ED source, group name and group code (columns)

`index_calculations.R` -- R code to calculate connectance, SURF mass and SURF energy indices
`group.aggregating.fxn.R` -- R code to create function to aggregate groups in diet matrices to calculate keyness at a coarser taxonomic resolution

