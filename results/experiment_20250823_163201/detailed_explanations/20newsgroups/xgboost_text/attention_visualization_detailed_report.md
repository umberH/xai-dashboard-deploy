# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** xgboost_text  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 15:42:28  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7050
- **Average Feature Importance:** 0.0383
- **Feature Importance Std:** 0.0689
- **Max Feature Importance:** 3.0000

## Prediction Analysis

- **Correct Predictions:** 141 (70.5%)
- **Incorrect Predictions:** 59 (29.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 72 | 0.1204 | 36.0% |
| 0 | 51 | 0.4386 | 25.5% |
| 2 | 49 | 0.0961 | 24.5% |
| 15 | 20 | 0.0618 | 10.0% |
| 12 | 19 | 0.0781 | 9.5% |
| 25 | 19 | 0.0424 | 9.5% |
| 3 | 19 | 0.1757 | 9.5% |
| 9 | 17 | 0.1023 | 8.5% |
| 13 | 17 | 0.0727 | 8.5% |
| 21 | 16 | 0.0634 | 8.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.293', '0.219', '0.371', '0.117']
- **Top Features:**
  - Feature 22: 0.0867
  - Feature 61: 0.0558
  - Feature 41: 0.0540

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.059', '0.065', '0.850', '0.026']
- **Top Features:**
  - Feature 21: 0.0353
  - Feature 64: 0.0353
  - Feature 55: 0.0345

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.679', '0.119', '0.132', '0.069']
- **Top Features:**
  - Feature 41: 0.0220
  - Feature 33: 0.0210
  - Feature 44: 0.0210

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.004', '0.002', '0.002', '0.992']
- **Top Features:**
  - Feature 1: 0.0548
  - Feature 4: 0.0548
  - Feature 14: 0.0548

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.465', '0.169', '0.205', '0.161']
- **Top Features:**
  - Feature 11: 0.0167
  - Feature 2: 0.0163
  - Feature 50: 0.0163

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.193', '0.215', '0.288', '0.304']
- **Top Features:**
  - Feature 2: 0.1359
  - Feature 28: 0.1039
  - Feature 46: 0.1001

#### Instance 14

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.396', '0.207', '0.276', '0.120']
- **Top Features:**
  - Feature 31: 0.0122
  - Feature 58: 0.0122
  - Feature 97: 0.0118

#### Instance 15

- **True Label:** 0.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.140', '0.365', '0.424', '0.071']
- **Top Features:**
  - Feature 98: 0.0351
  - Feature 34: 0.0343
  - Feature 57: 0.0343

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 22 | 0.08665438713998662 |
| 1 | 2.0 | 2.000 | YES | 21 | 0.03529600513396438 |
| 2 | 2.0 | 3.000 | NO | 2 | 0.1358566116884355 |
| 3 | 0.0 | 0.000 | YES | 41 | 0.022013207924754852 |
| 4 | 3.0 | 3.000 | YES | 1 | 0.05482326864580632 |
| 5 | 0.0 | 0.000 | YES | 11 | 0.016687364172617198 |
| 6 | 1.0 | 1.000 | YES | 25 | 0.021498263601786007 |
| 7 | 3.0 | 3.000 | YES | 57 | 0.14916467780429596 |
| 8 | 2.0 | 2.000 | YES | 4 | 0.7311411992263055 |
| 9 | 2.0 | 2.000 | YES | 0 | 3.0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0.025985013294657962 |
| 11 | 3.0 | 3.000 | YES | 33 | 0.062311616044516585 |
| 12 | 2.0 | 2.000 | YES | 11 | 0.07263085081853815 |
| 13 | 3.0 | 3.000 | YES | 15 | 0.0782119021134594 |
| 14 | 1.0 | 0.000 | NO | 31 | 0.012202397093117847 |
| 15 | 0.0 | 2.000 | NO | 98 | 0.03511009415206873 |
| 16 | 1.0 | 1.000 | YES | 48 | 0.012970168612191958 |
| 17 | 3.0 | 3.000 | YES | 1 | 0.0986635572697103 |
| 18 | 0.0 | 1.000 | NO | 4 | 0.07509209407764239 |
| 19 | 0.0 | 3.000 | NO | 45 | 0.0622055164381386 |
| 20 | 2.0 | 2.000 | YES | 35 | 0.03483410258643212 |
| 21 | 3.0 | 3.000 | YES | 35 | 0.0620381603617514 |
| 22 | 1.0 | 1.000 | YES | 92 | 0.014242115971515767 |
| 23 | 0.0 | 0.000 | YES | 22 | 0.07184846505551926 |
| 24 | 2.0 | 2.000 | YES | 48 | 0.07114889808703434 |
| 25 | 1.0 | 1.000 | YES | 64 | 0.011656907395358924 |
| 26 | 1.0 | 0.000 | NO | 20 | 0.022935779816513763 |
| 27 | 3.0 | 3.000 | YES | 30 | 0.1510574018126888 |
| 28 | 2.0 | 0.000 | NO | 33 | 0.011367279722521788 |
| 29 | 0.0 | 0.000 | YES | 2 | 0.10055570256681662 |
| 30 | 1.0 | 1.000 | YES | 2 | 0.024854117138534686 |
| 31 | 3.0 | 3.000 | YES | 56 | 0.07371073228262034 |
| 32 | 0.0 | 3.000 | NO | 32 | 0.17090206568583738 |
| 33 | 2.0 | 1.000 | NO | 38 | 0.027458020910339 |
| 34 | 2.0 | 2.000 | YES | 97 | 0.0361100800678721 |
| 35 | 0.0 | 0.000 | YES | 29 | 0.012594458438287152 |
| 36 | 2.0 | 2.000 | YES | 5 | 0.554140127388535 |
| 37 | 0.0 | 3.000 | NO | 64 | 0.11375837210491334 |
| 38 | 2.0 | 0.000 | NO | 1 | 0.1839717741935484 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.12327981651376148 |
| 40 | 2.0 | 1.000 | NO | 1 | 0.011195870811036474 |
| 41 | 0.0 | 3.000 | NO | 16 | 0.11912497292614249 |
| 42 | 2.0 | 2.000 | YES | 37 | 0.03546285594199853 |
| 43 | 3.0 | 3.000 | YES | 97 | 0.05988189193664109 |
| 44 | 2.0 | 1.000 | NO | 1 | 0.011374838856449535 |
| 45 | 2.0 | 2.000 | YES | 96 | 0.03597877749530231 |
| 46 | 3.0 | 3.000 | YES | 58 | 0.061529205863049656 |
| 47 | 1.0 | 1.000 | YES | 5 | 0.07081436519979768 |
| 48 | 3.0 | 2.000 | NO | 36 | 0.141602634467618 |
| 49 | 1.0 | 1.000 | YES | 76 | 0.015407037268373931 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
