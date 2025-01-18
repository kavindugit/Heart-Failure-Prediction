📊 Dataset

The dataset, heart_failure_clinical_records.csv, contains the following columns:

    age: Age of the patient (years)
    anaemia: Decrease of red blood cells or hemoglobin (boolean)
    creatinine_phosphokinase: Level of CPK enzyme in blood (mcg/L)
    diabetes: If the patient has diabetes (boolean)
    ejection_fraction: Blood leaving the heart at each contraction (percentage)
    high_blood_pressure: If the patient has hypertension (boolean)
    platelets: Platelets in the blood (kiloplatelets/mL)
    serum_creatinine: Level of serum creatinine (mg/dL)
    serum_sodium: Level of serum sodium (mEq/L)
    sex: Gender (1 for male, 0 for female)
    smoking: Smoking status (boolean)
    time: Follow-up period (days)
    death_event: If the patient died during follow-up (boolean)

🚀 Project Steps

    Data Preprocessing & EDA
        Cleaned the dataset and explored patterns to understand factors influencing heart failure.

    Model Training
        Built and evaluated machine learning models:
            Gaussian Naive Bayes (GaussianNB)
            Support Vector Machine (SVM)
            XGBoost

    Performance Evaluation
        Used metrics like accuracy, precision, and ROC curves to compare models.

🛠️ Tools and Libraries

    Python
    pandas, numpy (Data manipulation)
    matplotlib, seaborn (Visualization)
    scikit-learn (ML models and evaluation)
    XGBoost

📈 Results

    Explored the impact of clinical factors like age, serum sodium, and ejection fraction on heart failure.
    SVM and XGBoost models showed promising results in terms of accuracy and ROC curve performance.

📂 Repository Structure

    notebooks/: Contains the Jupyter notebook(s) for analysis and modeling.
    data/: Dataset used for the project.
    results/: Plots and evaluation metrics.

🌟 Acknowledgements

This project is for learning purposes as part of my machine learning studies.
