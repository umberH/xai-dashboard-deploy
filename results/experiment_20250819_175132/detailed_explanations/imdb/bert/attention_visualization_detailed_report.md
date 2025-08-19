# Detailed Explanation Report

**Dataset:** imdb  
**Model:** bert  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-19 18:35:01  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8100
- **Average Feature Importance:** 0.0104
- **Feature Importance Std:** 0.0030
- **Max Feature Importance:** 0.1424

## Prediction Analysis

- **Correct Predictions:** 162 (81.0%)
- **Incorrect Predictions:** 38 (19.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 69 | 0.0137 | 34.5% |
| 2 | 48 | 0.0148 | 24.0% |
| 0 | 36 | 0.0127 | 18.0% |
| 50 | 25 | 0.0121 | 12.5% |
| 98 | 25 | 0.0117 | 12.5% |
| 97 | 22 | 0.0120 | 11.0% |
| 99 | 20 | 0.0119 | 10.0% |
| 4 | 17 | 0.0142 | 8.5% |
| 31 | 16 | 0.0120 | 8.0% |
| 44 | 15 | 0.0144 | 7.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.753', '0.247']
- **Top Features:**
  - Feature 50: 0.0124
  - Feature 39: 0.0117
  - Feature 48: 0.0117

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.320', '0.680']
- **Top Features:**
  - Feature 80: 0.0117
  - Feature 32: 0.0114
  - Feature 42: 0.0114

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.350', '0.650']
- **Top Features:**
  - Feature 32: 0.0115
  - Feature 77: 0.0115
  - Feature 98: 0.0113

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.259', '0.741']
- **Top Features:**
  - Feature 7: 0.0270
  - Feature 0: 0.0264
  - Feature 43: 0.0260

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.371', '0.629']
- **Top Features:**
  - Feature 41: 0.0131
  - Feature 73: 0.0120
  - Feature 46: 0.0115

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.510', '0.490']
- **Top Features:**
  - Feature 1: 0.0119
  - Feature 97: 0.0114
  - Feature 12: 0.0111

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.405', '0.595']
- **Top Features:**
  - Feature 92: 0.0129
  - Feature 30: 0.0127
  - Feature 81: 0.0121

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.656', '0.344']
- **Top Features:**
  - Feature 21: 0.0132
  - Feature 71: 0.0118
  - Feature 16: 0.0115

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 50 | 0.012396919469078992 |
| 1 | 1.0 | 1.000 | YES | 80 | 0.011687641811649063 |
| 2 | 1.0 | 0.000 | NO | 1 | 0.011876902146086436 |
| 3 | 1.0 | 1.000 | YES | 32 | 0.011486551564742728 |
| 4 | 1.0 | 1.000 | YES | 7 | 0.02701568822561661 |
| 5 | 1.0 | 1.000 | YES | 41 | 0.013123898256514216 |
| 6 | 1.0 | 1.000 | YES | 39 | 0.018729204564783566 |
| 7 | 0.0 | 1.000 | NO | 92 | 0.012920651197724209 |
| 8 | 1.0 | 0.000 | NO | 21 | 0.013153929287839906 |
| 9 | 1.0 | 1.000 | YES | 38 | 0.012348333468604809 |
| 10 | 0.0 | 0.000 | YES | 60 | 0.01231156552455833 |
| 11 | 0.0 | 0.000 | YES | 6 | 0.012784072035477389 |
| 12 | 1.0 | 1.000 | YES | 55 | 0.014439492936444453 |
| 13 | 1.0 | 1.000 | YES | 1 | 0.012466467658217064 |
| 14 | 0.0 | 0.000 | YES | 1 | 0.011533867408574693 |
| 15 | 0.0 | 0.000 | YES | 45 | 0.014890878376971834 |
| 16 | 1.0 | 1.000 | YES | 7 | 0.011750561843652254 |
| 17 | 0.0 | 1.000 | NO | 57 | 0.012367420339445162 |
| 18 | 1.0 | 1.000 | YES | 7 | 0.01186073243636116 |
| 19 | 0.0 | 1.000 | NO | 21 | 0.012783013812122438 |
| 20 | 1.0 | 1.000 | YES | 58 | 0.01145942166361974 |
| 21 | 0.0 | 0.000 | YES | 87 | 0.013771377771768782 |
| 22 | 1.0 | 1.000 | YES | 80 | 0.011416720063928586 |
| 23 | 1.0 | 1.000 | YES | 55 | 0.011555499846587625 |
| 24 | 0.0 | 0.000 | YES | 79 | 0.012509462138353581 |
| 25 | 1.0 | 1.000 | YES | 2 | 0.012404494952374084 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.012790624134486376 |
| 27 | 0.0 | 0.000 | YES | 19 | 0.01202848662217748 |
| 28 | 0.0 | 1.000 | NO | 51 | 0.01985160644223442 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.012978369826203718 |
| 30 | 0.0 | 0.000 | YES | 10 | 0.02947481243301179 |
| 31 | 0.0 | 0.000 | YES | 33 | 0.012990997716682651 |
| 32 | 0.0 | 0.000 | YES | 17 | 0.012431399508344636 |
| 33 | 0.0 | 1.000 | NO | 0 | 0.012149400533625673 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.011284347273154771 |
| 35 | 0.0 | 0.000 | YES | 65 | 0.01504110470343655 |
| 36 | 1.0 | 1.000 | YES | 74 | 0.015816776515508026 |
| 37 | 1.0 | 1.000 | YES | 39 | 0.012907969460711271 |
| 38 | 1.0 | 1.000 | YES | 11 | 0.012035358165418916 |
| 39 | 0.0 | 0.000 | YES | 29 | 0.011762920239811795 |
| 40 | 0.0 | 0.000 | YES | 68 | 0.011662282819221674 |
| 41 | 0.0 | 1.000 | NO | 69 | 0.01129114606887345 |
| 42 | 1.0 | 1.000 | YES | 51 | 0.012934578128756823 |
| 43 | 1.0 | 1.000 | YES | 4 | 0.012493375935228701 |
| 44 | 0.0 | 0.000 | YES | 59 | 0.012794512416438489 |
| 45 | 0.0 | 0.000 | YES | 45 | 0.013113142284941046 |
| 46 | 1.0 | 1.000 | YES | 7 | 0.013039994899271332 |
| 47 | 1.0 | 1.000 | YES | 43 | 0.014914984932671519 |
| 48 | 1.0 | 1.000 | YES | 31 | 0.013015244252798732 |
| 49 | 0.0 | 0.000 | YES | 52 | 0.012132203590838204 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
