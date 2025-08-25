# Detailed Explanation Report

**Dataset:** digits  
**Model:** logistic_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:53:44  

## Summary Statistics

- **Total Instances:** 360
- **Valid Explanations:** 360
- **Errors:** 0
- **Model Accuracy:** 0.9722
- **Average Feature Importance:** 0.0030
- **Feature Importance Std:** 0.0256
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 350 (97.2%)
- **Incorrect Predictions:** 10 (2.8%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 308 | 0.0068 | 85.6% |
| 3 | 306 | 0.0053 | 85.0% |
| 0 | 304 | 0.0010 | 84.4% |
| 4 | 300 | 0.0027 | 83.3% |
| 1 | 298 | 0.0000 | 82.8% |
| 38 | 18 | 0.2269 | 5.0% |
| 21 | 15 | 0.1605 | 4.2% |
| 27 | 14 | 0.1691 | 3.9% |
| 51 | 14 | 0.2165 | 3.9% |
| 20 | 13 | 0.1754 | 3.6% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 5.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '0.918', '0.000', '0.000', '0.000', '0.081']
- **Top Features:**
  - Feature 38: 0.1363
  - Feature 27: 0.1254
  - Feature 5: 0.1037

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.996', '0.001', '0.000', '0.001', '0.000', '0.000', '0.002', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 8.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.000', '0.066', '0.000', '0.001', '0.001', '0.000', '0.003', '0.003', '0.915', '0.009']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 7.0
- **Prediction:** 7.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.001', '0.000', '0.000', '0.000', '0.999', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.782', '0.218', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.005', '0.218', '0.003', '0.000', '0.005', '0.007', '0.173', '0.014', '0.575', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 36

- **True Label:** 6.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.127', '0.010', '0.000', '0.000', '0.007', '0.001', '0.102', '0.001', '0.753', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 51

- **True Label:** 8.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.007', '0.914', '0.000', '0.000', '0.022', '0.000', '0.001', '0.000', '0.035', '0.021']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 5.0 | 5.000 | YES | 38 | 0.13628036363002155 |
| 1 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 2 | 8.0 | 8.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 8.000 | NO | 0 | 0.0 |
| 4 | 7.0 | 7.000 | YES | 0 | 0.0 |
| 5 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 6 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 7 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 8 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 9 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 11 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 12 | 9.0 | 9.000 | YES | 0 | 0.0 |
| 13 | 3.0 | 3.000 | YES | 0 | 0.0 |
| 14 | 4.0 | 4.000 | YES | 26 | 0.23089758677510958 |
| 15 | 4.0 | 4.000 | YES | 0 | 0.0 |
| 16 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 17 | 4.0 | 4.000 | YES | 0 | 0.0 |
| 18 | 9.0 | 9.000 | YES | 0 | 0.0 |
| 19 | 9.0 | 9.000 | YES | 19 | 1.0 |
| 20 | 6.0 | 6.000 | YES | 51 | 0.2600805282480619 |
| 21 | 3.0 | 3.000 | YES | 0 | 0.0 |
| 22 | 8.0 | 8.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 24 | 2.0 | 2.000 | YES | 51 | 0.29846272631451404 |
| 25 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 26 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 2 | 0.3648805185765907 |
| 28 | 3.0 | 3.000 | YES | 2 | 0.2589675602809345 |
| 29 | 4.0 | 4.000 | YES | 0 | 0.0 |
| 30 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 31 | 7.0 | 7.000 | YES | 20 | 0.21564771418737788 |
| 32 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 33 | 6.0 | 6.000 | YES | 38 | 0.28700182173870536 |
| 34 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 35 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 36 | 6.0 | 8.000 | NO | 0 | 0.0 |
| 37 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 9.0 | 9.000 | YES | 0 | 0.0 |
| 40 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 41 | 7.0 | 7.000 | YES | 20 | 0.40580048884597275 |
| 42 | 9.0 | 9.000 | YES | 0 | 0.0 |
| 43 | 6.0 | 6.000 | YES | 54 | 0.4257703993055448 |
| 44 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 45 | 7.0 | 7.000 | YES | 44 | 0.2625368728498184 |
| 46 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 47 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 48 | 7.0 | 7.000 | YES | 43 | 0.23208635235607464 |
| 49 | 5.0 | 5.000 | YES | 0 | 0.0 |

*Showing first 50 of 360 instances. See JSON file for complete data.*
