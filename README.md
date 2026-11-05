# working-memory-and-basic-number-processing
Data and analysis files for basic number processing in preschool children


This repository contains the dataset and Mplus analysis files for the manuscript:

**“Differential Contributions of Working Memory Components and Visual Attention to Young Children’s Varieties of Basic Number Processing.”**

## Study Overview

The study involved 110 Chinese children and examined how three components of working memory (phonological loop, visuospatial sketchpad, and central executive) and visual selective attention relate to three basic number-processing abilities:

* Numerosity estimation
* Number line estimation
* Numerical magnitude comparison


## Repository Files

| File                      | Description                                                                                                           

| `data_WMandNUMBER.sav`    | Study dataset in SPSS format. 

| `data_WMandNUMBER.dat`    | Dataset in the format used by Mplus.

| `Path_analysis.inp`       | Mplus syntax for the main multivariate multiple regression analysis using the robust maximum likelihood (MLR) estimator.

| `path_analysis.out`       | Mplus results for the main analysis, reported in the manuscript (Table 3 and Figure 2). 

| `BAYES_Path_analysis.inp` | Mplus syntax for the supplementary Bayesian multivariate multiple regression analysis. 

| `bayes_path_analysis.out` | Mplus results for the Bayesian analysis, reported in the Supplementary Material (Table S1).


## Data and Analysis

The dataset includes demographic variables, cognitive-task scores, and standardized variables. Missing values in the Mplus data file are coded as `999`.

The main analysis estimates the associations of working memory components and visual selective attention with the three number-processing outcomes, controlling for age and gender. The supplementary Bayesian analysis assesses the corresponding model using Bayesian estimation.

The analyses were performed using Mplus 8.3. To reproduce them, place `data_WMandNUMBER.dat` in the same directory as the `.inp` files and run the two Mplus input files. The `.out` files contain the corresponding saved results.


## Data Availability
The study dataset and the analysis files supporting the results reported in the manuscript are provided in this repository.
