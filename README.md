# Kaggle Competition: ISIC 2024 - Skin Cancer Detection with 3D-TBP

## Competition Overview

The **ISIC 2024 - Skin Cancer Detection with 3D-TBP** competition is hosted on Kaggle. This repository contains the code and models developed for this competition.

### Objective

This project focuses on developing image-based algorithms to identify histologically confirmed skin cancer from 3D total body photos (TBP), resembling smartphone-quality images. The goal is to create a binary classifier that aids early skin cancer detection in settings without specialized care, thereby improving triage.

### Background

Early detection of skin cancer is crucial, yet many individuals lack access to dermatologic care. While AI algorithms have shown promise in diagnosing melanoma, basal cell carcinoma, and squamous cell carcinoma, there is still untapped potential in identifying which individuals require clinical attention. This project leverages a dataset of single lesions from TBP images, presenting the challenge of distinguishing malignant from benign lesions using lower-quality images often found in non-clinical settings.

### Evaluation Metric

Submissions are evaluated based on the partial area under the ROC curve (pAUC), with a focus on true positive rates (TPR) above 80%. This ensures that algorithms meet the sensitivity required for effective clinical practice. Scores range from [0.0, 0.2].

### Model

- **Model:** Ensemble Method (XGBoost, CatBoost, LGBM)
- **Achievement:** Bronze Solution

This repository includes the code and models developed for this competition. For detailed implementation and further instructions, please refer to the provided code.

## Competition Details

- **Period:** June 2024 - September 2024
