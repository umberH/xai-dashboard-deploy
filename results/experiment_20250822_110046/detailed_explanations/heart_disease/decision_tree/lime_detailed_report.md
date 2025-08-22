# Detailed Explanation Report

**Dataset:** heart_disease  
**Model:** decision_tree  
**Explanation Method:** lime  
**Generated:** 2025-08-22 13:57:42  

## Summary Statistics

- **Total Instances:** 60
- **Valid Explanations:** 60
- **Errors:** 0
- **Model Accuracy:** 0.7333
- **Average Feature Importance:** 0.0633
- **Feature Importance Std:** 0.2370
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 44 (73.3%)
- **Incorrect Predictions:** 16 (26.7%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 60 | 0.0131 | 100.0% |
| 1 | 60 | 0.0167 | 100.0% |
| 2 | 60 | 0.0000 | 100.0% |
| 3 | 60 | 0.1035 | 100.0% |
| 4 | 60 | 0.1833 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 3: 0.9481
  - Feature 0: 0.0519
  - Feature 1: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 3: 0.7778
  - Feature 0: 0.2222
  - Feature 1: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 4: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

### Incorrect Predictions (Sample)

#### Instance 9

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 11

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 12

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 3 | 0.9480601371667282 |
| 3 | 0.0 | 0.000 | YES | 3 | 0.7777777777777778 |
| 4 | 0.0 | 0.000 | YES | 4 | 1.0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 11 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 12 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 13 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 14 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 4 | 1.0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 0 | 0.514579686968912 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 1.0 | 1.000 | YES | 1 | 1.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 4 | 1.0 |
| 37 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 44 | 0.0 | 1.000 | NO | 4 | 1.0 |
| 45 | 0.0 | 0.000 | YES | 3 | 1.0 |
| 46 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 47 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 48 | 1.0 | 1.000 | YES | 3 | 1.0 |
| 49 | 0.0 | 1.000 | NO | 0 | 0.0 |

*Showing first 50 of 60 instances. See JSON file for complete data.*
