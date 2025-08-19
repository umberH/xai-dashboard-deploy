# Detailed Explanation Report

**Dataset:** compas  
**Model:** gradient_boosting  
**Explanation Method:** lime  
**Generated:** 2025-08-19 18:31:29  

## Summary Statistics

- **Total Instances:** 1443
- **Valid Explanations:** 1443
- **Errors:** 0
- **Model Accuracy:** 0.6951
- **Average Feature Importance:** 0.2292
- **Feature Importance Std:** 0.4070
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 1003 (69.5%)
- **Incorrect Predictions:** 440 (30.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 1443 | 0.6534 | 100.0% |
| 0 | 1443 | 0.0130 | 100.0% |
| 1 | 1443 | 0.0210 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.673', '0.327']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.468', '0.532']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.248', '0.752']
- **Top Features:**
  - Feature 2: 0.6543
  - Feature 1: 0.3457
  - Feature 0: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.195', '0.805']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.813', '0.187']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.609', '0.391']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.494', '0.506']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 10

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.732', '0.268']
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
| 3 | 1.0 | 1.000 | YES | 2 | 0.6543013549816271 |
| 4 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 5 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 6 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 9 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 10 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 11 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 12 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 13 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 16 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 18 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 19 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 20 | 0.0 | 1.000 | NO | 0 | 0.945817488887015 |
| 21 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 22 | 0.0 | 1.000 | NO | 2 | 0.7449278506937923 |
| 23 | 1.0 | 1.000 | YES | 2 | 0.7996927410205359 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 26 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 0.0 | 1.000 | NO | 2 | 0.9024147469354101 |
| 29 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 30 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 35 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 36 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 37 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 38 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 39 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 40 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 41 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 42 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 43 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 44 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 45 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 46 | 0.0 | 0.000 | YES | 2 | 0.8591355734212878 |
| 47 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 0.0 | 0.000 | YES | 0 | 0.0 |

*Showing first 50 of 1443 instances. See JSON file for complete data.*
