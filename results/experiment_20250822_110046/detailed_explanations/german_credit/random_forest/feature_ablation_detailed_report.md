# Detailed Explanation Report

**Dataset:** german_credit  
**Model:** random_forest  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-22 14:06:19  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7050

## Prediction Analysis

- **Correct Predictions:** 141 (70.5%)
- **Incorrect Predictions:** 59 (29.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 200 | 0.1100 | 100.0% |
| 1 | 200 | 0.1250 | 100.0% |
| 2 | 200 | 0.1000 | 100.0% |
| 3 | 200 | 0.0400 | 100.0% |
| 4 | 200 | 0.0950 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.746', '0.254']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.802', '0.198']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.841', '0.159']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.788', '0.212']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.813', '0.187']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.703', '0.297']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.627', '0.373']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 11

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.854', '0.146']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0 |
| 2 | 1.0 | 0.000 | NO | 0 | 0 |
| 3 | 0.0 | 0.000 | YES | 0 | 0 |
| 4 | 1.0 | 0.000 | NO | 0 | 0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0 |
| 8 | 0.0 | 0.000 | YES | 0 | 0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0 |
| 10 | 0.0 | 0.000 | YES | 0 | 0 |
| 11 | 1.0 | 0.000 | NO | 0 | 0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0 |
| 13 | 1.0 | 1.000 | YES | 0 | 1 |
| 14 | 1.0 | 0.000 | NO | 0 | 0 |
| 15 | 0.0 | 0.000 | YES | 0 | 0 |
| 16 | 0.0 | 0.000 | YES | 0 | 0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0 |
| 21 | 0.0 | 1.000 | NO | 0 | 1 |
| 22 | 1.0 | 0.000 | NO | 0 | 0 |
| 23 | 1.0 | 0.000 | NO | 0 | 0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0 |
| 25 | 0.0 | 0.000 | YES | 0 | 0 |
| 26 | 0.0 | 0.000 | YES | 0 | 0 |
| 27 | 0.0 | 0.000 | YES | 0 | 1 |
| 28 | 0.0 | 0.000 | YES | 0 | 0 |
| 29 | 0.0 | 0.000 | YES | 0 | 0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0 |
| 31 | 0.0 | 1.000 | NO | 0 | 0 |
| 32 | 0.0 | 0.000 | YES | 0 | 0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0 |
| 37 | 1.0 | 0.000 | NO | 0 | 0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0 |
| 39 | 0.0 | 1.000 | NO | 0 | 0 |
| 40 | 1.0 | 0.000 | NO | 0 | 0 |
| 41 | 1.0 | 1.000 | YES | 0 | 1 |
| 42 | 0.0 | 0.000 | YES | 0 | 0 |
| 43 | 0.0 | 1.000 | NO | 0 | 0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0 |
| 45 | 0.0 | 0.000 | YES | 0 | 1 |
| 46 | 1.0 | 0.000 | NO | 0 | 0 |
| 47 | 1.0 | 0.000 | NO | 0 | 0 |
| 48 | 0.0 | 0.000 | YES | 0 | 0 |
| 49 | 1.0 | 1.000 | YES | 0 | 1 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
