# Detailed Explanation Report

**Dataset:** heart_disease  
**Model:** random_forest  
**Explanation Method:** lime  
**Generated:** 2025-08-22 13:58:01  

## Summary Statistics

- **Total Instances:** 60
- **Valid Explanations:** 60
- **Errors:** 0
- **Model Accuracy:** 0.7333
- **Average Feature Importance:** 0.0633
- **Feature Importance Std:** 0.1879
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 44 (73.3%)
- **Incorrect Predictions:** 16 (26.7%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 60 | 0.1221 | 100.0% |
| 1 | 60 | 0.0091 | 100.0% |
| 2 | 60 | 0.0347 | 100.0% |
| 3 | 60 | 0.0440 | 100.0% |
| 4 | 60 | 0.1067 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.710', '0.290']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.642', '0.358']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.742', '0.258']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.656', '0.344']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.985', '0.015']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.456', '0.544']
- **Top Features:**
  - Feature 0: 0.8180
  - Feature 3: 0.1484
  - Feature 2: 0.0336

#### Instance 9

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.465', '0.535']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 10

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.627', '0.373']
- **Top Features:**
  - Feature 4: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 3 | 0.0 | 1.000 | NO | 0 | 0.8180251647734289 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 4 | 1.0 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 13 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 14 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 2 | 0.7861099155577435 |
| 16 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 1.000 | NO | 0 | 0.6502056959103395 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 4 | 0.9234879859851661 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 3 | 0.5037899597780079 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.778471149043546 |
| 27 | 1.0 | 1.000 | YES | 4 | 0.9531355381970528 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 4 | 0.5790875401647552 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.9305377663887379 |
| 31 | 1.0 | 0.000 | NO | 0 | 0.8305978485643678 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.635083831512403 |
| 37 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.5947789584153224 |
| 40 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 4 | 0.45837192111128616 |
| 43 | 1.0 | 0.000 | NO | 3 | 0.7680067805002944 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.536085529001472 |
| 45 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 0.0 | 1.000 | NO | 0 | 0.0 |

*Showing first 50 of 60 instances. See JSON file for complete data.*
