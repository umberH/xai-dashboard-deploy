# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** lstm  
**Explanation Method:** lime  
**Generated:** 2025-08-24 15:44:02  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7800
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0291
- **Max Feature Importance:** 0.9978

## Prediction Analysis

- **Correct Predictions:** 156 (78.0%)
- **Incorrect Predictions:** 44 (22.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 3 | 58 | 0.0639 | 29.0% |
| 0 | 51 | 0.0632 | 25.5% |
| 4 | 50 | 0.0670 | 25.0% |
| 2 | 45 | 0.0623 | 22.5% |
| 1 | 44 | 0.0639 | 22.0% |
| 7 | 35 | 0.0862 | 17.5% |
| 11 | 31 | 0.0973 | 15.5% |
| 19 | 30 | 0.0747 | 15.0% |
| 8 | 29 | 0.0827 | 14.5% |
| 14 | 29 | 0.0912 | 14.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.145', '0.400', '0.191', '0.265']
- **Top Features:**
  - Feature 15: 0.2339
  - Feature 29: 0.1201
  - Feature 8: 0.0629

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.030', '0.899', '0.030', '0.041']
- **Top Features:**
  - Feature 0: 0.0444
  - Feature 1: 0.0434
  - Feature 2: 0.0424

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.633', '0.099', '0.165', '0.103']
- **Top Features:**
  - Feature 15: 0.0669
  - Feature 31: 0.0586
  - Feature 34: 0.0527

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.143', '0.754', '0.054', '0.050']
- **Top Features:**
  - Feature 4: 0.0688
  - Feature 20: 0.0645
  - Feature 7: 0.0639

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.104', '0.562', '0.159', '0.175']
- **Top Features:**
  - Feature 0: 0.1063
  - Feature 22: 0.0861
  - Feature 3: 0.0710

### Incorrect Predictions (Sample)

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.358', '0.330', '0.172', '0.139']
- **Top Features:**
  - Feature 7: 0.1384
  - Feature 28: 0.1356
  - Feature 29: 0.1197

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.034', '0.032', '0.067', '0.866']
- **Top Features:**
  - Feature 32: 0.0530
  - Feature 9: 0.0527
  - Feature 5: 0.0491

#### Instance 15

- **True Label:** 3.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.107', '0.356', '0.190', '0.348']
- **Top Features:**
  - Feature 5: 0.1229
  - Feature 31: 0.1100
  - Feature 19: 0.1054

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 15 | 0.23393914097708757 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.044444444444444446 |
| 2 | 0.0 | 0.000 | YES | 15 | 0.06688882515090229 |
| 3 | 1.0 | 1.000 | YES | 4 | 0.06878442838434067 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.10630835268496998 |
| 5 | 1.0 | 0.000 | NO | 7 | 0.13836289888123163 |
| 6 | 2.0 | 3.000 | NO | 32 | 0.053017619340530335 |
| 7 | 1.0 | 1.000 | YES | 32 | 0.09914351515360127 |
| 8 | 0.0 | 0.000 | YES | 0 | 0.14474614406475014 |
| 9 | 3.0 | 3.000 | YES | 16 | 0.09290366735869068 |
| 10 | 3.0 | 3.000 | YES | 13 | 0.07758492411546919 |
| 11 | 3.0 | 3.000 | YES | 25 | 0.1350516222362176 |
| 12 | 1.0 | 1.000 | YES | 31 | 0.0656276540922338 |
| 13 | 2.0 | 2.000 | YES | 2 | 0.06862107150252028 |
| 14 | 3.0 | 3.000 | YES | 0 | 0.044444444444444446 |
| 15 | 3.0 | 1.000 | NO | 5 | 0.12285618645324813 |
| 16 | 2.0 | 2.000 | YES | 19 | 0.21051271734091048 |
| 17 | 0.0 | 0.000 | YES | 5 | 0.14809296400585875 |
| 18 | 1.0 | 1.000 | YES | 17 | 0.2312675931689546 |
| 19 | 2.0 | 2.000 | YES | 0 | 0.058823529411764705 |
| 20 | 1.0 | 1.000 | YES | 30 | 0.09986835456078573 |
| 21 | 2.0 | 2.000 | YES | 10 | 0.08711526322003509 |
| 22 | 2.0 | 3.000 | NO | 3 | 0.0947718823775708 |
| 23 | 3.0 | 3.000 | YES | 2 | 0.13260221924326293 |
| 24 | 0.0 | 0.000 | YES | 2 | 0.1822689931271508 |
| 25 | 2.0 | 3.000 | NO | 28 | 0.1421144776759026 |
| 26 | 0.0 | 0.000 | YES | 40 | 0.13684207702537862 |
| 27 | 2.0 | 2.000 | YES | 20 | 0.05281484495299408 |
| 28 | 3.0 | 3.000 | YES | 9 | 0.1912055294767848 |
| 29 | 2.0 | 2.000 | YES | 11 | 0.05685414170974964 |
| 30 | 3.0 | 3.000 | YES | 20 | 0.14406628255903464 |
| 31 | 0.0 | 0.000 | YES | 21 | 0.0851392734662199 |
| 32 | 2.0 | 3.000 | NO | 25 | 0.05608574435782444 |
| 33 | 3.0 | 3.000 | YES | 8 | 0.0821740391355898 |
| 34 | 0.0 | 1.000 | NO | 0 | 0.07407407407407407 |
| 35 | 1.0 | 1.000 | YES | 33 | 0.07015652109904412 |
| 36 | 3.0 | 3.000 | YES | 8 | 0.12710117069320048 |
| 37 | 2.0 | 2.000 | YES | 10 | 0.08789856881208802 |
| 38 | 3.0 | 3.000 | YES | 22 | 0.19645970269683458 |
| 39 | 3.0 | 0.000 | NO | 6 | 0.12677785428088445 |
| 40 | 2.0 | 2.000 | YES | 38 | 0.21455578499715064 |
| 41 | 2.0 | 2.000 | YES | 7 | 0.07128256547755449 |
| 42 | 2.0 | 2.000 | YES | 30 | 0.08658770288950098 |
| 43 | 2.0 | 2.000 | YES | 0 | 0.047619047619047616 |
| 44 | 2.0 | 2.000 | YES | 0 | 0.05263157894736842 |
| 45 | 1.0 | 1.000 | YES | 16 | 0.05893967946209384 |
| 46 | 2.0 | 2.000 | YES | 1 | 0.07646210839801233 |
| 47 | 1.0 | 1.000 | YES | 33 | 0.10398755465716915 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.05555555555555555 |
| 49 | 0.0 | 2.000 | NO | 14 | 0.22587992802522275 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
