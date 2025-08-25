# Detailed Explanation Report

**Dataset:** iris  
**Model:** gradient_boosting  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:29:12  

## Summary Statistics

- **Total Instances:** 30
- **Valid Explanations:** 30
- **Errors:** 0
- **Model Accuracy:** 0.9667
- **Average Feature Importance:** 0.0833
- **Feature Importance Std:** 0.2652
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 29 (96.7%)
- **Incorrect Predictions:** 1 (3.3%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 30 | 0.0001 | 100.0% |
| 1 | 30 | 0.0000 | 100.0% |
| 2 | 30 | 0.2850 | 100.0% |
| 3 | 30 | 0.0482 | 100.0% |

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
- **Prediction Probabilities:** ['0.000', '0.003', '0.997']
- **Top Features:**
  - Feature 2: 0.9596
  - Feature 3: 0.0404
  - Feature 0: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 25

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.005', '0.995']
- **Top Features:**
  - Feature 2: 0.7592
  - Feature 3: 0.2369
  - Feature 0: 0.0039

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 2.0 | 2.000 | YES | 2 | 0.9595899450874981 |
| 2 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 2.0 | 2.000 | YES | 2 | 1.0 |
| 9 | 1.0 | 1.000 | YES | 2 | 0.831649831649832 |
| 10 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 11 | 2.0 | 2.000 | YES | 2 | 1.0 |
| 12 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 13 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 16 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 17 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 18 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 19 | 2.0 | 2.000 | YES | 2 | 1.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 23 | 2.0 | 2.000 | YES | 3 | 1.0 |
| 24 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 2.000 | NO | 2 | 0.7591937478777482 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 0 | 0.0 |
