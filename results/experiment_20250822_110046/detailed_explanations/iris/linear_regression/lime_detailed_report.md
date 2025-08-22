# Detailed Explanation Report

**Dataset:** iris  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:09:51  

## Summary Statistics

- **Total Instances:** 30
- **Valid Explanations:** 30
- **Errors:** 0
- **Model Accuracy:** 1.0000
- **Average Feature Importance:** 0.2500
- **Feature Importance Std:** 0.3334
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 30 (100.0%)
- **Incorrect Predictions:** 0 (0.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 30 | 0.3113 | 100.0% |
| 0 | 30 | 0.0363 | 100.0% |
| 2 | 30 | 0.2539 | 100.0% |
| 3 | 30 | 0.3985 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** -0.021802036940573255
- **Prediction Probabilities:** ['-0.022']
- **Top Features:**
  - Feature 1: 1.0000
  - Feature 0: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 1.594678905525389
- **Prediction Probabilities:** ['1.595']
- **Top Features:**
  - Feature 3: 0.5844
  - Feature 2: 0.3823
  - Feature 0: 0.0327

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.8918912024316553
- **Prediction Probabilities:** ['0.892']
- **Top Features:**
  - Feature 3: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 0.8863871812290878
- **Prediction Probabilities:** ['0.886']
- **Top Features:**
  - Feature 2: 0.6665
  - Feature 3: 0.3335
  - Feature 0: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** -0.030704953543304048
- **Prediction Probabilities:** ['-0.031']
- **Top Features:**
  - Feature 1: 1.0000
  - Feature 0: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | -0.022 | YES | 1 | 1.0 |
| 1 | 2.0 | 1.595 | YES | 3 | 0.5844293127201232 |
| 2 | 1.0 | 0.892 | YES | 3 | 1.0 |
| 3 | 1.0 | 0.886 | YES | 2 | 0.6664755155190957 |
| 4 | 0.0 | -0.031 | YES | 1 | 1.0 |
| 5 | 1.0 | 1.393 | YES | 3 | 0.614085619705545 |
| 6 | 0.0 | -0.134 | YES | 1 | 1.0 |
| 7 | 0.0 | -0.051 | YES | 1 | 1.0 |
| 8 | 2.0 | 1.745 | YES | 3 | 0.6710777270638371 |
| 9 | 1.0 | 1.390 | YES | 3 | 0.6051165693805978 |
| 10 | 2.0 | 1.787 | YES | 3 | 0.6503525533032393 |
| 11 | 2.0 | 1.866 | YES | 3 | 0.6657265172006548 |
| 12 | 2.0 | 2.001 | YES | 3 | 0.6732609752777423 |
| 13 | 1.0 | 1.281 | YES | 3 | 0.5477741242647415 |
| 14 | 0.0 | -0.055 | YES | 1 | 1.0 |
| 15 | 0.0 | -0.073 | YES | 1 | 1.0 |
| 16 | 0.0 | -0.228 | YES | 0 | 0.652716011883916 |
| 17 | 1.0 | 1.012 | YES | 2 | 0.9697364113859226 |
| 18 | 1.0 | 1.306 | YES | 3 | 0.5027920951075489 |
| 19 | 2.0 | 1.583 | YES | 2 | 0.5579422858075758 |
| 20 | 0.0 | -0.109 | YES | 1 | 1.0 |
| 21 | 2.0 | 2.057 | YES | 3 | 0.6949648465705421 |
| 22 | 1.0 | 1.172 | YES | 3 | 0.6144134422105062 |
| 23 | 2.0 | 1.517 | YES | 3 | 0.618285001146391 |
| 24 | 2.0 | 1.976 | YES | 3 | 0.6604605403942285 |
| 25 | 1.0 | 1.495 | YES | 3 | 0.6361148973294672 |
| 26 | 1.0 | 1.186 | YES | 3 | 0.6201651413286199 |
| 27 | 0.0 | -0.037 | YES | 1 | 0.9233602629487052 |
| 28 | 2.0 | 1.687 | YES | 3 | 0.8042507697930613 |
| 29 | 0.0 | -0.097 | YES | 1 | 1.0 |
