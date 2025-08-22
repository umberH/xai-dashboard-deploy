# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** gradient_boosting  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:24:24  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.5393
- **Average Feature Importance:** 0.0539
- **Feature Importance Std:** 0.1737
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 48 (53.9%)
- **Incorrect Predictions:** 41 (46.1%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 84 | 0.1948 | 94.4% |
| 3 | 77 | 0.0503 | 86.5% |
| 0 | 75 | 0.0525 | 84.3% |
| 1 | 71 | 0.0159 | 79.8% |
| 4 | 60 | 0.0176 | 67.4% |
| 8 | 26 | 0.3398 | 29.2% |
| 5 | 17 | 0.1561 | 19.1% |
| 7 | 12 | 0.0651 | 13.5% |
| 6 | 12 | 0.6277 | 13.5% |
| 9 | 11 | 0.0940 | 12.4% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.040', '0.059', '0.902']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.960', '0.033', '0.007']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.321', '0.449', '0.230']
- **Top Features:**
  - Feature 8: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.222', '0.694', '0.084']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 9

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.986', '0.011', '0.003']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.109', '0.187', '0.704']
- **Top Features:**
  - Feature 5: 0.5464
  - Feature 4: 0.1591
  - Feature 2: 0.1222

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.083', '0.216', '0.701']
- **Top Features:**
  - Feature 8: 0.5691
  - Feature 2: 0.4142
  - Feature 3: 0.0167

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.970', '0.026', '0.004']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 2.000 | NO | 5 | 0.5464317945632167 |
| 1 | 0.0 | 2.000 | NO | 8 | 0.5691391602065881 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 8 | 1.0 |
| 6 | 2.0 | 1.000 | NO | 8 | 0.6083615371970079 |
| 7 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 11 | 0.0 | 0.000 | YES | 6 | 1.0 |
| 12 | 0.0 | 0.000 | YES | 6 | 0.8025434522334132 |
| 13 | 2.0 | 0.000 | NO | 2 | 0.7026584958486087 |
| 14 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 15 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 16 | 0.0 | 0.000 | YES | 8 | 0.5795967923147352 |
| 17 | 0.0 | 1.000 | NO | 2 | 0.5568602954320804 |
| 18 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 1 | 0.3877665544332212 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 0.0 | 0.000 | YES | 8 | 0.5075816927336695 |
| 25 | 2.0 | 1.000 | NO | 2 | 0.5346627188680864 |
| 26 | 1.0 | 0.000 | NO | 2 | 0.8601822332775888 |
| 27 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 28 | 2.0 | 2.000 | YES | 3 | 0.33631416499055017 |
| 29 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 6 | 0.3437061592061603 |
| 31 | 2.0 | 2.000 | YES | 2 | 0.5669459853485785 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 0.000 | NO | 6 | 1.0 |
| 34 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 35 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 36 | 1.0 | 1.000 | YES | 8 | 0.5736006704486952 |
| 37 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 1.0 | 0.000 | NO | 3 | 0.42577875974805474 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 2.000 | NO | 3 | 0.4484208933883684 |
| 43 | 2.0 | 1.000 | NO | 3 | 0.6556033196615714 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 0.0 | 2.000 | NO | 2 | 0.7114949150818466 |
| 46 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 48 | 0.0 | 0.000 | YES | 6 | 1.0 |
| 49 | 1.0 | 0.000 | NO | 3 | 0.7071552021251695 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
