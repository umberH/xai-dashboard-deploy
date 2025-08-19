# Detailed Explanation Report

**Dataset:** adult_income  
**Model:** decision_tree  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-19 17:53:59  

## Summary Statistics

- **Total Instances:** 6033
- **Valid Explanations:** 6033
- **Errors:** 0
- **Model Accuracy:** 0.8326

## Prediction Analysis

- **Correct Predictions:** 5023 (83.3%)
- **Incorrect Predictions:** 1010 (16.7%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 6033 | 0.0393 | 100.0% |
| 1 | 6033 | 0.0774 | 100.0% |
| 2 | 6033 | 0.0333 | 100.0% |
| 3 | 6033 | 0.0151 | 100.0% |
| 4 | 6033 | 0.0462 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.974', '0.026']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.889', '0.111']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.910', '0.090']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 8

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.494', '0.506']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 1.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.769', '0.231']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 1.000 | NO | 0 | 0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0 |
| 2 | 1.0 | 0.000 | NO | 0 | 1 |
| 3 | 0.0 | 0.000 | YES | 0 | 0 |
| 4 | 0.0 | 1.000 | NO | 0 | 0 |
| 5 | 1.0 | 0.000 | NO | 0 | 1 |
| 6 | 1.0 | 1.000 | YES | 0 | 0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0 |
| 8 | 0.0 | 0.000 | YES | 0 | 0 |
| 9 | 1.0 | 1.000 | YES | 0 | 0 |
| 10 | 0.0 | 0.000 | YES | 0 | 0 |
| 11 | 1.0 | 0.000 | NO | 0 | 0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0 |
| 15 | 0.0 | 0.000 | YES | 0 | 0 |
| 16 | 0.0 | 0.000 | YES | 0 | 0 |
| 17 | 1.0 | 0.000 | NO | 0 | 0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0 |
| 20 | 1.0 | 1.000 | YES | 0 | 0 |
| 21 | 0.0 | 0.000 | YES | 0 | 1 |
| 22 | 1.0 | 1.000 | YES | 0 | 0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0 |
| 25 | 0.0 | 0.000 | YES | 0 | 0 |
| 26 | 0.0 | 0.000 | YES | 0 | 0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0 |
| 28 | 1.0 | 1.000 | YES | 0 | 0 |
| 29 | 0.0 | 0.000 | YES | 0 | 0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0 |
| 32 | 0.0 | 0.000 | YES | 0 | 0 |
| 33 | 0.0 | 0.000 | YES | 0 | 0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0 |
| 37 | 0.0 | 0.000 | YES | 0 | 0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0 |
| 40 | 1.0 | 0.000 | NO | 0 | 0 |
| 41 | 1.0 | 0.000 | NO | 0 | 0 |
| 42 | 0.0 | 0.000 | YES | 0 | 0 |
| 43 | 0.0 | 1.000 | NO | 0 | 0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0 |
| 45 | 1.0 | 0.000 | NO | 0 | 0 |
| 46 | 1.0 | 1.000 | YES | 0 | 0 |
| 47 | 1.0 | 0.000 | NO | 0 | 0 |
| 48 | 1.0 | 0.000 | NO | 0 | 0 |
| 49 | 1.0 | 1.000 | YES | 0 | 0 |

*Showing first 50 of 6033 instances. See JSON file for complete data.*
