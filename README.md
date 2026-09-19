# Effects of Semantic Context on Neural Activation Patterns in CI Users
This repository contains the python script used to process, analyze, and generate cortical activation data + plots in the following manuscript: *Effects of Semantic Context on Neural Activation Patterns in CI Users*. Data can be found in the OSF repository linked here. 

## Requirements:
This script was executed with **Python 3.12** in **Jupyter Notebook**. All necessary libraries and packages are imported within the script, including MNE and MNE-NIRS.

## Scripts:CC
The script titled 'tCCA_script_for_fNIRS_data' is used to run the GLM process including both a short channel and tCCA denoising model. This model was developed in previous work and a more detailed breakdown of it can be found in the manuscript: *Group-level test-retest reliability assessment using systemic physiology augmented functional near-infrared spectroscopy during a passive-listening task*

To run each analysis:
  1. Open the notebook
  2. Run each cell in sequential order

These scripts will: 
  1. Import necessary packages and libraries
  2. Define functions needed to run analyses
  3. Run the GLM process for the full dataset
  4. Create dataframes for contrasts (listening and processing phases of the task) and region of interest (ROI)-level data + corresponding LMEMs
  5. Format the results for plotting ROI-level contrast data


## Data format:
Each script expects fNIRS data in formats such as `.snirf`. Make sure your data is correctly preprocessed and formatted as described in the manuscript before running the notebook. 

Data from the GLM processes are stored in .csv files. A cleaned individual-level contrast data frame has been included in the OSF repository. Contrast data was used for Figures 4-6 

## Citation:
If you use this code in your research, please cite the manuscripts: *Effects of Semantic Context on Neural Activation Patterns in CI Users* and *Group-level test-retest reliability assessment using systemic physiology augmented functional near-infrared spectroscopy during a passive-listening task*

