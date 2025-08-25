# Detailed Explanation Report

**Dataset:** imdb  
**Model:** svm_text  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 05:11:57  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8050
- **Average Feature Importance:** 0.0104
- **Feature Importance Std:** 0.0031
- **Max Feature Importance:** 0.1673

## Prediction Analysis

- **Correct Predictions:** 161 (80.5%)
- **Incorrect Predictions:** 39 (19.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 68 | 0.0144 | 34.0% |
| 2 | 48 | 0.0150 | 24.0% |
| 0 | 37 | 0.0131 | 18.5% |
| 98 | 27 | 0.0118 | 13.5% |
| 50 | 22 | 0.0121 | 11.0% |
| 97 | 22 | 0.0120 | 11.0% |
| 99 | 20 | 0.0121 | 10.0% |
| 4 | 17 | 0.0138 | 8.5% |
| 39 | 15 | 0.0136 | 7.5% |
| 33 | 15 | 0.0124 | 7.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.986', '0.014']
- **Top Features:**
  - Feature 50: 0.0124
  - Feature 39: 0.0117
  - Feature 48: 0.0117

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.078', '0.922']
- **Top Features:**
  - Feature 80: 0.0117
  - Feature 32: 0.0114
  - Feature 42: 0.0114

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.067', '0.933']
- **Top Features:**
  - Feature 32: 0.0115
  - Feature 77: 0.0115
  - Feature 98: 0.0113

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.009', '0.991']
- **Top Features:**
  - Feature 7: 0.0270
  - Feature 0: 0.0264
  - Feature 43: 0.0260

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.044', '0.956']
- **Top Features:**
  - Feature 41: 0.0131
  - Feature 73: 0.0120
  - Feature 46: 0.0115

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.706', '0.294']
- **Top Features:**
  - Feature 1: 0.0120
  - Feature 97: 0.0114
  - Feature 12: 0.0112

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.322', '0.678']
- **Top Features:**
  - Feature 92: 0.0129
  - Feature 30: 0.0127
  - Feature 81: 0.0121

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.829', '0.171']
- **Top Features:**
  - Feature 21: 0.0122
  - Feature 71: 0.0112
  - Feature 16: 0.0110

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 50 | 0.012396919469078992 |
| 1 | 1.0 | 1.000 | YES | 80 | 0.011687641811649063 |
| 2 | 1.0 | 0.000 | NO | 1 | 0.01195015677454666 |
| 3 | 1.0 | 1.000 | YES | 32 | 0.011486551564742728 |
| 4 | 1.0 | 1.000 | YES | 7 | 0.02701568822561661 |
| 5 | 1.0 | 1.000 | YES | 41 | 0.013123898256514216 |
| 6 | 1.0 | 1.000 | YES | 39 | 0.018729204564783566 |
| 7 | 0.0 | 1.000 | NO | 92 | 0.012920651197724209 |
| 8 | 1.0 | 0.000 | NO | 21 | 0.01219256693878532 |
| 9 | 1.0 | 1.000 | YES | 38 | 0.012348333468604809 |
| 10 | 0.0 | 0.000 | YES | 60 | 0.01231156552455833 |
| 11 | 0.0 | 0.000 | YES | 6 | 0.012784072035477389 |
| 12 | 1.0 | 1.000 | YES | 55 | 0.014439492936444453 |
| 13 | 1.0 | 1.000 | YES | 1 | 0.012466467658217064 |
| 14 | 0.0 | 0.000 | YES | 1 | 0.011533867408574693 |
| 15 | 0.0 | 0.000 | YES | 45 | 0.014890878376971834 |
| 16 | 1.0 | 1.000 | YES | 7 | 0.011750561843652254 |
| 17 | 0.0 | 1.000 | NO | 57 | 0.012367420339445162 |
| 18 | 1.0 | 0.000 | NO | 7 | 0.011681949879133565 |
| 19 | 0.0 | 1.000 | NO | 21 | 0.012783013812122438 |
| 20 | 1.0 | 1.000 | YES | 58 | 0.012048633787858476 |
| 21 | 0.0 | 0.000 | YES | 34 | 0.012203941985407214 |
| 22 | 1.0 | 1.000 | YES | 80 | 0.0120368221530242 |
| 23 | 1.0 | 0.000 | NO | 55 | 0.011114021820057836 |
| 24 | 0.0 | 0.000 | YES | 79 | 0.012509462138353581 |
| 25 | 1.0 | 1.000 | YES | 2 | 0.012404494952374084 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.012790624134486376 |
| 27 | 0.0 | 0.000 | YES | 19 | 0.01202848662217748 |
| 28 | 0.0 | 1.000 | NO | 51 | 0.01985160644223442 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.016445981986376642 |
| 30 | 0.0 | 0.000 | YES | 10 | 0.02947481243301179 |
| 31 | 0.0 | 0.000 | YES | 33 | 0.012990997716682651 |
| 32 | 0.0 | 0.000 | YES | 17 | 0.012431399508344636 |
| 33 | 0.0 | 1.000 | NO | 0 | 0.012149400533625673 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.011284347273154771 |
| 35 | 0.0 | 0.000 | YES | 79 | 0.011786958420722934 |
| 36 | 1.0 | 0.000 | NO | 0 | 0.014185398088717976 |
| 37 | 1.0 | 1.000 | YES | 39 | 0.012907969460711271 |
| 38 | 1.0 | 1.000 | YES | 11 | 0.012035358165418916 |
| 39 | 0.0 | 0.000 | YES | 29 | 0.011762920239811795 |
| 40 | 0.0 | 0.000 | YES | 68 | 0.011662282819221674 |
| 41 | 0.0 | 1.000 | NO | 69 | 0.011222419841523288 |
| 42 | 1.0 | 1.000 | YES | 16 | 0.014694162246127747 |
| 43 | 1.0 | 1.000 | YES | 4 | 0.012493375935228701 |
| 44 | 0.0 | 0.000 | YES | 59 | 0.012794512416438489 |
| 45 | 0.0 | 1.000 | NO | 45 | 0.013113142284941046 |
| 46 | 1.0 | 1.000 | YES | 7 | 0.013039994899271332 |
| 47 | 1.0 | 1.000 | YES | 60 | 0.013073438527029354 |
| 48 | 1.0 | 1.000 | YES | 31 | 0.013015244252798732 |
| 49 | 0.0 | 0.000 | YES | 52 | 0.012132203590838204 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
