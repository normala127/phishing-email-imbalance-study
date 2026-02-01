# phishing-email-imbalance-study

# Imbalanced Phishing Email Classification (Exploratory Study)

This repository contains code and a technical report for an exploratory study on phishing email classification using classical machine learning models under extreme class imbalance.

The project focuses on understanding how different imbalance-handling strategies affect minority class detection rather than achieving state-of-the-art performance.

## Project Context
This work was originally conducted as part of a university course project and is shared here for educational and reproducibility purposes.  
The report has not been peer-reviewed and should be considered an exploratory analysis.

## Methods Overview
The study evaluates two commonly used classification models:
- Complement Naive Bayes
- Logistic Regression

Several strategies for handling class imbalance are examined, including:
- Class weight adjustment
- Synthetic Minority Oversampling Technique (SMOTE)
- Random undersampling
- Hybrid approaches
- Feature engineering using interaction terms

Evaluation prioritizes recall and F1-score for the minority (phishing) class, highlighting the limitations of accuracy in highly imbalanced datasets.

## Dataset
The experiments use the *Email Phishing Dataset* by Ethan Cratchley, available on Kaggle and released under the Apache 2.0 license.  
The dataset consists of engineered numerical features derived from email content and does not include raw email text.

## Notes
This repository represents a preliminary exploration of imbalanced classification techniques.  
Future extensions could include additional models, threshold optimization, and validation across multiple datasets.
