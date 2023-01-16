# Molecules Dataset

This folder is dedicated to the datasets I will be using on my master's dissertation. Here will be the datasets (preferably in .csv) both **raw** and **curated** for peer-review availability.

The main idea here is to gather as much datasets as possible, with an emphasis on dihydrofolate reductase (DHFR) inhibitors (both **human** and from *Plasmodium spp.*). 

The first step is to construct a chemical space (CS) and compare each of the datasets. These are chemical libraries I'm going to try and retrieve any information regarding human and *Plasmodium* DHFR inhibitors:
* ChEMBL
* DrugDB
* ZINC


Process steps:

## Step 1 - Gathering of datasets:
* Gather known human DHFR inhibitors. (in progress)
* Gather known *Plasmodium spp.* DHFR inhibitors. (in progress)
* Gather FDA-approved drugs. (✓)
* Gather other relevant datasets such as NuBBE (brazilian natural products) or other chemical libraries.

## Step 2 - Processing:
* Process/curate all datasets gathered on step 1.

## Step 3 - Calculate descriptors and do Principal Component Analysis:
* Calculate partial descriptors using RDKit for doing the chemical space analysis.
* Exploratory data analysis.
* PCA using scikitlearn or tidyverse.

## Step 4 - Plot Chemical Space 
* Generate all important plots and assess possible clusters.
* Conclusion of Exploratory Data Analysis.
