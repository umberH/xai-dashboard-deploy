# Detailed Explanation Report

**Dataset:** compas  
**Model:** decision_tree  
**Explanation Method:** lime  
**Generated:** 2025-08-19 09:56:38  

## Summary Statistics

- **Total Instances:** 1443
- **Valid Explanations:** 1443
- **Errors:** 0
- **Model Accuracy:** 0.6736
- **Average Feature Importance:** 0.2657
- **Feature Importance Std:** 0.4276
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 972 (67.4%)
- **Incorrect Predictions:** 471 (32.6%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 1443 | 0.6140 | 100.0% |
| 0 | 1443 | 0.0557 | 100.0% |
| 1 | 1443 | 0.1272 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.703', '0.297']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.368', '0.632']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.320', '0.680']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.871', '0.129']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 1: 1.0000
  - Feature 0: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.559', '0.441']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.667', '0.333']
- **Top Features:**
  - Feature 1: 1.0000
  - Feature 0: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.467', '0.533']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 1 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 2 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 4 | 1.0 | 0.000 | NO | 1 | 1.0 |
| 5 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 6 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 7 | 0.0 | 0.000 | YES | 1 | 1.0 |
| 8 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 9 | 1.0 | 1.000 | YES | 1 | 1.0 |
| 10 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 11 | 0.0 | 1.000 | NO | 1 | 1.0 |
| 12 | 0.0 | 1.000 | NO | 1 | 1.0 |
| 13 | 1.0 | 0.000 | NO | 0 | 1.0 |
| 14 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 15 | 0.0 | 1.000 | NO | 2 | 0.9712064682573892 |
| 16 | 0.0 | 1.000 | NO | 0 | 1.0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 18 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 19 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 20 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 21 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 22 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 23 | 1.0 | 1.000 | YES | 1 | 1.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 26 | 1.0 | 1.000 | YES | 1 | 0.9180687365499454 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 0.0 | 1.000 | NO | 1 | 1.0 |
| 29 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 30 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 31 | 0.0 | 0.000 | YES | 0 | 1.0 |
| 32 | 1.0 | 0.000 | NO | 1 | 1.0 |
| 33 | 1.0 | 1.000 | YES | 1 | 0.5714285714285714 |
| 34 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 35 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 36 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 37 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 38 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 39 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 40 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 41 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 42 | 1.0 | 0.000 | NO | 0 | 0.974285800623828 |
| 43 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 44 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 45 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 46 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 47 | 0.0 | 1.000 | NO | 1 | 1.0 |
| 48 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 49 | 0.0 | 1.000 | NO | 0 | 0.0 |

*Showing first 50 of 1443 instances. See JSON file for complete data.*
