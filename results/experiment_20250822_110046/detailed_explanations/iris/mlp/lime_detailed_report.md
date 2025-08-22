# Detailed Explanation Report

**Dataset:** iris  
**Model:** mlp  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:09:42  

## Summary Statistics

- **Total Instances:** 30
- **Valid Explanations:** 30
- **Errors:** 0
- **Model Accuracy:** 0.9667
- **Average Feature Importance:** 0.0583
- **Feature Importance Std:** 0.1938
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 29 (96.7%)
- **Incorrect Predictions:** 1 (3.3%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 30 | 0.0035 | 100.0% |
| 1 | 30 | 0.1003 | 100.0% |
| 2 | 30 | 0.0598 | 100.0% |
| 3 | 30 | 0.0698 | 100.0% |

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
- **Prediction Probabilities:** ['0.001', '0.252', '0.747']
- **Top Features:**
  - Feature 2: 0.5094
  - Feature 3: 0.4497
  - Feature 0: 0.0409

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.025', '0.972', '0.003']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.009', '0.989', '0.002']
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
- **Prediction Probabilities:** ['0.001', '0.355', '0.644']
- **Top Features:**
  - Feature 3: 0.5449
  - Feature 2: 0.4263
  - Feature 0: 0.0189

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 2.0 | 2.000 | YES | 2 | 0.5093920101325868 |
| 2 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 1 | 1.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 9 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 10 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 11 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 12 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 13 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 16 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 17 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 2.0 | 2.000 | YES | 3 | 0.5384267027547944 |
| 20 | 0.0 | 0.000 | YES | 1 | 1.0 |
| 21 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 23 | 2.0 | 2.000 | YES | 3 | 0.5596415873350874 |
| 24 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 2.000 | NO | 3 | 0.5449215218702734 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 1 | 1.0 |
| 28 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 0 | 0.0 |
