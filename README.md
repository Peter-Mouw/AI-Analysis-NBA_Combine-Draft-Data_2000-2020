# AI Analysis of NBA Combine Draft Data 2000-2020

Author: Peter Mouw  
Date: January 2026


## Overview
Analyze NBA Draft Combine data (2000–2020) to explore correlations between player metrics and draft outcomes.
HTML Report: https://peter-mouw.github.io/AI-Analysis-NBA_Combine-Draft-Data_2000-2020/

**Key Questions:**
1. Which combine metrics most influence draft predictions?  
2. Are these metrics statistically significant for predicting draft outcomes using a Random Forest?


## Data
- Source: [Kaggle NBA Draft Combine Dataset](https://www.kaggle.com/datasets/marcusfern/nba-draft-combine)  
- 1249 entries; metrics include height, weight, wingspan, vertical jumps, agility times, body fat %, bench reps, and draft outcome


## Method
1. Preprocess data (fill missing values, one-hot encode categorical features)  
2. Train Random Forest Classifier (100 trees, 80/20 split)  
3. Evaluate: Accuracy, F1, Confusion Matrix  
4. Extract feature importance & test statistical significance with permutation testing


## Results
- Accuracy: 60.8%, F1 Score: 0.66  
- Top features: Lane Agility Time, Body Fat %, Weight, Max Vertical, Wingspan  
- Permutation test p-value: 0.597 → not statistically significant


## Conclusion
- Combine metrics alone provide limited predictive power for draft outcomes  
- Draft decisions also depend on in-game performance, skill development, and team strategy  
- Lane agility, body fat, and weight are the most influential combine metrics

---

## Report
Detailed analysis, charts, and tables available at:  
[Insert project HTML/interactive report URL here]
