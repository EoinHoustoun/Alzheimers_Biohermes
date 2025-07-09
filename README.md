# Alzheimer's Disease Classification with Digital Biomarkers
## Abstract
Alzheimer’s Dementia (AD) is a progressive neurodegenerative disorder with clinical stages ranging from cognitively normal (CN) to mild cognitive impairment (MCI) and mild Alzheimer’s Dementia (AD). Accurate classification of these stages is critical for early intervention and treatment planning, and AD risk prediction is also important for patient stratification. This work explores the predictive capabilities of machine learning models using a combination of digital biomarkers from the Bio-Hermes study. Five models—Logistic Regression, Elastic Net, Random Forest, Gradient Boosting, and XGBoost—were evaluated on a 20% test set after being trained or hyperparameter-tuned using repeated cross-validation, on an 80% training set. XGBoost achieved the best overall performance with an AUC of 0.815 followed closely by Gradient Boosting (AUC = 0.806). The findings highlight the potential of ensemble methods like XGBoost for the prediction of Alzheimer’s clinical stages and risk of AD, with digital biomarkers proving to be valuable while non-invasive and inexpensive to produce predictors. This is an important aspect in the economy of a very expensive and challenging to diagnose, treat, and evaluate risk for, medical condition such as Dementia.	 

## Summary

- Built models to classify cognitive stages: Cognitively Normal, Mild Cognitive Impairment, Mild AD  
- Techniques: XGBoost, Monte Carlo CV, Random Forest, Feature Selection  
- Presented at the [AIAI 2025 conference](https://ifipaiai.org/2025/)
- Published in [Artificial Intelligence Applications and Innovations (Springer)](https://link.springer.com/chapter/10.1007/978-3-031-96235-6_5)
- Dataset: Bio-Hermes (not publicly available)

## Technologies Used

- Python, scikit-learn, XGBoost, pandas, matplotlib  
- Monte Carlo cross-validation (200 iterations)

## Results

- XGBoost achieved highest accuracy and F1-score across all classes  
- Assessed importance of digital biomarkers
- [Results here](https://link.springer.com/chapter/10.1007/978-3-031-96235-6_5)

## Files

- Code available upon request

## Preview

<img src="docs/assets/preview.png" width="500"/>

