# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** gradient_boosting  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:17:21  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.7000
- **Average Feature Importance:** 0.0349
- **Feature Importance Std:** 0.1435
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 224 (70.0%)
- **Incorrect Predictions:** 96 (30.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 300 | 0.0540 | 93.8% |
| 0 | 287 | 0.0083 | 89.7% |
| 2 | 271 | 0.0155 | 84.7% |
| 3 | 263 | 0.0129 | 82.2% |
| 4 | 252 | 0.0842 | 78.8% |
| 8 | 62 | 0.3671 | 19.4% |
| 6 | 44 | 0.4276 | 13.8% |
| 7 | 40 | 0.1431 | 12.5% |
| 10 | 37 | 0.4391 | 11.6% |
| 9 | 25 | 0.3223 | 7.8% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.093', '0.535', '0.373']
- **Top Features:**
  - Feature 9: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.503', '0.470', '0.026']
- **Top Features:**
  - Feature 4: 0.7306
  - Feature 1: 0.1347
  - Feature 10: 0.1347

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.951', '0.041', '0.008']
- **Top Features:**
  - Feature 7: 0.6571
  - Feature 8: 0.3429
  - Feature 0: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.637', '0.345', '0.018']
- **Top Features:**
  - Feature 4: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.117', '0.581', '0.301']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.515', '0.434', '0.050']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 9

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.211', '0.638', '0.151']
- **Top Features:**
  - Feature 6: 0.3436
  - Feature 10: 0.3362
  - Feature 3: 0.1203

#### Instance 15

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.073', '0.180', '0.747']
- **Top Features:**
  - Feature 10: 0.9117
  - Feature 8: 0.0683
  - Feature 9: 0.0200

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 9 | 1.0 |
| 1 | 0.0 | 0.000 | YES | 4 | 0.7306397306397312 |
| 2 | 0.0 | 0.000 | YES | 7 | 0.6571063445269946 |
| 3 | 0.0 | 0.000 | YES | 4 | 1.0 |
| 4 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 6 | 0.6076790066869572 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 2.0 | 1.000 | NO | 6 | 0.3435584071196023 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 11 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 8 | 0.8621173011977825 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 6 | 1.0 |
| 15 | 1.0 | 2.000 | NO | 10 | 0.9116809179859967 |
| 16 | 1.0 | 0.000 | NO | 8 | 0.8316498316498316 |
| 17 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 18 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 1.0 | 1.000 | YES | 9 | 0.9406888008801856 |
| 21 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 22 | 0.0 | 0.000 | YES | 9 | 1.0 |
| 23 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 1.000 | YES | 1 | 1.0 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 1 | 0.4474955334367097 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 4 | 0.9564200280949231 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 1 | 0.41830647108936436 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 1 | 0.9096228693972603 |
| 41 | 0.0 | 1.000 | NO | 10 | 0.4374112872743575 |
| 42 | 1.0 | 0.000 | NO | 4 | 1.0 |
| 43 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 44 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 45 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 46 | 1.0 | 0.000 | NO | 1 | 0.8727306709987533 |
| 47 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 48 | 1.0 | 1.000 | YES | 4 | 0.8950990381769414 |
| 49 | 2.0 | 2.000 | YES | 0 | 0.0 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
