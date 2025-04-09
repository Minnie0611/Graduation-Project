### Project Title: A Machine Learning Diabetes Prediction Framework Based on Explainable Artificial Intelligence

Author: Li Xirui

Supervisor: Dr. Ifede Parfait Tebe

Abstract:

This project aims to develop a diabetes prediction framework based on machine learning, which integrates two base models and an Explainable Artificial Intelligence (XAI) technique to improve prediction performance and enhance the interpretability of the results. The framework uses a stacking method to combine the two base models, CatBoost and XGBoost, with Logistic Regression as the meta-classifier. SHAP is used as the XAI technique to provide explanations for the predictions.

### Key Achievements:

1. **Improved Prediction Performance**: The ensemble model achieved an accuracy of 88.93% on the test set, outperforming all base models, proving its effectiveness in handling complex medical datasets.
2. **Enhanced Interpretability**: SHAP analysis revealed that HbA1c levels and blood glucose levels are the most critical features affecting diabetes risk, followed by age and BMI. This provides healthcare professionals and patients with an understanding of the predictions, enhancing the credibility of AI in healthcare.

### Dataset:

The project used a publicly available diabetes dataset from Kaggle, containing 100,000 samples and 8 features:

- Gender
- Age
- Hypertension
- Heart disease
- Smoking history
- BMI
- HbA1c levels
- Blood glucose levels

### Tech Stack:
Programming Language: Python (3.9.19)  
Development Environment: Visual Studio Code  
Libraries: Pandas, Scikit-learn, Imblearn, Matplotlib, Seaborn, Joblib, Shap

## File Structure:
3069898(CSCU9Z7)_2024-25 Final Dissertation.docx: The final dissertation for this project, including research background, methodology, results, and discussion.

### Operating Environment:
Operating System: Windows 11  
Processor: Intel Core i9  
Memory: At least 16GB

### Running Steps:
1. Install the required Python libraries: `pip install pandas scikit-learn imblearn matplotlib seaborn joblib shap`
2. Import the dataset and execute the preprocessing steps.
3. Train the base models and ensemble model.
4. Evaluate the models using the test set.
5. Perform interpretability analysis using SHAP.

### Future Work:

- Explore advanced techniques like Bayesian optimization for hyperparameter tuning to avoid overfitting and improve model performance.
- Further fine-tune regularization parameters to benefit from hyperparameter optimization while maintaining model generalization.
- Apply techniques like "early stopping" to enhance model stability.

### Contact Information:

If you have any questions or suggestions, please contact the author, Li Xirui.
