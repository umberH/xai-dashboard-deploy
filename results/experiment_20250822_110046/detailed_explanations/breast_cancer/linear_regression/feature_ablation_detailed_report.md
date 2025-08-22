# Detailed Explanation Report

**Dataset:** breast_cancer  
**Model:** linear_regression  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-22 13:57:05  

## Summary Statistics

- **Total Instances:** 114
- **Valid Explanations:** 114
- **Errors:** 0
- **Model Accuracy:** 0.9561

## Prediction Analysis

- **Correct Predictions:** 109 (95.6%)
- **Incorrect Predictions:** 5 (4.4%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 114 | 0.0526 | 100.0% |
| 1 | 114 | 0.0088 | 100.0% |
| 2 | 114 | 0.5000 | 100.0% |
| 3 | 114 | 0.0088 | 100.0% |
| 4 | 114 | 0.0000 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.480', '0.520']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.240', '0.760']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.443', '0.557']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.347', '0.653']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.586', '0.414']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

### Incorrect Predictions (Sample)

#### Instance 16

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.380', '0.620']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 1.0000
  - Feature 2: 1.0000

#### Instance 21

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.367', '0.633']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 35

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.363', '0.637']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0 |
| 1 | 1.0 | 1.000 | YES | 0 | 0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0 |
| 3 | 1.0 | 1.000 | YES | 0 | 1 |
| 4 | 0.0 | 0.000 | YES | 0 | 0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0 |
| 8 | 0.0 | 0.000 | YES | 0 | 0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0 |
| 11 | 0.0 | 0.000 | YES | 0 | 0 |
| 12 | 1.0 | 1.000 | YES | 0 | 0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0 |
| 16 | 1.0 | 0.000 | NO | 0 | 0 |
| 17 | 1.0 | 1.000 | YES | 0 | 0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0 |
| 19 | 1.0 | 1.000 | YES | 0 | 0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0 |
| 21 | 0.0 | 1.000 | NO | 0 | 1 |
| 22 | 1.0 | 1.000 | YES | 0 | 0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0 |
| 25 | 1.0 | 1.000 | YES | 0 | 1 |
| 26 | 0.0 | 0.000 | YES | 0 | 0 |
| 27 | 1.0 | 1.000 | YES | 0 | 0 |
| 28 | 1.0 | 1.000 | YES | 0 | 0 |
| 29 | 1.0 | 1.000 | YES | 0 | 0 |
| 30 | 1.0 | 1.000 | YES | 0 | 0 |
| 31 | 1.0 | 1.000 | YES | 0 | 0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0 |
| 35 | 0.0 | 1.000 | NO | 0 | 0 |
| 36 | 1.0 | 1.000 | YES | 0 | 0 |
| 37 | 1.0 | 1.000 | YES | 0 | 0 |
| 38 | 1.0 | 1.000 | YES | 0 | 0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0 |
| 40 | 1.0 | 1.000 | YES | 0 | 0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0 |
| 43 | 0.0 | 0.000 | YES | 0 | 0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0 |
| 45 | 1.0 | 1.000 | YES | 0 | 0 |
| 46 | 1.0 | 1.000 | YES | 0 | 0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0 |
| 48 | 1.0 | 1.000 | YES | 0 | 1 |
| 49 | 0.0 | 0.000 | YES | 0 | 0 |

*Showing first 50 of 114 instances. See JSON file for complete data.*
