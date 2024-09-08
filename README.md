# Kaggle Competition: ISIC 2024 - Skin Cancer Detection with 3D-TBP

Period: Jun. 2024 - Sep. 2024

# Competition Outline

## Overview

This project focuses on developing image-based algorithms to identify histologically confirmed skin cancer from 3D total body photos (TBP), resembling smartphone-quality images. The goal is to create a binary classifier that aids early skin cancer detection in settings without specialized care, improving triage.

## Background

Early detection of skin cancer is crucial, but many lack access to dermatologic care. AI algorithms have helped diagnose melanoma, basal cell, and squamous cell carcinoma, but there's untapped potential in determining which individuals need clinical attention. This project uses a dataset of single lesions from TBP images, offering the challenge of distinguishing malignant from benign lesions with lower-quality images often found in non-clinical settings.

## Evaluation

Submissions are scored on the partial area under the ROC curve (pAUC), focusing on true positive rates (TPR) above 80%. This ensures algorithms meet the sensitivity required in clinical practice. Scores range from [0.0, 0.2].

# Model
Model: Ensemble Method (XGBoost, CatBoost, LGBM)
