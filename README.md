# EA FC24 Player Rating Analysis ⚽

## Overview
This notebook analyzes the EA FC24 player rating dataset to model how the game calculates a player's overall score based on their attributes.

## Key Steps 🔑
1. **Data Preprocessing**:
- Handled high cardinality categorical features like 'Nation' and 'Club' to avoid sparse data.
- Replaced 'Club Name' with 'Club Rate' to reduce parameters.

2. **Gender Analysis**:
   - Investigated differences in male and female player distributions and their impact on model performance.

3. **Feature Selection**:
   - Identified top 20 features correlated with the overall score.
   - Used RFE (Recursive Feature Elimination) to select significant features.

4. **Model Development**:
   - Dropped 'Nation' and 'Gender' to prevent bias.
   - Split data into training and test sets.
   - Chose XGBoost for its best performance and optimized hyperparameters.
     
5. **Performance and Error Analysis**:
   - Improved MSE from 0.66 to 0.53.
   - Utilized SHAP graphs for feature importance and individual player score explanations.

## Summary 📝
This project developed a fair and accurate model to predict EA FC24 player ratings by carefully handling categorical data, ensuring bias mitigation, and selecting the best model and features.
