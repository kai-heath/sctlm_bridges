# SCTLM-Bridges

## Overview

This is the github for my SCRNA work

This is a cleaned up version of my other github project, with better annotation, and more clear workflow
All figures and data presented have been made using these scripts
Raw data isn't included here but can be found in the following papers:

Prodzynski Data: https://pubmed.ncbi.nlm.nih.gov/39009604/

Galdos Data: https://pubmed.ncbi.nlm.nih.gov/37284748/

Kanemaru Data (also just the heart cell atlas): https://www.nature.com/articles/s41586-023-06311-1

## Organization
Workflow is divided into 3 subfolders
rawFileProcess processes raw data from the above 3 sources (QC control, file conversion, etc)
integration takes the 3 sources, and merges them together, and performs dimension reduction
figureCode has the figure making script and also the script for cluster marker identification
Also all the code is in the ".pynb" files
