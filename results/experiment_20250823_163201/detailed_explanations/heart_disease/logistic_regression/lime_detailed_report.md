# Detailed Explanation Report

**Dataset:** heart_disease  
**Model:** logistic_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:25:57  

## Summary Statistics

- **Total Instances:** 60
- **Valid Explanations:** 60
- **Errors:** 0
- **Model Accuracy:** 0.8000
- **Average Feature Importance:** 0.0433
- **Feature Importance Std:** 0.1805
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 48 (80.0%)
- **Incorrect Predictions:** 12 (20.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 60 | 0.0044 | 100.0% |
| 1 | 60 | 0.0007 | 100.0% |
| 2 | 60 | 0.0043 | 100.0% |
| 3 | 60 | 0.0592 | 100.0% |
| 4 | 60 | 0.1481 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.903', '0.097']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.781', '0.219']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.646', '0.354']
- **Top Features:**
  - Feature 3: 0.8288
  - Feature 2: 0.1345
  - Feature 0: 0.0366

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.742', '0.258']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.864', '0.136']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.497', '0.503']
- **Top Features:**
  - Feature 4: 0.5178
  - Feature 3: 0.4503
  - Feature 1: 0.0319

#### Instance 26

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.285', '0.715']
- **Top Features:**
  - Feature 4: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 28

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.368', '0.632']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 3 | 0.8288338641703757 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 1.000 | NO | 4 | 0.5178128256813463 |
| 5 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 13 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 14 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 15 | 1.0 | 1.000 | YES | 4 | 0.9835271377609199 |
| 16 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 4 | 0.4755138952679731 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 26 | 0.0 | 1.000 | NO | 4 | 1.0 |
| 27 | 1.0 | 1.000 | YES | 4 | 0.901273798665103 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 32 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 33 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 4 | 0.6846051856981482 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 3 | 0.578814673831677 |
| 45 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 1.000 | NO | 4 | 0.9791666666666667 |
| 48 | 1.0 | 0.000 | NO | 3 | 1.0 |
| 49 | 0.0 | 1.000 | NO | 0 | 0.0 |

*Showing first 50 of 60 instances. See JSON file for complete data.*
