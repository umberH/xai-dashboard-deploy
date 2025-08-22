# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:18:52  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.6375
- **Average Feature Importance:** 0.0909
- **Feature Importance Std:** 0.2054
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 204 (63.7%)
- **Incorrect Predictions:** 116 (36.2%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 201 | 0.3388 | 62.8% |
| 0 | 186 | 0.0633 | 58.1% |
| 7 | 167 | 0.1151 | 52.2% |
| 8 | 160 | 0.0553 | 50.0% |
| 4 | 148 | 0.0637 | 46.2% |
| 10 | 146 | 0.7166 | 45.6% |
| 6 | 143 | 0.3624 | 44.7% |
| 9 | 130 | 0.2480 | 40.6% |
| 2 | 125 | 0.0172 | 39.1% |
| 5 | 108 | 0.0423 | 33.8% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.2454908014455746
- **Prediction Probabilities:** ['1.245']
- **Top Features:**
  - Feature 10: 0.8585
  - Feature 0: 0.0397
  - Feature 4: 0.0312

#### Instance 2

- **True Label:** 0.0
- **Prediction:** -0.074243013988612
- **Prediction Probabilities:** ['-0.074']
- **Top Features:**
  - Feature 1: 0.7495
  - Feature 7: 0.2079
  - Feature 8: 0.0424

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.34263686960739365
- **Prediction Probabilities:** ['0.343']
- **Top Features:**
  - Feature 1: 0.7174
  - Feature 7: 0.2054
  - Feature 0: 0.0304

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.118043609529831
- **Prediction Probabilities:** ['1.118']
- **Top Features:**
  - Feature 10: 0.8867
  - Feature 4: 0.0547
  - Feature 0: 0.0346

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.04649308636080407
- **Prediction Probabilities:** ['0.046']
- **Top Features:**
  - Feature 6: 0.5294
  - Feature 1: 0.3311
  - Feature 7: 0.0496

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.64681275757956
- **Prediction Probabilities:** ['0.647']
- **Top Features:**
  - Feature 10: 0.8170
  - Feature 1: 0.0870
  - Feature 4: 0.0770

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.49436565303495084
- **Prediction Probabilities:** ['0.494']
- **Top Features:**
  - Feature 9: 0.7155
  - Feature 7: 0.2412
  - Feature 8: 0.0391

#### Instance 9

- **True Label:** 2.0
- **Prediction:** 0.8197238398038897
- **Prediction Probabilities:** ['0.820']
- **Top Features:**
  - Feature 10: 0.4980
  - Feature 1: 0.1524
  - Feature 6: 0.0692

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.245 | YES | 10 | 0.858536572038951 |
| 1 | 0.0 | 0.647 | NO | 10 | 0.8169985070036647 |
| 2 | 0.0 | -0.074 | YES | 1 | 0.7495205628958475 |
| 3 | 0.0 | 0.343 | YES | 1 | 0.7173746292009114 |
| 4 | 1.0 | 0.494 | NO | 9 | 0.7154724857314558 |
| 5 | 1.0 | 1.118 | YES | 10 | 0.8867177487089257 |
| 6 | 0.0 | 0.046 | YES | 6 | 0.5293904668783032 |
| 7 | 0.0 | 0.056 | YES | 1 | 0.6033551193804809 |
| 8 | 1.0 | 1.201 | YES | 10 | 0.9589954607308435 |
| 9 | 2.0 | 0.820 | NO | 10 | 0.4979707425528779 |
| 10 | 0.0 | 0.264 | YES | 1 | 0.6627488584876035 |
| 11 | 1.0 | 1.062 | YES | 10 | 0.8533781639916928 |
| 12 | 0.0 | 0.154 | YES | 1 | 0.4390089053729319 |
| 13 | 0.0 | -0.199 | YES | 1 | 0.39525935184980454 |
| 14 | 0.0 | 0.166 | YES | 6 | 0.9652833429221707 |
| 15 | 1.0 | 1.335 | YES | 10 | 0.8126604213333029 |
| 16 | 1.0 | 0.373 | NO | 1 | 0.5478861117579646 |
| 17 | 0.0 | 0.346 | YES | 1 | 0.3132018930054501 |
| 18 | 2.0 | 1.343 | NO | 10 | 0.7755959650932037 |
| 19 | 0.0 | -0.497 | YES | 6 | 0.48918381510419773 |
| 20 | 1.0 | 1.038 | YES | 10 | 0.6648583072162156 |
| 21 | 1.0 | 0.762 | YES | 10 | 0.6505175620749 |
| 22 | 0.0 | 0.403 | YES | 6 | 0.35361865213808175 |
| 23 | 1.0 | 0.503 | YES | 6 | 0.9724949319820905 |
| 24 | 0.0 | 0.186 | YES | 6 | 0.657106817046593 |
| 25 | 1.0 | 0.498 | NO | 9 | 0.5208569985699487 |
| 26 | 1.0 | 0.649 | YES | 1 | 0.6465833503454527 |
| 27 | 0.0 | -0.091 | YES | 1 | 0.4311343493559974 |
| 28 | 2.0 | 1.210 | NO | 10 | 0.7191741929094867 |
| 29 | 0.0 | 0.059 | YES | 1 | 0.42329813374734987 |
| 30 | 0.0 | 0.193 | YES | 6 | 0.5935225437967965 |
| 31 | 0.0 | 0.358 | YES | 1 | 0.6326181395920235 |
| 32 | 1.0 | 0.279 | NO | 1 | 0.7727967312000652 |
| 33 | 1.0 | 1.024 | YES | 10 | 0.6999790244912546 |
| 34 | 2.0 | 1.463 | NO | 10 | 0.7885324145286104 |
| 35 | 0.0 | 0.393 | YES | 6 | 0.3831122036288923 |
| 36 | 0.0 | 0.204 | YES | 6 | 0.6425211564190665 |
| 37 | 1.0 | 0.932 | YES | 10 | 0.7921066336975058 |
| 38 | 0.0 | 0.077 | YES | 1 | 0.5278304409129383 |
| 39 | 0.0 | -0.179 | YES | 6 | 0.30001484839926396 |
| 40 | 0.0 | 0.316 | YES | 1 | 0.7598810602500982 |
| 41 | 0.0 | 0.520 | NO | 10 | 0.6375334576280507 |
| 42 | 1.0 | 0.330 | NO | 4 | 0.7077964293044745 |
| 43 | 1.0 | 0.745 | YES | 10 | 0.9767985077442762 |
| 44 | 2.0 | 1.532 | YES | 10 | 0.7543524313510154 |
| 45 | 2.0 | 1.108 | NO | 9 | 0.6898356862921705 |
| 46 | 1.0 | 0.055 | NO | 6 | 0.5681462293370971 |
| 47 | 1.0 | 0.885 | YES | 10 | 0.7499406180397375 |
| 48 | 1.0 | 0.157 | NO | 1 | 0.7393315662415808 |
| 49 | 2.0 | 1.535 | YES | 10 | 0.8328638269835272 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
