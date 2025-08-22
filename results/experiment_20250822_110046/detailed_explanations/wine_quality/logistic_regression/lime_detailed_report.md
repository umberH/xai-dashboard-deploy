# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** logistic_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:19:12  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.6531
- **Average Feature Importance:** 0.0230
- **Feature Importance Std:** 0.1081
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 209 (65.3%)
- **Incorrect Predictions:** 111 (34.7%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 301 | 0.0057 | 94.1% |
| 1 | 293 | 0.0368 | 91.6% |
| 2 | 290 | 0.0344 | 90.6% |
| 3 | 264 | 0.0030 | 82.5% |
| 4 | 261 | 0.0058 | 81.6% |
| 10 | 35 | 0.6096 | 10.9% |
| 8 | 34 | 0.2004 | 10.6% |
| 9 | 33 | 0.2473 | 10.3% |
| 7 | 33 | 0.0988 | 10.3% |
| 6 | 28 | 0.3421 | 8.8% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.097', '0.545', '0.357']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.495', '0.449', '0.056']
- **Top Features:**
  - Feature 10: 0.6796
  - Feature 1: 0.2851
  - Feature 4: 0.0193

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.893', '0.105', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.696', '0.288', '0.016']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.146', '0.563', '0.290']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.577', '0.386', '0.036']
- **Top Features:**
  - Feature 9: 0.5047
  - Feature 8: 0.3452
  - Feature 7: 0.1501

#### Instance 9

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.341', '0.549', '0.110']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 15

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.060', '0.444', '0.496']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 10 | 0.6796091248611289 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 4 | 1.0 | 0.000 | NO | 9 | 0.5047458763170246 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 11 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 16 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 1 | 0.32733598256738117 |
| 18 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 21 | 1.0 | 1.000 | YES | 1 | 0.3311307245329701 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 0.000 | NO | 1 | 0.853623630548604 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 0.000 | YES | 1 | 0.3099723864788352 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 43 | 1.0 | 1.000 | YES | 10 | 0.7270750926595165 |
| 44 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 45 | 2.0 | 1.000 | NO | 2 | 0.6679823800294978 |
| 46 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 47 | 1.0 | 1.000 | YES | 2 | 0.43873504732676416 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 2.0 | 2.000 | YES | 2 | 0.2782757296840722 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
