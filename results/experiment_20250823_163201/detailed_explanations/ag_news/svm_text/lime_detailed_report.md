# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** svm_text  
**Explanation Method:** lime  
**Generated:** 2025-08-24 19:02:17  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7900
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0244
- **Max Feature Importance:** 0.3330

## Prediction Analysis

- **Correct Predictions:** 158 (79.0%)
- **Incorrect Predictions:** 42 (21.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 50 | 0.0708 | 25.0% |
| 3 | 49 | 0.0666 | 24.5% |
| 1 | 48 | 0.0636 | 24.0% |
| 4 | 48 | 0.0671 | 24.0% |
| 2 | 42 | 0.0636 | 21.0% |
| 8 | 36 | 0.0773 | 18.0% |
| 14 | 33 | 0.0740 | 16.5% |
| 7 | 29 | 0.0729 | 14.5% |
| 24 | 28 | 0.0783 | 14.0% |
| 23 | 28 | 0.0707 | 14.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.062', '0.677', '0.089', '0.172']
- **Top Features:**
  - Feature 15: 0.2293
  - Feature 28: 0.0911
  - Feature 8: 0.0648

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0444
  - Feature 1: 0.0434
  - Feature 2: 0.0424

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.937', '0.009', '0.045', '0.010']
- **Top Features:**
  - Feature 34: 0.0657
  - Feature 7: 0.0610
  - Feature 8: 0.0586

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.025', '0.972', '0.001', '0.001']
- **Top Features:**
  - Feature 13: 0.0739
  - Feature 22: 0.0664
  - Feature 28: 0.0624

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.059', '0.841', '0.068', '0.031']
- **Top Features:**
  - Feature 3: 0.1011
  - Feature 0: 0.0955
  - Feature 7: 0.0799

### Incorrect Predictions (Sample)

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.005', '0.995']
- **Top Features:**
  - Feature 20: 0.0634
  - Feature 37: 0.0557
  - Feature 3: 0.0534

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.766', '0.106', '0.079', '0.049']
- **Top Features:**
  - Feature 39: 0.1097
  - Feature 5: 0.0804
  - Feature 7: 0.0759

#### Instance 22

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.064', '0.036', '0.200', '0.701']
- **Top Features:**
  - Feature 3: 0.1504
  - Feature 28: 0.1440
  - Feature 17: 0.1114

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 15 | 0.22926552710410822 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.044444444444444446 |
| 2 | 0.0 | 0.000 | YES | 34 | 0.06572368092785795 |
| 3 | 1.0 | 1.000 | YES | 13 | 0.07391836441887836 |
| 4 | 1.0 | 1.000 | YES | 3 | 0.1011299188592565 |
| 5 | 1.0 | 1.000 | YES | 11 | 0.08081732414687919 |
| 6 | 2.0 | 3.000 | NO | 20 | 0.06335106196189262 |
| 7 | 1.0 | 0.000 | NO | 39 | 0.1097238491036527 |
| 8 | 0.0 | 0.000 | YES | 0 | 0.10646732817702097 |
| 9 | 3.0 | 3.000 | YES | 16 | 0.10149090770187767 |
| 10 | 3.0 | 3.000 | YES | 13 | 0.07089425839170505 |
| 11 | 3.0 | 3.000 | YES | 23 | 0.1506466870340996 |
| 12 | 1.0 | 1.000 | YES | 21 | 0.0634148765658704 |
| 13 | 2.0 | 2.000 | YES | 3 | 0.05855429701115938 |
| 14 | 3.0 | 3.000 | YES | 39 | 0.07230455571275039 |
| 15 | 3.0 | 3.000 | YES | 5 | 0.09855322427110365 |
| 16 | 2.0 | 2.000 | YES | 19 | 0.16249158272726044 |
| 17 | 0.0 | 0.000 | YES | 5 | 0.12171234936802637 |
| 18 | 1.0 | 1.000 | YES | 12 | 0.3329683496970641 |
| 19 | 2.0 | 2.000 | YES | 0 | 0.058823529411764705 |
| 20 | 1.0 | 1.000 | YES | 10 | 0.08118580889327956 |
| 21 | 2.0 | 2.000 | YES | 10 | 0.09761449822923578 |
| 22 | 2.0 | 3.000 | NO | 3 | 0.15043828026280193 |
| 23 | 3.0 | 3.000 | YES | 15 | 0.10992912839692487 |
| 24 | 0.0 | 0.000 | YES | 5 | 0.17103476963205758 |
| 25 | 2.0 | 3.000 | NO | 21 | 0.14058874969468516 |
| 26 | 0.0 | 0.000 | YES | 40 | 0.06564788267137589 |
| 27 | 2.0 | 2.000 | YES | 0 | 0.04081632653061224 |
| 28 | 3.0 | 3.000 | YES | 9 | 0.11498062431773588 |
| 29 | 2.0 | 2.000 | YES | 44 | 0.059896560285466055 |
| 30 | 3.0 | 3.000 | YES | 19 | 0.1250988685190434 |
| 31 | 0.0 | 0.000 | YES | 24 | 0.08458618672590103 |
| 32 | 2.0 | 3.000 | NO | 25 | 0.04466206704756415 |
| 33 | 3.0 | 3.000 | YES | 0 | 0.10652073555145354 |
| 34 | 0.0 | 1.000 | NO | 5 | 0.09196254729607249 |
| 35 | 1.0 | 1.000 | YES | 1 | 0.08342937934677394 |
| 36 | 3.0 | 3.000 | YES | 8 | 0.09065628923746503 |
| 37 | 2.0 | 2.000 | YES | 23 | 0.08142918740716157 |
| 38 | 3.0 | 3.000 | YES | 22 | 0.11261977660575383 |
| 39 | 3.0 | 0.000 | NO | 6 | 0.16600057110840957 |
| 40 | 2.0 | 2.000 | YES | 38 | 0.2567761237119744 |
| 41 | 2.0 | 2.000 | YES | 20 | 0.07438287243557896 |
| 42 | 2.0 | 2.000 | YES | 22 | 0.0660643063995939 |
| 43 | 2.0 | 2.000 | YES | 0 | 0.047619047619047616 |
| 44 | 2.0 | 2.000 | YES | 0 | 0.05263157894736842 |
| 45 | 1.0 | 1.000 | YES | 2 | 0.08074017362543327 |
| 46 | 2.0 | 2.000 | YES | 17 | 0.05511274493255927 |
| 47 | 1.0 | 1.000 | YES | 8 | 0.08864072388933805 |
| 48 | 1.0 | 1.000 | YES | 8 | 0.05692829991794191 |
| 49 | 0.0 | 0.000 | YES | 22 | 0.1849695840459776 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
