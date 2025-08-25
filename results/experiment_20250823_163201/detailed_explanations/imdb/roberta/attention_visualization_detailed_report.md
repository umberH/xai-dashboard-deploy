# Detailed Explanation Report

**Dataset:** imdb  
**Model:** roberta  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 05:07:30  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8700
- **Average Feature Importance:** 0.0104
- **Feature Importance Std:** 0.0030
- **Max Feature Importance:** 0.1655

## Prediction Analysis

- **Correct Predictions:** 174 (87.0%)
- **Incorrect Predictions:** 26 (13.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 66 | 0.0138 | 33.0% |
| 2 | 48 | 0.0148 | 24.0% |
| 0 | 35 | 0.0126 | 17.5% |
| 98 | 25 | 0.0115 | 12.5% |
| 97 | 23 | 0.0118 | 11.5% |
| 50 | 21 | 0.0118 | 10.5% |
| 99 | 20 | 0.0118 | 10.0% |
| 31 | 15 | 0.0123 | 7.5% |
| 4 | 15 | 0.0136 | 7.5% |
| 77 | 14 | 0.0126 | 7.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.907', '0.093']
- **Top Features:**
  - Feature 50: 0.0124
  - Feature 39: 0.0117
  - Feature 48: 0.0117

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.053', '0.947']
- **Top Features:**
  - Feature 80: 0.0117
  - Feature 32: 0.0114
  - Feature 42: 0.0114

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.033', '0.967']
- **Top Features:**
  - Feature 1: 0.0127
  - Feature 97: 0.0120
  - Feature 12: 0.0116

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.029', '0.971']
- **Top Features:**
  - Feature 32: 0.0115
  - Feature 77: 0.0115
  - Feature 98: 0.0113

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.033', '0.967']
- **Top Features:**
  - Feature 7: 0.0270
  - Feature 0: 0.0264
  - Feature 43: 0.0260

### Incorrect Predictions (Sample)

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.523', '0.477']
- **Top Features:**
  - Feature 7: 0.0147
  - Feature 21: 0.0131
  - Feature 71: 0.0117

#### Instance 16

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.712', '0.288']
- **Top Features:**
  - Feature 7: 0.0118
  - Feature 74: 0.0115
  - Feature 77: 0.0115

#### Instance 23

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.515', '0.485']
- **Top Features:**
  - Feature 55: 0.0111
  - Feature 92: 0.0111
  - Feature 50: 0.0110

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 50 | 0.012396919469078992 |
| 1 | 1.0 | 1.000 | YES | 80 | 0.011687641811649063 |
| 2 | 1.0 | 1.000 | YES | 1 | 0.012706422555234268 |
| 3 | 1.0 | 1.000 | YES | 32 | 0.011486551564742728 |
| 4 | 1.0 | 1.000 | YES | 7 | 0.02701568822561661 |
| 5 | 1.0 | 1.000 | YES | 41 | 0.013123898256514216 |
| 6 | 1.0 | 1.000 | YES | 39 | 0.018729204564783566 |
| 7 | 0.0 | 0.000 | YES | 92 | 0.01715365612776808 |
| 8 | 1.0 | 0.000 | NO | 7 | 0.014733569007193848 |
| 9 | 1.0 | 1.000 | YES | 38 | 0.012348333468604809 |
| 10 | 0.0 | 0.000 | YES | 60 | 0.01231156552455833 |
| 11 | 0.0 | 0.000 | YES | 6 | 0.012784072035477389 |
| 12 | 1.0 | 1.000 | YES | 55 | 0.014439492936444453 |
| 13 | 1.0 | 1.000 | YES | 1 | 0.012466467658217064 |
| 14 | 0.0 | 0.000 | YES | 1 | 0.011533867408574693 |
| 15 | 0.0 | 0.000 | YES | 45 | 0.014890878376971834 |
| 16 | 1.0 | 0.000 | NO | 7 | 0.011750561843652254 |
| 17 | 0.0 | 0.000 | YES | 57 | 0.012367420339445162 |
| 18 | 1.0 | 1.000 | YES | 7 | 0.012354521604261348 |
| 19 | 0.0 | 0.000 | YES | 21 | 0.016758388140078538 |
| 20 | 1.0 | 1.000 | YES | 58 | 0.012048633787858476 |
| 21 | 0.0 | 0.000 | YES | 87 | 0.013771377771768782 |
| 22 | 1.0 | 1.000 | YES | 80 | 0.0120368221530242 |
| 23 | 1.0 | 0.000 | NO | 55 | 0.011080051080890836 |
| 24 | 0.0 | 0.000 | YES | 79 | 0.012509462138353581 |
| 25 | 1.0 | 1.000 | YES | 2 | 0.012404494952374084 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.012790624134486376 |
| 27 | 0.0 | 0.000 | YES | 19 | 0.01202848662217748 |
| 28 | 0.0 | 0.000 | YES | 51 | 0.01985160644223442 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.012422756345448354 |
| 30 | 0.0 | 0.000 | YES | 10 | 0.02947481243301179 |
| 31 | 0.0 | 0.000 | YES | 33 | 0.012990997716682651 |
| 32 | 0.0 | 0.000 | YES | 17 | 0.012431399508344636 |
| 33 | 0.0 | 0.000 | YES | 0 | 0.0130870438336105 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.011837185716683839 |
| 35 | 0.0 | 0.000 | YES | 79 | 0.011786958420722934 |
| 36 | 1.0 | 1.000 | YES | 31 | 0.013035626939841383 |
| 37 | 1.0 | 1.000 | YES | 39 | 0.012907969460711271 |
| 38 | 1.0 | 1.000 | YES | 11 | 0.012035358165418916 |
| 39 | 0.0 | 0.000 | YES | 29 | 0.012531328320802004 |
| 40 | 0.0 | 0.000 | YES | 68 | 0.011662282819221674 |
| 41 | 0.0 | 0.000 | YES | 69 | 0.011757200693953425 |
| 42 | 1.0 | 0.000 | NO | 51 | 0.012934578128756823 |
| 43 | 1.0 | 0.000 | NO | 91 | 0.014925924602883155 |
| 44 | 0.0 | 0.000 | YES | 59 | 0.012794512416438489 |
| 45 | 0.0 | 0.000 | YES | 45 | 0.012166259836292494 |
| 46 | 1.0 | 1.000 | YES | 7 | 0.013039994899271332 |
| 47 | 1.0 | 0.000 | NO | 60 | 0.012177564304168973 |
| 48 | 1.0 | 1.000 | YES | 31 | 0.013015244252798732 |
| 49 | 0.0 | 0.000 | YES | 52 | 0.013060455243080821 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
