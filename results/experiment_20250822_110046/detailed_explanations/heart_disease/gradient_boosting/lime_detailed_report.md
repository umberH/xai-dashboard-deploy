# Detailed Explanation Report

**Dataset:** heart_disease  
**Model:** gradient_boosting  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:01:11  

## Summary Statistics

- **Total Instances:** 60
- **Valid Explanations:** 60
- **Errors:** 0
- **Model Accuracy:** 0.7000
- **Average Feature Importance:** 0.0900
- **Feature Importance Std:** 0.2440
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 42 (70.0%)
- **Incorrect Predictions:** 18 (30.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 60 | 0.0596 | 100.0% |
| 1 | 60 | 0.0087 | 100.0% |
| 2 | 60 | 0.1160 | 100.0% |
| 3 | 60 | 0.2377 | 100.0% |
| 4 | 60 | 0.0281 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.916', '0.084']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.689', '0.311']
- **Top Features:**
  - Feature 3: 0.9116
  - Feature 2: 0.0537
  - Feature 1: 0.0347

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.817', '0.183']
- **Top Features:**
  - Feature 2: 0.5187
  - Feature 0: 0.3963
  - Feature 3: 0.0850

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.736', '0.264']
- **Top Features:**
  - Feature 3: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.968', '0.032']
- **Top Features:**
  - Feature 3: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.350', '0.650']
- **Top Features:**
  - Feature 0: 0.7212
  - Feature 3: 0.1459
  - Feature 2: 0.1329

#### Instance 9

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.292', '0.708']
- **Top Features:**
  - Feature 3: 0.5112
  - Feature 2: 0.4888
  - Feature 0: 0.0000

#### Instance 10

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.802', '0.198']
- **Top Features:**
  - Feature 2: 0.8778
  - Feature 0: 0.1222
  - Feature 1: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 3 | 0.9116304562306236 |
| 2 | 0.0 | 0.000 | YES | 2 | 0.5187074829931972 |
| 3 | 0.0 | 1.000 | NO | 0 | 0.7212277343208069 |
| 4 | 0.0 | 0.000 | YES | 3 | 1.0 |
| 5 | 0.0 | 0.000 | YES | 3 | 1.0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 3 | 0.5904170790803919 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 1.000 | NO | 3 | 0.5111815897214785 |
| 10 | 1.0 | 0.000 | NO | 2 | 0.8777845982112554 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 13 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 14 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 1.000 | NO | 0 | 0.639069264069265 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 3 | 0.5486588707295488 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 3 | 1.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.9237217536186609 |
| 30 | 0.0 | 0.000 | YES | 3 | 0.9262153835164652 |
| 31 | 1.0 | 0.000 | NO | 3 | 1.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 0.0 | 0.000 | YES | 2 | 0.6250866854066219 |
| 34 | 0.0 | 0.000 | YES | 3 | 1.0 |
| 35 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 38 | 0.0 | 0.000 | YES | 3 | 1.0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 2 | 0.6280577418998645 |
| 43 | 1.0 | 0.000 | NO | 0 | 0.6659391181059539 |
| 44 | 0.0 | 1.000 | NO | 2 | 0.6896617346364255 |
| 45 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 0.0 | 1.000 | NO | 0 | 0.0 |

*Showing first 50 of 60 instances. See JSON file for complete data.*
