# ENVIRE-JPIAMR

This is the parent directory containing repositories related to Work Package 3 (WP3) of the ENVIRE-JPIAMR project.  
- WP3 focuses on assessing the risk of human exposure to ESBL-producing *Escherichia coli* originating from broiler production, using a multi-pathway Quantitative Microbial Risk Assessment (QMRA) model.  
- Each repository within this directory represents a distinct module of the QMRA model.

## Prerequisites

- R (tested with version 4.1.2)
- [`here`](https://cran.r-project.org/package=here) package installed

## Directory Setup

To initialize the environment, follow these steps:

1. In the parent directory, create an empty file named `.here`.
2. Create an `init.R` script with the following contents:

   ```r
   library(here)

   here::i_am("init.R")
   ```
3. Run the initialization script from within the R environment

   ```
   source("init.R")
   ```
