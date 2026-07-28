# Cycling Sensor Analysis Project

This repository contains a Jupyter notebook for analyzing cycling sensor data and estimating power output from different sensor sources.

## Overview

The main notebook processes data from cycling experiments and compares estimated power values against reference values from TCX or CSV files. The workflow includes:

- loading sensor data
- cleaning and aligning timestamps
- filtering and preprocessing signals
- estimating power from piezo or force-related measurements
- comparing results with ground truth data

## Data Folders

- Data_Files/: example data and converted files
- HMD/: main measurement files used in the notebook


## How to Run

1. Install the required Python packages:
   - pandas
   - numpy
   - plotly
   - scipy
   - dtaidistance

2. Run the cells in order.

3. The notebook will generate plots and evaluation metrics such as correlation and error values.

## Notes

- The notebook expects the project folder structure to stay intact.
- Data files are referenced relatively, so the files should remain in the same folders as provided.
- Some cells depend on specific files from the HMD folder.
