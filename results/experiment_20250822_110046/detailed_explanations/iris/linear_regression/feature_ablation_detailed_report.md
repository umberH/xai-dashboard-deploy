# Detailed Explanation Report

**Dataset:** iris  
**Model:** linear_regression  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-22 14:09:53  

## Summary Statistics

- **Total Instances:** 30
- **Valid Explanations:** 30
- **Errors:** 0
- **Model Accuracy:** 1.0000
- **Average Feature Importance:** 0.2108
- **Feature Importance Std:** 0.2238
- **Max Feature Importance:** 0.7435

## Prediction Analysis

- **Correct Predictions:** 30 (100.0%)
- **Incorrect Predictions:** 0 (0.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 3 | 30 | 0.4165 | 100.0% |
| 2 | 30 | 0.3474 | 100.0% |
| 0 | 30 | 0.0671 | 100.0% |
| 1 | 30 | 0.0125 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** -0.021802036940573255
- **Prediction Probabilities:** ['-0.022']
- **Top Features:**
  - Feature 3: 0.6253
  - Feature 2: 0.5422
  - Feature 0: 0.1435

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 1.594678905525389
- **Prediction Probabilities:** ['1.595']
- **Top Features:**
  - Feature 3: 0.3702
  - Feature 2: 0.2480
  - Feature 0: 0.0257

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.8918912024316553
- **Prediction Probabilities:** ['0.892']
- **Top Features:**
  - Feature 3: 0.1276
  - Feature 2: 0.1032
  - Feature 0: 0.0937

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 0.8863871812290878
- **Prediction Probabilities:** ['0.886']
- **Top Features:**
  - Feature 3: 0.1276
  - Feature 2: 0.1032
  - Feature 0: 0.0838

#### Instance 4

- **True Label:** 0.0
- **Prediction:** -0.030704953543304048
- **Prediction Probabilities:** ['-0.031']
- **Top Features:**
  - Feature 3: 0.6253
  - Feature 2: 0.5422
  - Feature 0: 0.1435

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | -0.022 | YES | 3 | 0.6253153798035743 |
| 1 | 2.0 | 1.595 | YES | 3 | 0.3702115930180365 |
| 2 | 1.0 | 0.892 | YES | 3 | 0.12755189339276873 |
| 3 | 1.0 | 0.886 | YES | 3 | 0.12755189339276884 |
| 4 | 0.0 | -0.031 | YES | 3 | 0.6253153798035743 |
| 5 | 1.0 | 1.393 | YES | 3 | 0.2457707214153353 |
| 6 | 0.0 | -0.134 | YES | 3 | 0.6253153798035742 |
| 7 | 0.0 | -0.051 | YES | 3 | 0.6253153798035743 |
| 8 | 2.0 | 1.745 | YES | 3 | 0.494652464620738 |
| 9 | 1.0 | 1.390 | YES | 3 | 0.1835502856139848 |
| 10 | 2.0 | 1.787 | YES | 2 | 0.555332976851213 |
| 11 | 2.0 | 1.866 | YES | 3 | 0.6813137720247899 |
| 12 | 2.0 | 2.001 | YES | 3 | 0.6190933362234394 |
| 13 | 1.0 | 1.281 | YES | 3 | 0.18355028561398457 |
| 14 | 0.0 | -0.055 | YES | 3 | 0.6253153798035743 |
| 15 | 0.0 | -0.073 | YES | 3 | 0.6253153798035743 |
| 16 | 0.0 | -0.228 | YES | 3 | 0.6253153798035743 |
| 17 | 1.0 | 1.012 | YES | 3 | 0.06533145759141812 |
| 18 | 1.0 | 1.306 | YES | 2 | 0.20413425631289672 |
| 19 | 2.0 | 1.583 | YES | 3 | 0.3702115930180365 |
| 20 | 0.0 | -0.109 | YES | 3 | 0.6253153798035743 |
| 21 | 2.0 | 2.057 | YES | 3 | 0.7435342078261407 |
| 22 | 1.0 | 1.172 | YES | 2 | 0.18218433627925168 |
| 23 | 2.0 | 1.517 | YES | 2 | 0.40168353661569944 |
| 24 | 2.0 | 1.976 | YES | 3 | 0.6190933362234394 |
| 25 | 1.0 | 1.495 | YES | 3 | 0.307991157216686 |
| 26 | 1.0 | 1.186 | YES | 2 | 0.13828449621196226 |
| 27 | 0.0 | -0.037 | YES | 3 | 0.5630949440022234 |
| 28 | 2.0 | 1.687 | YES | 2 | 0.37973361658205484 |
| 29 | 0.0 | -0.097 | YES | 3 | 0.6253153798035743 |
