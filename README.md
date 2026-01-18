# SurakshaAI – Women Safety Risk Prediction (Machine Learning)

## Overview
SurakshaAI is a Machine Learning project that predicts women safety risk levels using a crime dataset.
The model learns patterns from location and time-based features to classify areas/situations as safe or unsafe.

---

## Objective
To train a Machine Learning model that predicts a safety risk category using:
- LAT (Latitude)
- LON (Longitude)
- HOUR (Time of occurrence)

---

## Tech Stack
- Python
- Google Colab
- Pandas
- Scikit-learn

---

## Model Used
- RandomForestClassifier

---

## Accuracy
**Accuracy Score:** 0.6744333291123211 (~67.44%)

---

## Workflow
1. Imported required libraries  
2. Loaded the dataset (`crime_in_la.csv`)  
3. Preprocessed the dataset  
4. Selected features: `LAT`, `LON`, `HOUR`  
5. Split data into train/test sets  
6. Trained model using Random Forest  
7. Evaluated model using accuracy score  
8. Tested prediction on a sample input  

---

## How to Run
### Run on Google Colab
1. Open the notebook in Colab  
2. Upload `crime_in_la.csv` when required  
3. Run all cells  

### Run locally
Install dependencies:
```bash
pip install -r requirements.txt
