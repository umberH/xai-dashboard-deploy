# Detailed Explanation Report

**Dataset:** digits  
**Model:** decision_tree  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:32:38  

## Summary Statistics

- **Total Instances:** 360
- **Valid Explanations:** 360
- **Errors:** 0
- **Model Accuracy:** 0.8083
- **Average Feature Importance:** 0.0063
- **Feature Importance Std:** 0.0738
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 291 (80.8%)
- **Incorrect Predictions:** 69 (19.2%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 335 | 0.0012 | 93.1% |
| 1 | 332 | 0.0002 | 92.2% |
| 2 | 324 | 0.0002 | 90.0% |
| 3 | 310 | 0.0010 | 86.1% |
| 4 | 219 | 0.0042 | 60.8% |
| 20 | 46 | 0.7551 | 12.8% |
| 60 | 37 | 0.7186 | 10.3% |
| 38 | 35 | 0.7544 | 9.7% |
| 33 | 33 | 0.6397 | 9.2% |
| 13 | 17 | 0.6800 | 4.7% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 5.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '1.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**
  - Feature 60: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '1.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 8.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.010', '0.020', '0.000', '0.000', '0.000', '0.000', '0.949', '0.020']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 7.0
- **Prediction:** 7.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 7

- **True Label:** 2.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '1.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 14

- **True Label:** 4.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 18

- **True Label:** 9.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '1.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**
  - Feature 38: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 5.0 | 5.000 | YES | 60 | 1.0 |
| 1 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 2 | 8.0 | 8.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 4 | 7.0 | 7.000 | YES | 0 | 0.0 |
| 5 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 6 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 7 | 2.0 | 5.000 | NO | 0 | 0.0 |
| 8 | 6.0 | 6.000 | YES | 43 | 0.5 |
| 9 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 10 | 0.0 | 0.000 | YES | 13 | 1.0 |
| 11 | 5.0 | 5.000 | YES | 33 | 1.0 |
| 12 | 9.0 | 9.000 | YES | 0 | 0.0 |
| 13 | 3.0 | 3.000 | YES | 38 | 1.0 |
| 14 | 4.0 | 8.000 | NO | 0 | 0.0 |
| 15 | 4.0 | 4.000 | YES | 33 | 0.6843023035987092 |
| 16 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 17 | 4.0 | 4.000 | YES | 0 | 0.0 |
| 18 | 9.0 | 3.000 | NO | 38 | 1.0 |
| 19 | 9.0 | 9.000 | YES | 0 | 0.0 |
| 20 | 6.0 | 6.000 | YES | 33 | 0.511350254777912 |
| 21 | 3.0 | 3.000 | YES | 20 | 1.0 |
| 22 | 8.0 | 8.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 8.000 | NO | 20 | 1.0 |
| 24 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 25 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 26 | 6.0 | 6.000 | YES | 27 | 1.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 3.0 | 9.000 | NO | 20 | 0.9504682441193397 |
| 29 | 4.0 | 4.000 | YES | 0 | 0.0 |
| 30 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 31 | 7.0 | 7.000 | YES | 38 | 1.0 |
| 32 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 33 | 6.0 | 6.000 | YES | 60 | 1.0 |
| 34 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 35 | 6.0 | 5.000 | NO | 33 | 1.0 |
| 36 | 6.0 | 1.000 | NO | 0 | 0.0 |
| 37 | 5.0 | 5.000 | YES | 60 | 1.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 9.0 | 3.000 | NO | 60 | 1.0 |
| 40 | 1.0 | 1.000 | YES | 20 | 1.0 |
| 41 | 7.0 | 7.000 | YES | 0 | 0.0 |
| 42 | 9.0 | 8.000 | NO | 38 | 1.0 |
| 43 | 6.0 | 6.000 | YES | 33 | 0.7273505444392973 |
| 44 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 45 | 7.0 | 9.000 | NO | 13 | 0.9846893639320006 |
| 46 | 5.0 | 5.000 | YES | 27 | 0.6909561370560495 |
| 47 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 48 | 7.0 | 7.000 | YES | 0 | 0.0 |
| 49 | 5.0 | 5.000 | YES | 0 | 0.0 |

*Showing first 50 of 360 instances. See JSON file for complete data.*
