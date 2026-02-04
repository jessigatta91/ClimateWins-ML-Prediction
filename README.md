# ClimateWins-ML-Prediction

ML analysis of European weather data to predict climate patterns

---

## Project Overview
ClimateWins uses machine learning to analyze historical weather data from 18 European weather stations. The goal is to predict extreme events and day-to-day weather conditions, while addressing ethical concerns such as regional biases, anonymization, and responsible use of predictions. This project demonstrates ML modeling, optimization, and predictive analytics on climate data.

---

## Folder Structure
- `data/` - raw and processed datasets from European weather stations  
- `notebooks/` - Jupyter notebooks for gradient descent, KNN, Decision Tree, and ANN analysis  
- `scripts/` - Python scripts for automation or running models  
- `outputs/` - visualizations, charts, and results  
- `presentation/` - final stakeholder-ready slides  
- `requirements.txt` - Python dependencies  

---

## Datasets
- Historical weather data (temperature, wind, snow, radiation, etc.)  
- Data ranges from late 1800s to 2022, collected by the European Climate Assessment & Data Set project  

---

## Methodology
1. **Data Preprocessing:** Cleaning, scaling, and anonymizing station data  
2. **Exploratory Data Analysis:** Understanding trends and distributions  
3. **Gradient Descent:** Modeling temperature trends over decades  
4. **Supervised ML Models:** KNN, Decision Tree, ANN to predict pleasant/unpleasant days  
5. **Evaluation:** Confusion matrices, accuracy assessment, and model comparison  
6. **Ethical Considerations:** Bias mitigation, anonymization, and human oversight  

---

## Key Insights
- Gradient Descent converges reliably across climates and stations  
- ANN (Scenario 3) performs best overall in predicting pleasant days  
- Winter minimum temperatures show a long-term warming trend across Europe  
- Regional biases in historical data need careful consideration to ensure fairness  

---
