# COMP4329-Deep-Learning-Assignment-2-Submission
 Submission Repo for COMP4329 Assignment 2

## Description
This repo is ran on Python 3.11.5 or higher. 
All dependencies/library imports are ran in individual ipynb files. 

## how to run best model
Option 1: use the colab file provided in the report  
Option 2: run '500543568_530454874_MixPrec.ipynb' after cloning this repo.  

## ipynb files
All files are annotated as 'SID1_SID2_fileName.ipynb' and can be run top to bottom.
Please not that some files are run on mps and others on cuda due to the team's machine limitation.

Files to be explained by 'fileName' and device  usage annotated in brackets ('') below:
- TransferLearning (mps): runs combinations of pre-trained models and optimizers.
- layerVisualizer (mps): loads the best model and visualizes it's layers.
- MixPrec (cuda): re-trains the best model (RegNet AdaDelta) with MixPrecision on CUDA.
- MixPrec_Colab (cuda): the same as MixPrec, with a data download command line. Run on Colab.
- log_to_excel (any): aggregates log files to a single excel file for analysis.

## other files
- log visualizer: tableau file (.twb) used to create dynamic visualization, use link in report to access HTML version.
- dot_regnet_architecture: layer visualization of the best model (regnet AdaDelta)

## all model output (including the best model prediction output)
- All output can be accessed in models/output/final
- The best model is saved in models/output/final/regnetMixPrec_Adadelta_0.01.csv
- Predicted_labels.txt is saved in the root directory. This file is the same as the best model csv above.

## folders
- data: contain all image files and train and test files
- backup: contain other documents (e.g. excel file used for report)
- models: contain logs, csv output, and pth model files
