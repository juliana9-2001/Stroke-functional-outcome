<img width="1366" height="572" alt="image" src="https://github.com/user-attachments/assets/a9648073-5aac-4fe2-974f-b2fbc602f3ed" /># Stroke Functional Outcome Prediction (Ordinal ML)

## Note: This repository contains the baseline comparative models (XGBoost). The advanced multimodal fusion framework (LightGBM + 3D-CNN) mentioned in my current research is currently unpublished/under preparation and will be released upon publication.

XGBoost-based dual-head pipeline for ordinal prediction of post-stroke functional outcome (e.g. mRS), alongside stroke subtype classification.

## Key Features
- Ordinal classification framework for functional outcome prediction
- Dual-head modeling:
  - Stroke subtype (ischemic vs hemorrhagic)
  - Ordinal mRS outcome
- Handles class imbalance
- Stratified cross-validation
- Python, XGBoost, Scikit-learn

## Data
Clinical and imaging-derived features from an acute stroke cohort (ICPSR).

## Purpose
Academic research in computational neurology (MS-level research project)
