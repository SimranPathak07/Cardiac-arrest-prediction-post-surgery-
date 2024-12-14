# Cardiac Arrest Prediction System (Post-Surgery)

This project focuses on developing a predictive system to assess the likelihood of cardiac arrest in patients following surgery. By analyzing real-time ECG data and patient vitals, the system can detect early signs of instability and alert medical staff for timely intervention.

## Overview

The system uses advanced ECG signal processing algorithms to detect key features in heart rhythms and integrate machine learning models to predict the risk of cardiac arrest post-surgery. Continuous monitoring devices, including ECG patches and vital sign monitors, are employed to track patient health in real time. 

## Key Features

- **ECG Signal Processing**: Implemented algorithms such as **Pan-Tompkins** and **Wavelet Transform** to detect critical features like **QRS complexes**, **P-waves**, and **T-waves**. This helps monitor heart rate, rhythm, and early signs of abnormal heart conditions.
  
- **Machine Learning Integration**: Utilized **Random Forest** and **Support Vector Machine (SVM)** models to predict the likelihood of cardiac arrest based on:
  - Patient demographics
  - Surgery type and details
  - Comorbidities and pre-existing conditions
  - Real-time vitals and ECG data
  
- **Noise Reduction Techniques**: Incorporated noise reduction and hybrid methods (e.g., **Hilbert Transform**) to improve signal quality, ensuring accurate heart activity detection even in noisy environments or with signal interference.

- **Continuous Monitoring**: Used wearable devices like **ECG patches** and **vital sign monitors** to continuously track heart activity after surgery and alert medical personnel in case of abnormal readings.

- **Evaluation and Tuning**: Evaluated and fine-tuned the prediction model using standard clinical datasets (e.g., **MIT-BIH** database) and patient-specific data to ensure robust and reliable performance.


