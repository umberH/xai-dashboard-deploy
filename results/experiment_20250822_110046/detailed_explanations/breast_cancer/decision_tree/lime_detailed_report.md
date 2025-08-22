# Detailed Explanation Report

**Dataset:** breast_cancer  
**Model:** decision_tree  
**Explanation Method:** lime  
**Generated:** 2025-08-22 13:36:14  

## Summary Statistics

- **Total Instances:** 114
- **Valid Explanations:** 114
- **Errors:** 0
- **Model Accuracy:** 0.9123
- **Average Feature Importance:** 0.0064
- **Feature Importance Std:** 0.0756
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 104 (91.2%)
- **Incorrect Predictions:** 10 (8.8%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 111 | 0.0000 | 97.4% |
| 1 | 110 | 0.0000 | 96.5% |
| 2 | 108 | 0.0010 | 94.7% |
| 3 | 107 | 0.0000 | 93.9% |
| 4 | 93 | 0.0002 | 81.6% |
| 27 | 14 | 0.8220 | 12.3% |
| 20 | 12 | 0.7103 | 10.5% |
| 11 | 2 | 0.7425 | 1.8% |
| 5 | 2 | 0.0252 | 1.8% |
| 14 | 2 | 0.0202 | 1.8% |

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

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 25

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 20: 0.8889
  - Feature 2: 0.1111
  - Feature 0: 0.0000

#### Instance 33

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 37

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 20 | 1.0 |
| 16 | 1.0 | 1.000 | YES | 20 | 1.0 |
| 17 | 1.0 | 1.000 | YES | 11 | 0.5849068242305874 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 1.000 | YES | 11 | 0.9 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 0.000 | NO | 20 | 0.8888888888888888 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 28 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 30 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 31 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 0.000 | YES | 27 | 1.0 |
| 36 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 38 | 1.0 | 1.000 | YES | 27 | 1.0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 1.0 | 0.000 | NO | 27 | 0.697988298842532 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 48 | 1.0 | 0.000 | NO | 20 | 0.9303379275652794 |
| 49 | 0.0 | 0.000 | YES | 0 | 0.0 |

*Showing first 50 of 114 instances. See JSON file for complete data.*
