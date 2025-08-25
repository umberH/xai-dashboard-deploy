# Detailed Explanation Report

**Dataset:** digits  
**Model:** mlp  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:52:20  

## Summary Statistics

- **Total Instances:** 360
- **Valid Explanations:** 360
- **Errors:** 0
- **Model Accuracy:** 0.9778
- **Average Feature Importance:** 0.0021
- **Feature Importance Std:** 0.0227
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 352 (97.8%)
- **Incorrect Predictions:** 8 (2.2%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 3 | 322 | 0.0040 | 89.4% |
| 0 | 319 | 0.0064 | 88.6% |
| 2 | 318 | 0.0025 | 88.3% |
| 1 | 316 | 0.0000 | 87.8% |
| 4 | 316 | 0.0025 | 87.8% |
| 29 | 12 | 0.2008 | 3.3% |
| 20 | 11 | 0.1585 | 3.1% |
| 27 | 11 | 0.1557 | 3.1% |
| 21 | 10 | 0.1307 | 2.8% |
| 12 | 10 | 0.1199 | 2.8% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 5.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '0.996', '0.000', '0.000', '0.000', '0.004']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

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
- **Prediction Probabilities:** ['0.000', '0.003', '0.000', '0.000', '0.002', '0.000', '0.000', '0.000', '0.994', '0.000']
- **Top Features:**
  - Feature 29: 0.3119
  - Feature 21: 0.1881
  - Feature 50: 0.1881

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.002', '0.945', '0.000', '0.000', '0.000', '0.000', '0.016', '0.000', '0.037', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 7.0
- **Prediction:** 7.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.6250
  - Feature 7: 0.3750
  - Feature 1: 0.0000

### Incorrect Predictions (Sample)

#### Instance 36

- **True Label:** 6.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.047', '0.003', '0.000', '0.000', '0.071', '0.002', '0.144', '0.001', '0.733', '0.000']
- **Top Features:**
  - Feature 12: 0.2592
  - Feature 34: 0.1332
  - Feature 36: 0.1198

#### Instance 51

- **True Label:** 8.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.009', '0.967', '0.000', '0.000', '0.015', '0.000', '0.002', '0.000', '0.003', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 93

- **True Label:** 9.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.000', '0.001', '0.001', '0.000', '0.041', '0.000', '0.000', '0.064', '0.615', '0.278']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 1 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 2 | 8.0 | 8.000 | YES | 29 | 0.31186868686868685 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 4 | 7.0 | 7.000 | YES | 0 | 0.625 |
| 5 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 6 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 7 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 8 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 9 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 11 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 12 | 9.0 | 9.000 | YES | 0 | 0.0 |
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
| 23 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 24 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 25 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 26 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 3.0 | 3.000 | YES | 0 | 0.0 |
| 29 | 4.0 | 4.000 | YES | 0 | 0.0 |
| 30 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 31 | 7.0 | 7.000 | YES | 0 | 0.0 |
| 32 | 2.0 | 2.000 | YES | 42 | 0.22507993912755814 |
| 33 | 6.0 | 6.000 | YES | 51 | 1.0 |
| 34 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 35 | 6.0 | 6.000 | YES | 33 | 0.30691002703317755 |
| 36 | 6.0 | 8.000 | NO | 12 | 0.2591905449048416 |
| 37 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 9.0 | 9.000 | YES | 0 | 0.0 |
| 40 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 41 | 7.0 | 7.000 | YES | 37 | 0.17683997520429892 |
| 42 | 9.0 | 9.000 | YES | 0 | 0.0 |
| 43 | 6.0 | 6.000 | YES | 0 | 0.0 |
| 44 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 45 | 7.0 | 7.000 | YES | 0 | 0.0 |
| 46 | 5.0 | 5.000 | YES | 0 | 0.0 |
| 47 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 48 | 7.0 | 7.000 | YES | 36 | 0.20194522941944476 |
| 49 | 5.0 | 5.000 | YES | 0 | 0.0 |

*Showing first 50 of 360 instances. See JSON file for complete data.*
