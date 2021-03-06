# PeptidoformVisualisation
R package for launching shiny app to visualise Peptidoform data

# The package
This R package contains all code to launch a shiny app for the visualisation of quantitative peptidoform data. 
The user can upload a peptide intensity file and a metadata file containing information about the experiment setup. 
With the app, the user can perform preprocessing (normalisation, log transformation) and visualise the intensity data.

For more information about the package and the included example data, please see our preprint: https://www.biorxiv.org/content/10.1101/2022.05.05.490796v1.full

# How to install
In RStudio (or another IDE), use 

```
if (!require("devtools")) {install.packages("devtools")}
devtools::install_github("statOmics/PeptidoformViz") 
```

This will install the package and its dependencies.

# How to use
To load package: 

```
library(PeptidoformViz)
```

To launch shiny app, use: 

```
launchPeptidoformViz()
```
