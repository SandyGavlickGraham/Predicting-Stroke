# Predicting-Stroke

In this project, I used machine learning to predict strokes in patients based on characteristics including:
- gender
- age
- hypertension
- heart_disease
- ever_married
- work_type (type of occupation)
- Residence_type (Urban/ Rural)
- avg_glucose_level (measured after meal)
- bmi
- smoking_status (except that 30% of this column was missing so I dropped it)

The proportion of observations in the data that contained data for stroke patients was disproportionately low, so I used SMOTE (Synthetic Minority Over-sampling Technique) to create synthetic data to balance the sample.

After checking features for correlation, I used a logistic regression model and evaluated it using the AUC-ROC score.

## Author:
Sandy Graham