# File Description :

toxicity_prediction_pipeline.ipynb → Main machine learning workflow \

Peptide_Property_Calculation_by_R.ipynb → Peptide feature extraction using R

project_report_peptide_toxicity.pdf → Full project report

peptide.csv → Input peptide dataset

# Peptide Toxicity Prediction using Ensemble Machine Learning

### Machine Learning Course Project 

This project builds a machine learning pipeline to classify peptide sequences as toxic vs non-toxic using sequence-derived physicochemical features and ensemble learning methods. The goal is to support safe therapeutic peptide discovery by identifying toxicity patterns from peptide sequence data.


## Project Overview

Peptide toxicity prediction is an important step in peptide drug development.
In this project, multiple machine learning classifiers and a Super Learner ensemble framework were applied to predict peptide toxicity from sequence-based features.

Dataset characteristics:

Total peptide sequences: 3864 \
Balanced dataset (toxin vs non-toxin) \
Input format: FASTA \
Converted to CSV for analysis \
Extracted 438 physicochemical features from peptide sequences \

## Methodology

Extract physicochemical features from peptide sequences \
Perform dataset preprocessing and cleaning \
Apply stratified cross-validation \
Train multiple machine learning classifiers \
Select important features using XGBoost feature importance \
Optimize hyperparameters for best classifier performance \
Build a Super Learner ensemble stacking model \
Compare ensemble performance with individual classifiers \

## Results

Best performance achieved using Super Learner Ensemble Model \

Accuracy: 91.55% \
Matthews Correlation Coefficient (MCC): 0.83 \

The ensemble model performed better than the individual XGBoost classifier for toxicity prediction. \


## Tools and Technologies

Python \ 
R \ 
Scikit-learn \
XGBoost \
Super Learner Ensemble \
Bio.SeqUtils.ProtParam \
Peptides (R package) \
Protr (R package) \
VS Code
