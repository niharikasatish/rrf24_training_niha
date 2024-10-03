
---
"TANZANIAN CONDITIONAL CASH TRANSFER PROJECT" //
Author: Niharika Satish //
Date: 3rd October 2024
---

- This README template is designed to be included in reproducibility packages to provide directions for replicating the results in the research paper.

## Contents

1. [Overview](#overview)
2. [Data Availability](#data-availability)
3. [Instructions for Replicators](#instructions-for-replicators)
4. [Requirements](#requirements)

The rest of the contents of this README file is highly desirable, but not strictly needed for reproducibility. The points above are needed.

5. [Folder Structure](#folder-structure)


## Overview

The aim of this reproducibility package is to present analysis on a Tanzanian Conditional Cash Transfer Programme. All of the data, code and Stata packages needed are in this package. 

## Data Availability

This section will outline where and how the data supporting the findings of the study can be accessed and used. Some of the data used in this study was collected using a survey. All personal identifiers have been removed. However, this survey data cannot be made publicly available due to privacy concerns. Data from Open Street Maps have also been used and this is publicly available to all. 


### Data Sources

You can use the following as a template. Make sure to fill out this information for each of the data files used:

- **(1) TZA_amenity:** 

- **Source:** Open Street Maps

- **(2) TZA_CCT_baseline:** 

- **Source:** Survey Data

- **(3) treat_status:** 

- **Source:** Survey Data

## Instructions for Replicators

New users should follow these steps to run the package successfully:
- Users must first have access to all data files if they are not included in the reproducibility package. They should go to the mentioned links, download the listed files, and place them in the data folder.
- Update the following files with your directory paths

  - `main_dofile.do`
- Ensure all required software and dependencies are installed as listed in the [Requirements](#requirements) section.

- Run the `main_dofile.do` file.

## Requirements

### Computational Requirements

Please use STATA Version 18.0 to get the best results.

### Software Requirements

- **Stata version 18**

  - ietoolkit 
  - iefieldkit 
  - winsor 
  - sumstats 
  - estout 
  - keeporder 
  - grc1leg2 

### Memory and Runtime and Storage Requirements

Runtime is 5 mins. 

## Folder Structure

Folder structure is as follows:

```
Data
  ├── Raw
  └── Intermediate
  └── Final
Code
  ├── Main_dofile.do
  ├── 01_processing-data.do  
  ├── 02_constructing-data.do
  └── 03_analyzing-data.do
Outputs
  

```
