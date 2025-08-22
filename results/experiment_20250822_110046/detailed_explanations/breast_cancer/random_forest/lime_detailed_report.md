# Detailed Explanation Report

**Dataset:** breast_cancer  
**Model:** random_forest  
**Explanation Method:** lime  
**Generated:** 2025-08-22 13:37:15  

## Summary Statistics

- **Total Instances:** 114
- **Valid Explanations:** 114
- **Errors:** 0
- **Model Accuracy:** 0.9561
- **Average Feature Importance:** 0.0050
- **Feature Importance Std:** 0.0436
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 109 (95.6%)
- **Incorrect Predictions:** 5 (4.4%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 106 | 0.0065 | 93.0% |
| 3 | 102 | 0.0061 | 89.5% |
| 1 | 101 | 0.0002 | 88.6% |
| 2 | 101 | 0.0036 | 88.6% |
| 4 | 99 | 0.0008 | 86.8% |
| 27 | 9 | 0.4410 | 7.9% |
| 7 | 8 | 0.3564 | 7.0% |
| 20 | 6 | 0.3211 | 5.3% |
| 25 | 5 | 0.0546 | 4.4% |
| 6 | 4 | 0.2626 | 3.5% |

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
- **Prediction Probabilities:** ['0.880', '0.120']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.990', '0.010']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.010', '0.990']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.720', '0.280']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 25

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.690', '0.310']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 35

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.420', '0.580']
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
| 15 | 1.0 | 1.000 | YES | 2 | 0.3057933850570253 |
| 16 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 17 | 1.0 | 1.000 | YES | 27 | 0.48763199793417705 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 28 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 30 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 31 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 6 | 0.4392539594696638 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 36 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 1.000 | YES | 13 | 0.3561354761867852 |
| 38 | 1.0 | 1.000 | YES | 27 | 0.8787873807449207 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 1.0 | 1.000 | YES | 9 | 0.21892564543693563 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 49 | 0.0 | 0.000 | YES | 0 | 0.0 |

*Showing first 50 of 114 instances. See JSON file for complete data.*
