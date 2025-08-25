# Detailed Explanation Report

**Dataset:** breast_cancer  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:24:16  

## Summary Statistics

- **Total Instances:** 114
- **Valid Explanations:** 114
- **Errors:** 0
- **Model Accuracy:** 0.9561
- **Average Feature Importance:** 0.0114
- **Feature Importance Std:** 0.0657
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 109 (95.6%)
- **Incorrect Predictions:** 5 (4.4%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 104 | 0.0742 | 91.2% |
| 0 | 102 | 0.0437 | 89.5% |
| 1 | 89 | 0.0146 | 78.1% |
| 3 | 87 | 0.0071 | 76.3% |
| 4 | 78 | 0.0016 | 68.4% |
| 20 | 22 | 0.3177 | 19.3% |
| 23 | 10 | 0.1378 | 8.8% |
| 21 | 9 | 0.1351 | 7.9% |
| 10 | 6 | 0.3224 | 5.3% |
| 12 | 6 | 0.1603 | 5.3% |

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
  - Feature 20: 0.3046
  - Feature 2: 0.2756
  - Feature 0: 0.1741

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
  - Feature 0: 0.2372
  - Feature 2: 0.1427
  - Feature 20: 0.1248

#### Instance 21

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.367', '0.633']
- **Top Features:**
  - Feature 23: 0.2297
  - Feature 20: 0.1867
  - Feature 0: 0.1701

#### Instance 35

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.363', '0.637']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 20 | 0.3046387272121033 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 1.0 | 1.000 | YES | 10 | 0.27422625802357226 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 0.0 | 0.000 | YES | 1 | 0.316781910792711 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0.37663399521494084 |
| 16 | 1.0 | 0.000 | NO | 0 | 0.2372478151436635 |
| 17 | 1.0 | 1.000 | YES | 1 | 0.27173717215274124 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 1.000 | NO | 23 | 0.22971982342032238 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 10 | 0.5366488141137575 |
| 25 | 1.0 | 1.000 | YES | 20 | 0.29796498517071 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 1.0 | 1.000 | YES | 18 | 0.6666666666666666 |
| 28 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 10 | 0.5714285714285714 |
| 30 | 1.0 | 1.000 | YES | 5 | 0.4360410949218008 |
| 31 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 21 | 0.5689923645692623 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 36 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 1.0 | 1.000 | YES | 20 | 1.0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 2 | 0.8571428571428571 |
| 43 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 1.0 | 1.000 | YES | 0 | 0.36580741278139145 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 48 | 1.0 | 1.000 | YES | 20 | 0.3510769620494158 |
| 49 | 0.0 | 0.000 | YES | 24 | 1.0 |

*Showing first 50 of 114 instances. See JSON file for complete data.*
