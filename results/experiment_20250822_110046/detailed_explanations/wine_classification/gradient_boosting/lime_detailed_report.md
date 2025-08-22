# Detailed Explanation Report

**Dataset:** wine_classification  
**Model:** gradient_boosting  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:31:04  

## Summary Statistics

- **Total Instances:** 36
- **Valid Explanations:** 36
- **Errors:** 0
- **Model Accuracy:** 0.9444
- **Average Feature Importance:** 0.0192
- **Feature Importance Std:** 0.1318
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 34 (94.4%)
- **Incorrect Predictions:** 2 (5.6%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 36 | 0.0000 | 100.0% |
| 1 | 36 | 0.0000 | 100.0% |
| 2 | 36 | 0.0000 | 100.0% |
| 3 | 34 | 0.0000 | 94.4% |
| 4 | 27 | 0.0000 | 75.0% |
| 12 | 6 | 0.9075 | 16.7% |
| 6 | 4 | 0.8609 | 11.1% |
| 7 | 1 | 0.1111 | 2.8% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.009', '0.991']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 13

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '0.999', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 2.0 | 2.000 | YES | 12 | 0.8888888888888888 |
| 10 | 1.0 | 1.000 | YES | 6 | 1.0 |
| 11 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 13 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 18 | 1.0 | 1.000 | YES | 12 | 0.5562760489653079 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 1.0 | 1.000 | YES | 6 | 1.0 |
| 21 | 1.0 | 1.000 | YES | 12 | 1.0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 28 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 29 | 2.0 | 2.000 | YES | 12 | 1.0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 2.0 | 2.000 | YES | 12 | 1.0 |
| 32 | 1.0 | 1.000 | YES | 6 | 1.0 |
| 33 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 35 | 2.0 | 2.000 | YES | 12 | 1.0 |
