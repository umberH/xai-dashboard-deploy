# Detailed Explanation Report

**Dataset:** breast_cancer  
**Model:** gradient_boosting  
**Explanation Method:** lime  
**Generated:** 2025-08-22 13:55:00  

## Summary Statistics

- **Total Instances:** 114
- **Valid Explanations:** 114
- **Errors:** 0
- **Model Accuracy:** 0.9561
- **Average Feature Importance:** 0.0020
- **Feature Importance Std:** 0.0360
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 109 (95.6%)
- **Incorrect Predictions:** 5 (4.4%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 112 | 0.0031 | 98.2% |
| 3 | 112 | 0.0137 | 98.2% |
| 0 | 111 | 0.0003 | 97.4% |
| 1 | 111 | 0.0001 | 97.4% |
| 4 | 109 | 0.0005 | 95.6% |
| 20 | 5 | 0.4374 | 4.4% |
| 22 | 3 | 0.2556 | 2.6% |
| 21 | 2 | 0.1207 | 1.8% |
| 27 | 2 | 0.6899 | 1.8% |
| 16 | 1 | 0.1442 | 0.9% |

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
- **Prediction Probabilities:** ['0.997', '0.003']
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

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.001', '0.999']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.876', '0.124']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 35

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.061', '0.939']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 53

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.054', '0.946']
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
| 3 | 1.0 | 0.000 | NO | 0 | 0.0 |
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
| 15 | 1.0 | 1.000 | YES | 22 | 0.6777811479064366 |
| 16 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 17 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 28 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 30 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 31 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 36 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 1.0 | 1.000 | YES | 27 | 0.4364193989602863 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 49 | 0.0 | 0.000 | YES | 0 | 0.0 |

*Showing first 50 of 114 instances. See JSON file for complete data.*
