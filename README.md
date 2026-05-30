# crop_disease_predictor.py
ML model predicting crop disease risk from soil and  weather conditions using Random Forest. Full pipeline —  data preprocessing, model training, evaluation and  prediction. 85%+ accuracy. No API key needed.
# Crop Disease Risk Predictor
**Built by: Aadish Garg** | Python · Scikit-learn · Pandas · NumPy

## What This Does
A machine learning model that predicts whether a crop is at 
risk of disease based on environmental and soil conditions. 
Takes inputs like temperature, humidity, rainfall, soil pH, 
and nitrogen levels — and predicts Low Risk or High Risk.

## Pipeline
1. Generates 1000+ realistic crop/weather data records
2. Cleans and preprocesses data (encoding, train/test split)
3. Trains a Random Forest classifier (100 trees)
4. Evaluates model — accuracy, precision, recall, F1 score
5. Shows top factors affecting disease risk
6. Predicts disease risk for any new crop input

## How to Run
pip install pandas numpy scikit-learn
python crop_disease_predictor.py

## No API key needed — runs fully offline

## Sample Output
Model Accuracy: 85%+

Top Factors:
humidity_pct     ████████████  0.24
temperature_c    ██████████    0.19
rainfall_mm      █████████     0.17

## Tech Stack
- Python
- Scikit-learn (Random Forest)
- Pandas
- NumPy

## Crops Covered
Wheat, Rice, Maize, Cotton, Soybean

## Resume Line
Built a crop disease risk prediction model using Random 
Forest on 1000+ agricultural records. Implemented full ML 
pipeline — preprocessing, training, evaluation, and 
prediction. Achieved 85%+ accuracy.
