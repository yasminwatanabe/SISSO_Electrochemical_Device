# SISSO_Electrochemical_Device

This repository contains the machine learning code and input files used in the study:

"High-Density Electrochemical Millifluidic Device: a Set of Advances to Enable Anticancer Drug Susceptibility Testing in Daily Practice"

## Repository Contents

### SISSO input files
- `SISSO.in` → Input file containing the configuration used in the study
- `train.dat` → Training dataset (available upon reasonable request)

SISSO code:
https://github.com/rouyang2017/SISSO

### Machine Learning
- `SISSO_High_Density_Electrochemical_Millifluidic_Device.ipynb`  
  Notebook used to:
  - Apply the selected SISSO descriptor 
  - Perform 5-fold cross-validation  
  - Generate predictions  
  - Compute performance metrics (R², MAE, RMSE)

