# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** logistic_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:35:54  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.6517
- **Average Feature Importance:** 0.0315
- **Feature Importance Std:** 0.1075
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 58 (65.2%)
- **Incorrect Predictions:** 31 (34.8%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 81 | 0.0235 | 91.0% |
| 2 | 78 | 0.0651 | 87.6% |
| 3 | 77 | 0.0279 | 86.5% |
| 0 | 76 | 0.0051 | 85.4% |
| 4 | 74 | 0.0234 | 83.1% |
| 8 | 20 | 0.4177 | 22.5% |
| 7 | 16 | 0.1885 | 18.0% |
| 5 | 14 | 0.2312 | 15.7% |
| 9 | 6 | 0.1094 | 6.7% |
| 6 | 3 | 0.0992 | 3.4% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.225', '0.617', '0.158']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.025', '0.257', '0.717']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.879', '0.119', '0.001']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.262', '0.466', '0.271']
- **Top Features:**
  - Feature 7: 0.2462
  - Feature 8: 0.2246
  - Feature 3: 0.2167

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.036', '0.306', '0.658']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.052', '0.388', '0.561']
- **Top Features:**
  - Feature 2: 0.3980
  - Feature 3: 0.2650
  - Feature 8: 0.2506

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.897', '0.102', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.003', '0.073', '0.924']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 2.000 | NO | 2 | 0.3980366119671443 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 7 | 0.2462086272603902 |
| 6 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 7 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 7 | 0.5714285714285714 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 13 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 14 | 1.0 | 1.000 | YES | 2 | 0.9954433464772238 |
| 15 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 16 | 0.0 | 0.000 | YES | 8 | 0.3357830553314902 |
| 17 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 1.000 | NO | 8 | 0.29359164464684023 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 0.0 | 1.000 | NO | 8 | 0.36593386224798485 |
| 25 | 2.0 | 1.000 | NO | 2 | 0.6024786046877366 |
| 26 | 1.0 | 1.000 | YES | 8 | 0.37321402891862604 |
| 27 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 28 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 29 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 2.0 | 1.000 | NO | 2 | 0.4784562425592373 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 36 | 1.0 | 1.000 | YES | 8 | 0.4166896082168206 |
| 37 | 0.0 | 1.000 | NO | 8 | 0.5985609947447854 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 2.000 | NO | 3 | 0.375169952742696 |
| 43 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 46 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 48 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 49 | 1.0 | 1.000 | YES | 2 | 1.0 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
