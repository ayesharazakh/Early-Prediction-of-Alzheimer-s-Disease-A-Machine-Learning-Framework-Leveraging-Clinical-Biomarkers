<img width="1021" height="592" alt="Screenshot 2025-09-19 234016" src="https://github.com/user-attachments/assets/ef032e85-ab26-4dd8-b598-b34a6dcad783" />
<img width="742" height="616" alt="Screenshot 2025-09-19 233632" src="https://github.com/user-attachments/assets/8659b70f-e233-4cdc-a38d-dde47511ea27" />
<img width="766" height="685" alt="Screenshot 2025-09-19 233605" src="https://github.com/user-attachments/assets/50510d04-eb22-4579-8721-a2a37798862a" />
# Early-Prediction-of-Alzheimer-s-Disease-A-Machine-Learning-Framework-Leveraging-Clinical-Biomarkers
A machine learning analysis of Alzheimer's biomarkers using clinical data from 2,149 patients. Gradient Boosting achieved 95% accuracy in prediction. SHAP interpretation identified key clinical factors. Supports early detection approaches in neurodegenerative disease care.

## Project Overview

The goal of this project is to develop a predictive model for Alzheimer's Disease using clinical and lifestyle biomarkers from a dataset of 2,149 patients. The analysis compares multiple machine learning algorithms to identify the most effective approach for early detection.

## Dataset

- **Source:** Publicly available Alzheimer's Disease dataset
- **Samples:** 2,149 patient records
- **Features:** 35 clinical biomarkers including:
  - MMSE (Mini-Mental State Examination) scores
  - Demographic data (Age, Gender)
  - Cardiovascular health metrics
  - Lifestyle factors (Physical activity, Diet quality)
  - Medical history (Diabetes, Hypertension)

### Models Evaluated
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- XGBoost Classifier

## Results

The Gradient Boosting classifier demonstrated the best performance:
- **Accuracy:** 95%
- **F1-Score:** 0.93 (Alzheimer's class)
- Key predictive features identified through SHAP analysis:
  - MMSE scores
  - Age
  - Cardiovascular metrics
  - Functional assessment scores

## Key Findings
- Gradient Boosting emerged as the optimal model with 95% accuracy and 0.93 F1-score for Alzheimer's detection
- Tree-based models significantly outperformed traditional logistic regression (95% vs 79% accuracy)
- The most predictive features aligned with known clinical markers of Alzheimer's progression
- The model shows strong potential as a decision-support tool for early intervention


## Clinical Relevance:
This predictive tool could assist clinicians in:
- Identifying high-risk patients for earlier neurological referral
- Prioritizing costly diagnostic workups (PET/MRI) for those most likely to benefit
- Monitoring disease progression through longitudinal biomarker tracking
- Reducing time-to-diagnosis by flagging subtle patterns in routine clinical data

## Future Research Directions:
- Integration with neuroimaging data (MRI, PET scans) for multimodal prediction
- Validation on larger, multi-center cohorts to ensure generalizability
- Development of a real-time clinical decision support system interface
- Exploration of time-to-conversion prediction in Mild Cognitive Impairment (MCI) patients
- Investigation of feature importance shifts across different disease stages

##  Author
Ayesha Razakh

Third Year MBBS Student
