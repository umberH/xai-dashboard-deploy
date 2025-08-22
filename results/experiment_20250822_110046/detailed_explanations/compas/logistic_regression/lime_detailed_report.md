# Detailed Explanation Report

**Dataset:** compas  
**Model:** logistic_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-22 13:35:31  

## Summary Statistics

- **Total Instances:** 1443
- **Valid Explanations:** 1443
- **Errors:** 0
- **Model Accuracy:** 0.6854
- **Average Feature Importance:** 0.0372
- **Feature Importance Std:** 0.1763
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 989 (68.5%)
- **Incorrect Predictions:** 454 (31.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 1443 | 0.0108 | 100.0% |
| 1 | 1443 | 0.0993 | 100.0% |
| 2 | 1443 | 0.0014 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.648', '0.352']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.320', '0.680']
- **Top Features:**
  - Feature 1: 1.0000
  - Feature 0: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.205', '0.795']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.525', '0.475']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.733', '0.267']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.704', '0.296']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.517', '0.483']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 10

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.652', '0.348']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 1 | 1.0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 9 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 11 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 12 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 13 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 0.0 | 1.000 | NO | 1 | 1.0 |
| 16 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 21 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 22 | 0.0 | 1.000 | NO | 1 | 1.0 |
| 23 | 1.0 | 1.000 | YES | 1 | 1.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 26 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 1 | 0.7402106653619737 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 30 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 35 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 37 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 38 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 43 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 46 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 0.0 | 1.000 | NO | 1 | 0.9255332737823068 |

*Showing first 50 of 1443 instances. See JSON file for complete data.*
