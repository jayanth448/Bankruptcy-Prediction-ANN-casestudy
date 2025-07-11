# Bankruptcy-Prediction-ANN-casestudy
Excited to share insights from my recent case study on Bankruptcy Prediction using Artificial Neural Networks!

In this study, I developed a machine learning-based system to predict company bankruptcy by analyzing financial ratios and company characteristics. The goal was to accurately classify firms as bankrupt or non-bankrupt, a critical capability for financial institutions, investors, and policymakers.

Key Highlights:
Dataset: Utilized a dataset of 6819 records with 96 financial attributes, including liquidity, profitability, and leverage ratios, as well as company attributes like total revenue and net income.
Preprocessing: Thorough data preprocessing steps were performed, including ensuring correct data types, handling missing values, feature scaling with StandardScaler, and feature selection based on correlation analysis.
Ensemble Learning: The system leveraged the power of ensemble learning techniques, combining multiple models for improved classification performance and reduced overfitting. The base models used were:
Random Forest Classifier 
LightGBM (Gradient Boosting) 
Extra Trees Classifier 
Stacking Classifier: A Stacking Classifier was implemented, integrating predictions from Random Forest, LightGBM, and Extra Trees into a meta-learner (Logistic Regression) to produce final, enhanced predictions.
Results: The Stacking Classifier achieved an impressive accuracy of approximately 97%, outperforming individual base models (Random Forest: ~94%, LightGBM: ~95%, Extra Trees: ~94%). This demonstrates the effectiveness of ensemble methods in financial risk assessment.
This approach provides valuable insights for assessing risk and making data-driven decisions in the financial sector.

