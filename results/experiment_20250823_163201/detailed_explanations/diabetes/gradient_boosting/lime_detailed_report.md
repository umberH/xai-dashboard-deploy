# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** gradient_boosting  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:35:22  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.5393
- **Average Feature Importance:** 0.0506
- **Feature Importance Std:** 0.1692
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 48 (53.9%)
- **Incorrect Predictions:** 41 (46.1%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 83 | 0.1908 | 93.3% |
| 0 | 78 | 0.0555 | 87.6% |
| 1 | 75 | 0.0166 | 84.3% |
| 3 | 75 | 0.0337 | 84.3% |
| 4 | 65 | 0.0175 | 73.0% |
| 8 | 22 | 0.3678 | 24.7% |
| 9 | 14 | 0.0969 | 15.7% |
| 5 | 12 | 0.1240 | 13.5% |
| 6 | 11 | 0.6462 | 12.4% |
| 7 | 10 | 0.0719 | 11.2% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.040', '0.059', '0.902']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.960', '0.033', '0.007']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.321', '0.449', '0.230']
- **Top Features:**
  - Feature 8: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.222', '0.694', '0.084']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 9

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.986', '0.011', '0.003']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.109', '0.187', '0.704']
- **Top Features:**
  - Feature 8: 0.2460
  - Feature 5: 0.1765
  - Feature 7: 0.1375

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.083', '0.216', '0.701']
- **Top Features:**
  - Feature 8: 0.4995
  - Feature 2: 0.4613
  - Feature 6: 0.0393

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.970', '0.026', '0.004']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 2.000 | NO | 8 | 0.2460084477977472 |
| 1 | 0.0 | 2.000 | NO | 8 | 0.4994552671061757 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 8 | 1.0 |
| 6 | 2.0 | 1.000 | NO | 8 | 0.6441230530985478 |
| 7 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 11 | 0.0 | 0.000 | YES | 6 | 1.0 |
| 12 | 0.0 | 0.000 | YES | 6 | 0.8861531248417039 |
| 13 | 2.0 | 0.000 | NO | 2 | 0.6286368954856997 |
| 14 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 15 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 16 | 0.0 | 0.000 | YES | 8 | 1.0 |
| 17 | 0.0 | 1.000 | NO | 2 | 0.7433636461894679 |
| 18 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 2 | 0.5963300498368016 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 0.0 | 0.000 | YES | 8 | 0.5256635393765043 |
| 25 | 2.0 | 1.000 | NO | 2 | 0.374156242731363 |
| 26 | 1.0 | 0.000 | NO | 2 | 0.7041232127373173 |
| 27 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 28 | 2.0 | 2.000 | YES | 3 | 0.3694298184268994 |
| 29 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 2 | 0.4526432586505543 |
| 31 | 2.0 | 2.000 | YES | 2 | 0.34813440833500015 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 0.000 | NO | 6 | 1.0 |
| 34 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 35 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 36 | 1.0 | 1.000 | YES | 8 | 0.6106835262706347 |
| 37 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 1.0 | 0.000 | NO | 3 | 0.41062338696578166 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 2.000 | NO | 3 | 0.3979870423679793 |
| 43 | 2.0 | 1.000 | NO | 3 | 0.3187536642686625 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 0.0 | 2.000 | NO | 0 | 0.0 |
| 46 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 48 | 0.0 | 0.000 | YES | 6 | 1.0 |
| 49 | 1.0 | 0.000 | NO | 2 | 0.5126730175064413 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
