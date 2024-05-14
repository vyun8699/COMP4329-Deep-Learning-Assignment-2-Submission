# COMP4329-Deep-Learning-Assignment-2-Submission
 Submission Repo for COMP4329 Assignment 2

## Description
This repository contains the submission for COMP4329 Deep Learning Assignment 2.
This repo is ran on Python 3.11.5 or higher. 
All dependencies/library imports are ran in individual ipynb files. 

## ipynb files
All files are annotated as 'SID1_SID2_fileName.ipynb' and can be run top to bottom.
Please not that some files are run on mps and others on cuda due to the team's machine limitation.
device usage shall be annotated below.

Files to be explained by 'fileName' below:
- TransferLearning (mps): this file runs the different combinations of pre-trained models and optimizers.
- layerVisualizer (mps): this file visualizes layers of the best model from transfer learning.
- MixPrec (cuda): this file runs the best model (RegNet AdaDelta) on MixPrecision in CUDA.
- log_to_excel (any): this file aggregates log files to a single excel file for analysis

## other files
- log visualizer: this tableau file is used to create dynamic visualization
- dot_regnet_architecture: layer visualization of the best model (regnet AdaDelta)

## folders
- data: contain all image files and train and test files
- backup: contain other documents
- models: contain logs, csv output, and pth model files