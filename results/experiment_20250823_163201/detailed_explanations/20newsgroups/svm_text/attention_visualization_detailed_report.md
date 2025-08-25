# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** svm_text  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 15:39:45  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7950
- **Average Feature Importance:** 0.0399
- **Feature Importance Std:** 0.0770
- **Max Feature Importance:** 3.0000

## Prediction Analysis

- **Correct Predictions:** 159 (79.5%)
- **Incorrect Predictions:** 41 (20.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 68 | 0.1544 | 34.0% |
| 2 | 51 | 0.1179 | 25.5% |
| 0 | 51 | 0.4661 | 25.5% |
| 9 | 23 | 0.1332 | 11.5% |
| 99 | 21 | 0.0329 | 10.5% |
| 25 | 20 | 0.0537 | 10.0% |
| 15 | 20 | 0.0807 | 10.0% |
| 3 | 19 | 0.2006 | 9.5% |
| 13 | 18 | 0.0714 | 9.0% |
| 21 | 17 | 0.0665 | 8.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.017', '0.018', '0.953', '0.012']
- **Top Features:**
  - Feature 61: 0.0565
  - Feature 41: 0.0547
  - Feature 2: 0.0535

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.001', '0.001', '0.997', '0.000']
- **Top Features:**
  - Feature 21: 0.0353
  - Feature 64: 0.0353
  - Feature 55: 0.0345

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.060', '0.025', '0.502', '0.412']
- **Top Features:**
  - Feature 28: 0.0628
  - Feature 46: 0.0605
  - Feature 2: 0.0591

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.979', '0.006', '0.004', '0.012']
- **Top Features:**
  - Feature 41: 0.0220
  - Feature 33: 0.0210
  - Feature 44: 0.0210

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.024', '0.003', '0.006', '0.968']
- **Top Features:**
  - Feature 1: 0.0606
  - Feature 4: 0.0606
  - Feature 14: 0.0606

### Incorrect Predictions (Sample)

#### Instance 11

- **True Label:** 3.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.550', '0.009', '0.039', '0.402']
- **Top Features:**
  - Feature 7: 0.0187
  - Feature 79: 0.0184
  - Feature 25: 0.0123

#### Instance 12

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.327', '0.027', '0.173', '0.473']
- **Top Features:**
  - Feature 46: 0.2333
  - Feature 42: 0.2322
  - Feature 40: 0.2296

#### Instance 14

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.341', '0.160', '0.242', '0.257']
- **Top Features:**
  - Feature 63: 0.0215
  - Feature 65: 0.0215
  - Feature 89: 0.0215

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 61 | 0.056517311608961306 |
| 1 | 2.0 | 2.000 | YES | 21 | 0.03529600513396438 |
| 2 | 2.0 | 2.000 | YES | 28 | 0.06283024305889134 |
| 3 | 0.0 | 0.000 | YES | 41 | 0.022013207924754852 |
| 4 | 3.0 | 3.000 | YES | 1 | 0.06058484571059292 |
| 5 | 0.0 | 0.000 | YES | 11 | 0.016687364172617198 |
| 6 | 1.0 | 1.000 | YES | 25 | 0.021498263601786007 |
| 7 | 3.0 | 3.000 | YES | 72 | 0.07410401509027217 |
| 8 | 2.0 | 2.000 | YES | 4 | 0.7311411992263055 |
| 9 | 2.0 | 2.000 | YES | 0 | 3.0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0.025985013294657962 |
| 11 | 3.0 | 0.000 | NO | 7 | 0.01867264191207853 |
| 12 | 2.0 | 3.000 | NO | 46 | 0.2332700021110407 |
| 13 | 3.0 | 3.000 | YES | 15 | 0.0782119021134594 |
| 14 | 1.0 | 0.000 | NO | 63 | 0.021535719590078717 |
| 15 | 0.0 | 2.000 | NO | 21 | 0.05714588073443039 |
| 16 | 1.0 | 1.000 | YES | 48 | 0.012970168612191958 |
| 17 | 3.0 | 3.000 | YES | 1 | 0.0986635572697103 |
| 18 | 0.0 | 1.000 | NO | 9 | 0.09498540726983284 |
| 19 | 0.0 | 3.000 | NO | 45 | 0.0622055164381386 |
| 20 | 2.0 | 2.000 | YES | 41 | 0.041735780405586176 |
| 21 | 3.0 | 3.000 | YES | 35 | 0.0620381603617514 |
| 22 | 1.0 | 1.000 | YES | 92 | 0.014242115971515767 |
| 23 | 0.0 | 3.000 | NO | 1 | 0.17845003399048265 |
| 24 | 2.0 | 2.000 | YES | 48 | 0.07114889808703434 |
| 25 | 1.0 | 1.000 | YES | 64 | 0.011656907395358924 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.019776322967812333 |
| 27 | 3.0 | 3.000 | YES | 30 | 0.1510574018126888 |
| 28 | 2.0 | 2.000 | YES | 33 | 0.037359900373599 |
| 29 | 0.0 | 0.000 | YES | 2 | 0.08110300081103002 |
| 30 | 1.0 | 1.000 | YES | 2 | 0.024854117138534686 |
| 31 | 3.0 | 3.000 | YES | 38 | 0.06326047162700549 |
| 32 | 0.0 | 3.000 | NO | 32 | 0.17090206568583738 |
| 33 | 2.0 | 2.000 | YES | 40 | 0.07668548301203536 |
| 34 | 2.0 | 2.000 | YES | 97 | 0.0361100800678721 |
| 35 | 0.0 | 0.000 | YES | 29 | 0.012594458438287152 |
| 36 | 2.0 | 2.000 | YES | 5 | 0.554140127388535 |
| 37 | 0.0 | 0.000 | YES | 41 | 0.019808340917608008 |
| 38 | 2.0 | 2.000 | YES | 2 | 0.5450581395348838 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.12327981651376148 |
| 40 | 2.0 | 2.000 | YES | 1 | 0.035151779388522535 |
| 41 | 0.0 | 0.000 | YES | 16 | 0.0238249945852285 |
| 42 | 2.0 | 2.000 | YES | 37 | 0.03546285594199853 |
| 43 | 3.0 | 3.000 | YES | 97 | 0.05988189193664109 |
| 44 | 2.0 | 3.000 | NO | 1 | 0.05960767313319605 |
| 45 | 2.0 | 2.000 | YES | 96 | 0.03597877749530231 |
| 46 | 3.0 | 3.000 | YES | 58 | 0.061529205863049656 |
| 47 | 1.0 | 1.000 | YES | 20 | 0.054723799690242644 |
| 48 | 3.0 | 1.000 | NO | 31 | 0.04850389397458669 |
| 49 | 1.0 | 1.000 | YES | 76 | 0.015407037268373931 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
