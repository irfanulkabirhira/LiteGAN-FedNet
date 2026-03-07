# An-Explainable-Hybrid-Ensemble-Framework-for-Imbalanced-Clinical-Stroke-Risk-Prediction
An Explainable Hybrid Ensemble Framework for Imbalanced Clinical Stroke Risk Prediction. This project presents a SMOTE-enhanced RF+Extra Trees ensemble with SHAP &amp; LIME explainability, achieving robust performance across clinical and Kaggle stroke datasets for reliable decision support.



🧠 An Explainable Hybrid Ensemble Framework for Imbalanced Clinical Stroke Risk Prediction

Stroke is a leading cause of mortality and long-term disability worldwide, and early identification of high-risk individuals is critical for effective prevention and clinical intervention. However, stroke prediction using clinical data remains challenging due to severe class imbalance, heterogeneous risk factors, and the lack of transparency in many machine learning models.

This project presents an explainable, imbalance-aware hybrid ensemble framework for clinical stroke risk prediction. The proposed approach integrates Synthetic Minority Over-sampling Technique (SMOTE) with a soft-voting hybrid ensemble of Random Forest and Extra Trees classifiers, designed to improve minority-class (stroke) detection while maintaining strong generalization and stability.

A comprehensive experimental pipeline is implemented, including exploratory data analysis, feature encoding, imbalance handling, large-scale benchmarking of classical and ensemble machine learning models, and rigorous evaluation using recall-sensitive metrics such as F1-score and ROC–AUC. The proposed hybrid model consistently outperforms baseline methods, achieving high accuracy and superior discrimination capability under extreme class imbalance.

To ensure clinical trust and transparency, the framework incorporates Explainable Artificial Intelligence (XAI) techniques. SHAP is used to provide global and local feature importance analysis, while LIME enables instance-level explanations for individual patient predictions. The explanations consistently highlight clinically established risk factors such as age, glucose level, BMI, and hypertension, confirming alignment between model behavior and medical knowledge.

The robustness and generalizability of the framework are validated across multiple real-world datasets, including:

Clinical Stroke Risk Prediction Dataset (Mendeley Data, DOI: 10.17632/2d9332pzfr.2)

Stroke Prediction Dataset (Kaggle)

Across datasets, the hybrid ensemble demonstrates strong performance, achieving up to 99% accuracy while maintaining a favorable balance between sensitivity and specificity. Statistical significance testing, ablation studies, and threshold sensitivity analysis further confirm the reliability of the proposed design.

Overall, this project delivers a clinically interpretable, statistically robust, and deployment-ready stroke risk prediction framework, suitable for real-world healthcare decision-support systems and future multi-center validation studies.

🔑 Key Features

Hybrid Random Forest + Extra Trees ensemble with soft probabilistic voting

SMOTE-based imbalance handling for minority stroke detection

Extensive benchmarking of classical and ensemble ML models

Recall-, F1-score–, and ROC–AUC–oriented evaluation

SHAP (global & local) and LIME (instance-level) explainability

Cross-dataset generalization and robustness validation

📌 Potential Applications

Clinical decision-support systems

Early stroke risk screening

Preventive healthcare analytics

Explainable AI in medical diagnostics
