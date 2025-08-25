# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** random_forest  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:33:30  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.5843
- **Average Feature Importance:** 0.0337
- **Feature Importance Std:** 0.1318
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 52 (58.4%)
- **Incorrect Predictions:** 37 (41.6%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 82 | 0.1058 | 92.1% |
| 0 | 81 | 0.0282 | 91.0% |
| 3 | 81 | 0.0279 | 91.0% |
| 1 | 76 | 0.0065 | 85.4% |
| 4 | 70 | 0.0262 | 78.7% |
| 8 | 14 | 0.2666 | 15.7% |
| 5 | 12 | 0.2174 | 13.5% |
| 9 | 11 | 0.1510 | 12.4% |
| 7 | 10 | 0.2174 | 11.2% |
| 6 | 8 | 0.4153 | 9.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.285', '0.479', '0.235']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.213', '0.299', '0.488']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.967', '0.033', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.239', '0.568', '0.193']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.164', '0.353', '0.483']
- **Top Features:**
  - Feature 2: 0.8634
  - Feature 8: 0.0550
  - Feature 9: 0.0499

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.164', '0.442', '0.394']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.958', '0.042', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.010', '0.255', '0.735']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 2.0 | 2.000 | YES | 2 | 0.8633569725975195 |
| 7 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 11 | 0.0 | 0.000 | YES | 6 | 0.8888888888888888 |
| 12 | 0.0 | 1.000 | NO | 6 | 0.5720823947407706 |
| 13 | 2.0 | 0.000 | NO | 2 | 0.7934760268878164 |
| 14 | 1.0 | 1.000 | YES | 2 | 0.7137476022302649 |
| 15 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 16 | 0.0 | 1.000 | NO | 4 | 0.4965986394557829 |
| 17 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 2 | 0.636078258376629 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 0.0 | 1.000 | NO | 8 | 0.4802271035021511 |
| 25 | 2.0 | 1.000 | NO | 7 | 0.5091941311565766 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 28 | 2.0 | 1.000 | NO | 9 | 0.34767844177356594 |
| 29 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 2 | 0.7986287129785339 |
| 31 | 2.0 | 2.000 | YES | 2 | 0.3834257645186874 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 35 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 36 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 37 | 0.0 | 0.000 | YES | 5 | 1.0 |
| 38 | 0.0 | 0.000 | YES | 6 | 1.0 |
| 39 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 2.0 | 2.000 | YES | 3 | 0.4748905098032437 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 46 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 48 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 49 | 1.0 | 0.000 | NO | 0 | 0.0 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
