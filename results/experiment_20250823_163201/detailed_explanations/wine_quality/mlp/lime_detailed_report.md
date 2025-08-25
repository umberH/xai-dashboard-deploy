# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** mlp  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:32:35  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.6906
- **Average Feature Importance:** 0.0318
- **Feature Importance Std:** 0.1188
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 221 (69.1%)
- **Incorrect Predictions:** 99 (30.9%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 290 | 0.0310 | 90.6% |
| 1 | 279 | 0.0246 | 87.2% |
| 2 | 278 | 0.0376 | 86.9% |
| 3 | 249 | 0.0104 | 77.8% |
| 4 | 244 | 0.0218 | 76.2% |
| 8 | 66 | 0.3982 | 20.6% |
| 10 | 52 | 0.3040 | 16.2% |
| 9 | 43 | 0.2590 | 13.4% |
| 7 | 41 | 0.1702 | 12.8% |
| 6 | 32 | 0.3635 | 10.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '0.943', '0.056']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.891', '0.106', '0.003']
- **Top Features:**
  - Feature 8: 0.6796
  - Feature 10: 0.1667
  - Feature 4: 0.0850

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.715', '0.283', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.230', '0.714', '0.056']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.566', '0.122', '0.311']
- **Top Features:**
  - Feature 10: 0.5200
  - Feature 5: 0.4203
  - Feature 8: 0.0322

#### Instance 15

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.017', '0.159', '0.824']
- **Top Features:**
  - Feature 10: 0.3843
  - Feature 2: 0.2408
  - Feature 9: 0.2401

#### Instance 16

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.855', '0.137', '0.008']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 8 | 0.6795707973911218 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 6 | 0.731360536842361 |
| 8 | 1.0 | 0.000 | NO | 10 | 0.5200236912241191 |
| 9 | 2.0 | 2.000 | YES | 9 | 0.3788240738859149 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 11 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 8 | 1.0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 2.000 | NO | 10 | 0.38431992473310406 |
| 16 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 17 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 18 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 1.0 | 1.000 | YES | 9 | 0.6264561164979685 |
| 21 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 1.000 | YES | 8 | 1.0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 2.0 | 1.000 | NO | 9 | 0.41571795233036635 |
| 29 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 4 | 0.3149863047557161 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 1.000 | YES | 10 | 0.4280524484074472 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 41 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 42 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 43 | 1.0 | 1.000 | YES | 8 | 1.0 |
| 44 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 45 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 46 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 47 | 1.0 | 1.000 | YES | 2 | 0.5006562645293796 |
| 48 | 1.0 | 1.000 | YES | 8 | 0.6829421731202209 |
| 49 | 2.0 | 2.000 | YES | 8 | 0.47544752779196797 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
