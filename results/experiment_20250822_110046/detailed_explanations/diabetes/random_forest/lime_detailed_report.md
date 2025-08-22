# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** random_forest  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:19:58  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.5843
- **Average Feature Importance:** 0.0360
- **Feature Importance Std:** 0.1401
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 52 (58.4%)
- **Incorrect Predictions:** 37 (41.6%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 85 | 0.0422 | 95.5% |
| 2 | 85 | 0.1208 | 95.5% |
| 3 | 82 | 0.0203 | 92.1% |
| 1 | 80 | 0.0066 | 89.9% |
| 4 | 67 | 0.0272 | 75.3% |
| 8 | 13 | 0.4436 | 14.6% |
| 9 | 10 | 0.1540 | 11.2% |
| 5 | 10 | 0.2376 | 11.2% |
| 6 | 7 | 0.4626 | 7.9% |
| 7 | 6 | 0.0554 | 6.7% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.285', '0.479', '0.235']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.213', '0.299', '0.488']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.967', '0.033', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.239', '0.568', '0.193']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.164', '0.353', '0.483']
- **Top Features:**
  - Feature 2: 0.7545
  - Feature 8: 0.1089
  - Feature 9: 0.0763

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.164', '0.442', '0.394']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.958', '0.042', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.010', '0.255', '0.735']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 2.0 | 2.000 | YES | 2 | 0.7545083556207967 |
| 7 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 11 | 0.0 | 0.000 | YES | 6 | 0.8659159725182975 |
| 12 | 0.0 | 1.000 | NO | 2 | 0.6868582389189835 |
| 13 | 2.0 | 0.000 | NO | 2 | 0.8190624549388056 |
| 14 | 1.0 | 1.000 | YES | 2 | 0.548195043565082 |
| 15 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 16 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 17 | 0.0 | 1.000 | NO | 8 | 1.0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 2 | 0.766830059715698 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 0.0 | 1.000 | NO | 8 | 0.6921917164279622 |
| 25 | 2.0 | 1.000 | NO | 2 | 0.47282799675031056 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 28 | 2.0 | 1.000 | NO | 9 | 0.3419773732231183 |
| 29 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 31 | 2.0 | 2.000 | YES | 2 | 0.5050235345111509 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 35 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 36 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 37 | 0.0 | 0.000 | YES | 5 | 1.0 |
| 38 | 0.0 | 0.000 | YES | 6 | 1.0 |
| 39 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 2.0 | 2.000 | YES | 3 | 0.24938316595536447 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 46 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 48 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 49 | 1.0 | 0.000 | NO | 0 | 0.0 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
