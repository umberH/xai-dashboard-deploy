# Detailed Explanation Report

**Dataset:** compas  
**Model:** gradient_boosting  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-20 18:41:57  

## Summary Statistics

- **Total Instances:** 1443
- **Valid Explanations:** 1443
- **Errors:** 0
- **Model Accuracy:** 0.6951

## Prediction Analysis

- **Correct Predictions:** 1003 (69.5%)
- **Incorrect Predictions:** 440 (30.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 1443 | 0.1996 | 100.0% |
| 1 | 1443 | 0.3306 | 100.0% |
| 2 | 1443 | 0.3153 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.673', '0.327']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.468', '0.532']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.248', '0.752']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.195', '0.805']
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

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.609', '0.391']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.494', '0.506']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 10

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.732', '0.268']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 1.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 0.000 | NO | 0 | 0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0 |
| 2 | 1.0 | 1.000 | YES | 0 | 1 |
| 3 | 1.0 | 1.000 | YES | 0 | 0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0 |
| 5 | 0.0 | 1.000 | NO | 0 | 1 |
| 6 | 0.0 | 0.000 | YES | 0 | 0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0 |
| 8 | 0.0 | 0.000 | YES | 0 | 0 |
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
| 26 | 1.0 | 0.000 | NO | 0 | 1 |
| 27 | 0.0 | 0.000 | YES | 0 | 0 |
| 28 | 0.0 | 1.000 | NO | 0 | 0 |
| 29 | 1.0 | 1.000 | YES | 0 | 1 |
| 30 | 1.0 | 1.000 | YES | 0 | 0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0 |
| 34 | 1.0 | 0.000 | NO | 0 | 0 |
| 35 | 0.0 | 1.000 | NO | 0 | 1 |
| 36 | 0.0 | 1.000 | NO | 0 | 1 |
| 37 | 0.0 | 0.000 | YES | 0 | 0 |
| 38 | 1.0 | 0.000 | NO | 0 | 0 |
| 39 | 1.0 | 1.000 | YES | 0 | 1 |
| 40 | 0.0 | 1.000 | NO | 0 | 1 |
| 41 | 0.0 | 0.000 | YES | 0 | 0 |
| 42 | 1.0 | 0.000 | NO | 0 | 0 |
| 43 | 0.0 | 0.000 | YES | 0 | 0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0 |
| 45 | 0.0 | 0.000 | YES | 0 | 0 |
| 46 | 0.0 | 0.000 | YES | 0 | 0 |
| 47 | 0.0 | 1.000 | NO | 0 | 0 |
| 48 | 1.0 | 0.000 | NO | 0 | 0 |
| 49 | 0.0 | 0.000 | YES | 0 | 0 |

*Showing first 50 of 1443 instances. See JSON file for complete data.*
