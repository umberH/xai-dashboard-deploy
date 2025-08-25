# Detailed Explanation Report

**Dataset:** digits  
**Model:** random_forest  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:39:02  

## Summary Statistics

- **Total Instances:** 360
- **Valid Explanations:** 360
- **Errors:** 0
- **Model Accuracy:** 0.9611
- **Average Feature Importance:** 0.0034
- **Feature Importance Std:** 0.0311
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 346 (96.1%)
- **Incorrect Predictions:** 14 (3.9%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 293 | 0.0004 | 81.4% |
| 3 | 290 | 0.0032 | 80.6% |
| 1 | 289 | 0.0002 | 80.3% |
| 2 | 289 | 0.0020 | 80.3% |
| 4 | 288 | 0.0055 | 80.0% |
| 29 | 28 | 0.2612 | 7.8% |
| 37 | 20 | 0.2552 | 5.6% |
| 19 | 20 | 0.2864 | 5.6% |
| 20 | 20 | 0.3383 | 5.6% |
| 12 | 14 | 0.1494 | 3.9% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 5.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.033', '0.010', '0.000', '0.031', '0.002', '0.529', '0.020', '0.010', '0.010', '0.355']
- **Top Features:**
  - Feature 29: 0.1930
  - Feature 46: 0.1923
  - Feature 45: 0.1055

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.030', '0.899', '0.021', '0.000', '0.020', '0.010', '0.010', '0.010', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 8.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.030', '0.146', '0.036', '0.022', '0.067', '0.024', '0.043', '0.013', '0.556', '0.062']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '0.579', '0.054', '0.010', '0.043', '0.050', '0.111', '0.030', '0.114', '0.010']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 7.0
- **Prediction:** 7.0
- **Prediction Probabilities:** ['0.020', '0.020', '0.036', '0.090', '0.030', '0.050', '0.031', '0.616', '0.066', '0.040']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 36

- **True Label:** 6.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.095', '0.089', '0.044', '0.004', '0.175', '0.083', '0.111', '0.086', '0.283', '0.030']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 51

- **True Label:** 8.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.051', '0.547', '0.026', '0.001', '0.045', '0.029', '0.062', '0.023', '0.196', '0.021']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 59

- **True Label:** 2.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.330', '0.010', '0.280', '0.060', '0.030', '0.010', '0.020', '0.030', '0.090', '0.140']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 5.0 | 5.000 | YES | 29 | 0.19301353884174055 |
| 1 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 2 | 8.0 | 8.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 4 | 7.0 | 7.000 | YES | 0 | 0.0 |
| 5 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 6 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 7 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 8 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 9 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 11 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 12 | 9.0 | 9.000 | YES | 37 | 0.4737854737855209 |
| 13 | 3.0 | 3.000 | YES | 0 | 0.0 |
| 14 | 4.0 | 4.000 | YES | 0 | 0.0 |
| 15 | 4.0 | 4.000 | YES | 0 | 0.0 |
| 16 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 17 | 4.0 | 4.000 | YES | 0 | 0.0 |
| 18 | 9.0 | 9.000 | YES | 0 | 0.0 |
| 19 | 9.0 | 9.000 | YES | 0 | 0.0 |
| 20 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 21 | 3.0 | 3.000 | YES | 0 | 0.0 |
| 22 | 8.0 | 8.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 1.000 | YES | 19 | 0.37335682818907057 |
| 24 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 25 | 5.0 | 5.000 | YES | 46 | 0.18531774514021135 |
| 26 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 3.0 | 3.000 | YES | 0 | 0.0 |
| 29 | 4.0 | 4.000 | YES | 0 | 0.0 |
| 30 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 31 | 7.0 | 7.000 | YES | 0 | 0.0 |
| 32 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 33 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 34 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 35 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 36 | 6.0 | 8.000 | NO | 0 | 0.0 |
| 37 | 5.0 | 5.000 | YES | 27 | 0.2872478523420134 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 9.0 | 9.000 | YES | 29 | 1.0 |
| 40 | 1.0 | 1.000 | YES | 20 | 0.4132875159512217 |
| 41 | 7.0 | 7.000 | YES | 35 | 0.3737373737373745 |
| 42 | 9.0 | 9.000 | YES | 20 | 0.2659863945578326 |
| 43 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 44 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 45 | 7.0 | 7.000 | YES | 0 | 0.0 |
| 46 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 47 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 48 | 7.0 | 7.000 | YES | 0 | 0.0 |
| 49 | 5.0 | 5.000 | YES | 0 | 0.0 |

*Showing first 50 of 360 instances. See JSON file for complete data.*
