# Chronic Kidney Disease Prediction

This repository contains a project aimed at predicting the stages of Chronic Kidney Disease (CKD) using patient data. The dataset includes various medical attributes of patients which are used to train machine learning models for classification purposes.

## Table of Contents

- [Problem Statement](#problem-statement)
- [Solution Approach](#solution-approach)
- [Dataset Information](#dataset-information)
- [Model Performance](#model-performance)
- [Instructions](#instructions)
- [Results and Conclusion](#results-and-conclusion)
- [Future Work](#future-work)
- [License](#license)

## Problem Statement

To predict the stage of Chronic Kidney Disease (CKD) in patients based on various medical attributes. The goal is to assist healthcare professionals in early detection and treatment planning.

## Solution Approach

1. **Exploratory Data Analysis (EDA)**: Understand the dataset, visualize distributions, and identify correlations.
2. **Data Preprocessing**: Handle missing values, encode categorical features, and scale numerical features.
3. **Model Building**: Train multiple classification models including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.
4. **Model Evaluation**: Evaluate models using metrics like accuracy, precision, recall, and F1 score.
5. **Hyperparameter Tuning**: Optimize model performance using Grid Search and Cross-Validation.
6. **Feature Importance**: Analyze and visualize the importance of different features in predicting CKD.

## Dataset Information

**Title**: Early stage of Indians Chronic Kidney Disease (CKD)

**Source Information**:
- Dr. P. Soundarapandian, M.D., D.M (Senior Consultant Nephrologist, Apollo Hospitals, Managiri, Madurai Main Road, Karaikudi, Tamilnadu, India)
- Creator: L. Jerlin Rubini (Research Scholar, Alagappa University, Email: jel.jerlin@gmail.com, Contact: +91-9597231281)
- Guided by: Dr. P. Eswaran (Assistant Professor, Department of Computer Science and Engineering, Alagappa University, Karaikudi, Tamilnadu, India, Email: eswaranperumal@gmail.com)
- Date: July 2015

**Attributes**: 24 medical attributes plus class label (25 total)

**Number of Instances**: 400 (250 CKD, 150 not CKD)

**Missing Values**: Yes (denoted by "?")

## Model Performance

The models are evaluated on various performance metrics:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

The performance metrics will help in determining the effectiveness of the models in predicting CKD stages.

## Results and Conclusion

The model provides a classification of patients into CKD and non-CKD categories based on their medical attributes. The detailed results and performance metrics are documented in the notebook.

### Insights:
- Early detection of CKD can significantly improve treatment outcomes.
- Certain attributes such as blood pressure, serum creatinine, and hemoglobin levels are crucial in predicting CKD.

### Recommendations:
1. Incorporate regular screening for high-risk patients.
2. Utilize the model to assist healthcare professionals in diagnosis and treatment planning.
2. Explore other advanced classification techniques.
3. Implement model deployment for real-time CKD prediction in healthcare settings.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
