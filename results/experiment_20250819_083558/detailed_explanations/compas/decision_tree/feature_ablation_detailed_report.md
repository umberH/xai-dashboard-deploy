# Detailed Explanation Report

**Dataset:** compas  
**Model:** decision_tree  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-19 09:56:51  

## Summary Statistics

- **Total Instances:** 1443
- **Valid Explanations:** 1443
- **Errors:** 0
- **Model Accuracy:** 0.6736

## Prediction Analysis

- **Correct Predictions:** 972 (67.4%)
- **Incorrect Predictions:** 471 (32.6%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 1443 | 0.2349 | 100.0% |
| 1 | 1443 | 0.3763 | 100.0% |
| 2 | 1443 | 0.2924 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.703', '0.297']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.368', '0.632']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

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
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.559', '0.441']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.667', '0.333']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 1.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.467', '0.533']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 0.000 | NO | 0 | 0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0 |
| 2 | 1.0 | 1.000 | YES | 0 | 1 |
| 3 | 1.0 | 1.000 | YES | 0 | 0 |
| 4 | 1.0 | 0.000 | NO | 0 | 1 |
| 5 | 0.0 | 1.000 | NO | 0 | 1 |
| 6 | 0.0 | 0.000 | YES | 0 | 0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0 |
| 8 | 0.0 | 1.000 | NO | 0 | 1 |
| 9 | 1.0 | 1.000 | YES | 0 | 0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0 |
| 11 | 0.0 | 1.000 | NO | 0 | 0 |
| 12 | 0.0 | 1.000 | NO | 0 | 0 |
| 13 | 1.0 | 0.000 | NO | 0 | 0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0 |
| 15 | 0.0 | 1.000 | NO | 0 | 1 |
| 16 | 0.0 | 1.000 | NO | 0 | 0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0 |
| 19 | 0.0 | 1.000 | NO | 0 | 1 |
| 20 | 0.0 | 1.000 | NO | 0 | 0 |
| 21 | 1.0 | 1.000 | YES | 0 | 1 |
| 22 | 0.0 | 1.000 | NO | 0 | 0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0 |
| 24 | 1.0 | 1.000 | YES | 0 | 1 |
| 25 | 0.0 | 0.000 | YES | 0 | 0 |
| 26 | 1.0 | 1.000 | YES | 0 | 0 |
| 27 | 0.0 | 0.000 | YES | 0 | 1 |
| 28 | 0.0 | 1.000 | NO | 0 | 0 |
| 29 | 1.0 | 1.000 | YES | 0 | 1 |
| 30 | 1.0 | 0.000 | NO | 0 | 1 |
| 31 | 0.0 | 0.000 | YES | 0 | 0 |
| 32 | 1.0 | 0.000 | NO | 0 | 1 |
| 33 | 1.0 | 1.000 | YES | 0 | 0 |
| 34 | 1.0 | 0.000 | NO | 0 | 0 |
| 35 | 0.0 | 1.000 | NO | 0 | 1 |
| 36 | 0.0 | 1.000 | NO | 0 | 1 |
| 37 | 0.0 | 0.000 | YES | 0 | 0 |
| 38 | 1.0 | 0.000 | NO | 0 | 0 |
| 39 | 1.0 | 0.000 | NO | 0 | 0 |
| 40 | 0.0 | 1.000 | NO | 0 | 1 |
| 41 | 0.0 | 1.000 | NO | 0 | 1 |
| 42 | 1.0 | 0.000 | NO | 0 | 0 |
| 43 | 0.0 | 0.000 | YES | 0 | 0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0 |
| 45 | 0.0 | 0.000 | YES | 0 | 0 |
| 46 | 0.0 | 0.000 | YES | 0 | 0 |
| 47 | 0.0 | 1.000 | NO | 0 | 0 |
| 48 | 1.0 | 0.000 | NO | 0 | 0 |
| 49 | 0.0 | 1.000 | NO | 0 | 1 |

*Showing first 50 of 1443 instances. See JSON file for complete data.*
