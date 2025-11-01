# Mental Health and Screen Exposure Analysis

 **A Data-Driven Exploration of the Impact of Demographic, Psychophysiological, and Screen Exposure Factors on Mental Health**

---

## Overview
This project investigates how demographic variables, psychophysiological factors (such as stress and sleep quality), and screen exposure duration influence mental health outcomes.  
The analysis uses statistical methods and machine learning models to uncover potential patterns that can support data-informed interventions in mental health and digital well-being.

---

## Objectives
- Examine relationships between demographic, psychophysiological, and behavioral factors with mental health outcomes.
- Assess the role of screen exposure and sleep quality in influencing well-being.
- Develop predictive models using supervised learning techniques to evaluate mental health risk patterns.

---

## Dataset
- **Source:** [Kaggle – Mental Health and Technology Usage Dataset](https://www.kaggle.com/datasets/waqi786/mental-healthand-technology-usage-dataset)
- **Size:** 10,000 participants, 14 variables  
- **Type:** Mixed (categorical, ordinal, and continuous data)

---

## Methodology
1. **Data Collection & Storage:**  
   - Extracted dataset and managed using MySQL via phpMyAdmin.
2. **Data Cleaning & Preprocessing:**  
   - Verified null values, outliers, and inconsistent data types.
   - Encoded categorical and ordinal variables.
3. **Exploratory Data Analysis:**  
   - Visualized distributions using histograms and bar plots.
   - Conducted correlation analysis with Spearman’s Rank Correlation.
4. **Statistical Testing:**  
   - Applied Chi-square tests and ordinal logistic regression.
5. **Machine Learning Models:**  
   - Trained and evaluated:
     - Random Forest Classifier  
     - Support Vector Machine (SVM)  
     - XGBoost  
     - LightGBM  
   - Compared model performance based on accuracy, ROC, and AUC.

---

## Tools & Technologies
`Python` · `MySQL` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `SciPy` · `Scikit-learn` · `XGBoost` · `LightGBM`  

---

## Key Findings
- No significant linear or monotonic correlations were found between screen exposure and mental health.  
- “Support System Access” was the only variable with a statistically significant relationship to mental health outcomes.  
- All machine learning models achieved modest accuracies (~23–25%), suggesting the need for deeper feature engineering and more representative datasets.

---

## Challenges & Learnings
- Handling mixed-type (ordinal, categorical, and continuous) data required careful model selection.
- Normality assumptions influenced test choice (non-parametric vs parametric).
- Discovered the importance of data quality, feature selection, and model interpretability in health analytics.

---

## Results Summary
| Model | Accuracy (%) | Key Insight |
|--------|---------------|-------------|
| Random Forest | 24.3 | Moderate pattern capture |
| XGBoost | 23.1 | Slightly better precision |
| LightGBM | 25.0 | Efficient but limited interpretability |
| SVM | 24.7 | Linear separation not effective |

---

## Author
**Bhavana Devi Korlagunta**  
Master’s Student in Health Informatics, Indiana University – Indianapolis  
Passionate about Health Data Analytics, Clinical Decision Support, and Digital Health Research  
[LinkedIn](https://www.linkedin.com/in/bhavana-devi-korlagunta-490352234/) · [Email](mailto:bhavanadevikorlagunta@gmail.com)

---

## Keywords
`Mental Health` · `Screen Time` · `Data Analytics` · `Machine Learning` · `Health Informatics` · `Python` · `MySQL`
