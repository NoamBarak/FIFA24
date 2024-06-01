# EA FC24 Player Rating Analysis ⚽

## Overview
This notebook analyzes the EA FC24 player rating dataset to model how the game calculates a player's overall score based on their attributes.

## Key Steps 🔑
1. **Data Preprocessing**:
   - Handled high cardinality categorical features to avoid sparse data.

2. **Gender Analysis**:
   - Investigated differences in male and female player distributions and their impact on model performance.

3. **Feature Selection**:
   - Identified top 20 features correlated with the overall score.
   - Used RFE (Recursive Feature Elimination) to select significant features.

4. **Model Development**: 
   - Dropped 'Nation' and 'Gender' to prevent bias.
   - Chose XGBoost for its best performance and optimized hyperparameters.
     
5. **Performance and Error Analysis**:
   - Improved MSE from 0.66 to 0.53.
   - Utilized SHAP graphs for feature importance and individual player score explanations.


## Summary 📝

✅ Ensured fairness by excluding biased features.\n
✅ Achieved high accuracy with XGBoost.\n
✅ Provided actionable insights through SHAP analysis.\n
✅ Successfully developed a fair and robust model for EA FC24 player ratings.
