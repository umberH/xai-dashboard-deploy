# Detailed Explanation Report

**Dataset:** german_credit  
**Model:** gradient_boosting  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:06:25  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7150
- **Average Feature Importance:** 0.0214
- **Feature Importance Std:** 0.1288
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 143 (71.5%)
- **Incorrect Predictions:** 57 (28.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 200 | 0.0328 | 100.0% |
| 3 | 200 | 0.0028 | 100.0% |
| 4 | 200 | 0.0254 | 100.0% |
| 1 | 199 | 0.0825 | 99.5% |
| 2 | 199 | 0.0067 | 99.5% |
| 5 | 1 | 0.0375 | 0.5% |
| 6 | 1 | 0.0086 | 0.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.740', '0.260']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.818', '0.182']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.676', '0.324']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.624', '0.376']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.868', '0.132']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.716', '0.284']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.663', '0.337']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 11

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.653', '0.347']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 4 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 11 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 13 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 14 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 15 | 0.0 | 0.000 | YES | 1 | 0.5397175488712145 |
| 16 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 1 | 0.6010103852210352 |
| 22 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 23 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 1 | 0.9402732392715105 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.9439746557505296 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 37 | 1.0 | 1.000 | YES | 1 | 0.8247757638275633 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 40 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 2 | 0.8571428571428571 |
| 42 | 0.0 | 1.000 | NO | 1 | 0.9544362397845924 |
| 43 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 47 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 48 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 49 | 1.0 | 0.000 | NO | 0 | 0.0 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
