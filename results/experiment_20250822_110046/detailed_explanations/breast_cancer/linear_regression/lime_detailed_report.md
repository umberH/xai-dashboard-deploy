# Detailed Explanation Report

**Dataset:** breast_cancer  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-22 13:56:35  

## Summary Statistics

- **Total Instances:** 114
- **Valid Explanations:** 114
- **Errors:** 0
- **Model Accuracy:** 0.9561
- **Average Feature Importance:** 0.0117
- **Feature Importance Std:** 0.0666
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 109 (95.6%)
- **Incorrect Predictions:** 5 (4.4%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 103 | 0.0708 | 90.4% |
| 0 | 101 | 0.0537 | 88.6% |
| 1 | 90 | 0.0094 | 78.9% |
| 3 | 86 | 0.0038 | 75.4% |
| 4 | 75 | 0.0000 | 65.8% |
| 20 | 22 | 0.3320 | 19.3% |
| 5 | 9 | 0.3929 | 7.9% |
| 23 | 8 | 0.2130 | 7.0% |
| 17 | 8 | 0.1755 | 7.0% |
| 16 | 6 | 0.1918 | 5.3% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.480', '0.520']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.240', '0.760']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.443', '0.557']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.347', '0.653']
- **Top Features:**
  - Feature 20: 0.2888
  - Feature 0: 0.2160
  - Feature 23: 0.1563

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.586', '0.414']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 16

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.380', '0.620']
- **Top Features:**
  - Feature 2: 0.5220
  - Feature 20: 0.1426
  - Feature 0: 0.1416

#### Instance 21

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.367', '0.633']
- **Top Features:**
  - Feature 20: 0.3271
  - Feature 23: 0.2332
  - Feature 3: 0.1424

#### Instance 35

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.363', '0.637']
- **Top Features:**
  - Feature 5: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 20 | 0.2888163347008043 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 1.0 | 1.000 | YES | 10 | 0.33876297244612447 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 0.0 | 0.000 | YES | 2 | 0.6666666666666666 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 1.000 | YES | 17 | 1.0 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0.5572315090471983 |
| 16 | 1.0 | 0.000 | NO | 2 | 0.5219655075133771 |
| 17 | 1.0 | 1.000 | YES | 5 | 0.5982814263014223 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 1.000 | NO | 20 | 0.3271479354014838 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 10 | 0.45017113401838915 |
| 25 | 1.0 | 1.000 | YES | 23 | 0.3503935065138824 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 28 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 30 | 1.0 | 1.000 | YES | 5 | 0.5926317508791977 |
| 31 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 16 | 0.47669540217289674 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 1.000 | NO | 5 | 1.0 |
| 36 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 1.0 | 1.000 | YES | 5 | 0.39854477873623634 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 1.0 | 1.000 | YES | 20 | 0.29985036273952653 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 48 | 1.0 | 1.000 | YES | 2 | 0.24248336745208485 |
| 49 | 0.0 | 0.000 | YES | 20 | 0.6099773242630386 |

*Showing first 50 of 114 instances. See JSON file for complete data.*
