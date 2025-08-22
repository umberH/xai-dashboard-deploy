# Detailed Explanation Report

**Dataset:** compas  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-22 13:34:47  

## Summary Statistics

- **Total Instances:** 1443
- **Valid Explanations:** 1443
- **Errors:** 0
- **Model Accuracy:** 0.6868
- **Average Feature Importance:** 0.0365
- **Feature Importance Std:** 0.1771
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 991 (68.7%)
- **Incorrect Predictions:** 452 (31.3%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 1443 | 0.0104 | 100.0% |
| 1 | 1443 | 0.0989 | 100.0% |
| 2 | 1443 | 0.0002 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.408', '0.592']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.344', '0.656']
- **Top Features:**
  - Feature 1: 1.0000
  - Feature 0: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.318', '0.682']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.383', '0.617']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.428', '0.572']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.422', '0.578']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.382', '0.618']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 10

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.409', '0.591']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 1 | 1.0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 9 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 11 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 12 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 13 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 0.0 | 1.000 | NO | 1 | 1.0 |
| 16 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 21 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 22 | 0.0 | 1.000 | NO | 1 | 1.0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 26 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 1 | 0.8924997448436924 |
| 28 | 0.0 | 1.000 | NO | 1 | 0.8856955654864554 |
| 29 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 30 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 35 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 37 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 38 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 43 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 46 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 0.0 | 1.000 | NO | 1 | 0.8897757247045304 |

*Showing first 50 of 1443 instances. See JSON file for complete data.*
