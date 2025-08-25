# Detailed Explanation Report

**Dataset:** imdb  
**Model:** xgboost_text  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 05:14:26  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7900
- **Average Feature Importance:** 0.0104
- **Feature Importance Std:** 0.0030
- **Max Feature Importance:** 0.1424

## Prediction Analysis

- **Correct Predictions:** 158 (79.0%)
- **Incorrect Predictions:** 42 (21.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 67 | 0.0138 | 33.5% |
| 2 | 49 | 0.0148 | 24.5% |
| 0 | 32 | 0.0128 | 16.0% |
| 98 | 26 | 0.0120 | 13.0% |
| 97 | 23 | 0.0119 | 11.5% |
| 50 | 22 | 0.0119 | 11.0% |
| 99 | 18 | 0.0116 | 9.0% |
| 31 | 16 | 0.0121 | 8.0% |
| 4 | 15 | 0.0137 | 7.5% |
| 13 | 15 | 0.0129 | 7.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.849', '0.151']
- **Top Features:**
  - Feature 76: 0.0138
  - Feature 50: 0.0123
  - Feature 39: 0.0116

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.284', '0.716']
- **Top Features:**
  - Feature 80: 0.0117
  - Feature 32: 0.0114
  - Feature 42: 0.0114

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.256', '0.744']
- **Top Features:**
  - Feature 1: 0.0127
  - Feature 97: 0.0120
  - Feature 12: 0.0116

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.123', '0.877']
- **Top Features:**
  - Feature 32: 0.0115
  - Feature 77: 0.0115
  - Feature 98: 0.0113

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.131', '0.869']
- **Top Features:**
  - Feature 7: 0.0270
  - Feature 0: 0.0264
  - Feature 43: 0.0260

### Incorrect Predictions (Sample)

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.276', '0.724']
- **Top Features:**
  - Feature 92: 0.0129
  - Feature 30: 0.0127
  - Feature 81: 0.0121

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.783', '0.217']
- **Top Features:**
  - Feature 21: 0.0122
  - Feature 71: 0.0112
  - Feature 16: 0.0110

#### Instance 11

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.438', '0.562']
- **Top Features:**
  - Feature 6: 0.0119
  - Feature 19: 0.0110
  - Feature 26: 0.0110

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 76 | 0.013804927101101901 |
| 1 | 1.0 | 1.000 | YES | 80 | 0.011687641811649063 |
| 2 | 1.0 | 1.000 | YES | 1 | 0.012706422555234268 |
| 3 | 1.0 | 1.000 | YES | 32 | 0.011486551564742728 |
| 4 | 1.0 | 1.000 | YES | 7 | 0.02701568822561661 |
| 5 | 1.0 | 1.000 | YES | 41 | 0.013123898256514216 |
| 6 | 1.0 | 1.000 | YES | 39 | 0.018729204564783566 |
| 7 | 0.0 | 1.000 | NO | 92 | 0.012920651197724209 |
| 8 | 1.0 | 0.000 | NO | 21 | 0.01219256693878532 |
| 9 | 1.0 | 1.000 | YES | 38 | 0.012348333468604809 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.015392510042072134 |
| 11 | 0.0 | 1.000 | NO | 6 | 0.011939846208505913 |
| 12 | 1.0 | 1.000 | YES | 55 | 0.014439492936444453 |
| 13 | 1.0 | 1.000 | YES | 1 | 0.012466467658217064 |
| 14 | 0.0 | 0.000 | YES | 1 | 0.011533867408574693 |
| 15 | 0.0 | 0.000 | YES | 60 | 0.0157434138552138 |
| 16 | 1.0 | 0.000 | NO | 21 | 0.014420201168917143 |
| 17 | 0.0 | 1.000 | NO | 57 | 0.012367420339445162 |
| 18 | 1.0 | 1.000 | YES | 7 | 0.011717273906616707 |
| 19 | 0.0 | 1.000 | NO | 21 | 0.012783013812122438 |
| 20 | 1.0 | 1.000 | YES | 58 | 0.012048633787858476 |
| 21 | 0.0 | 0.000 | YES | 34 | 0.012203941985407214 |
| 22 | 1.0 | 1.000 | YES | 80 | 0.0120368221530242 |
| 23 | 1.0 | 1.000 | YES | 55 | 0.011555499846587625 |
| 24 | 0.0 | 0.000 | YES | 79 | 0.012509462138353581 |
| 25 | 1.0 | 1.000 | YES | 2 | 0.012404494952374084 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.012790624134486376 |
| 27 | 0.0 | 0.000 | YES | 19 | 0.01202848662217748 |
| 28 | 0.0 | 1.000 | NO | 51 | 0.01985160644223442 |
| 29 | 1.0 | 0.000 | NO | 70 | 0.014801279814633883 |
| 30 | 0.0 | 1.000 | NO | 10 | 0.02947481243301179 |
| 31 | 0.0 | 0.000 | YES | 17 | 0.014282379193672494 |
| 32 | 0.0 | 0.000 | YES | 30 | 0.0155396442103319 |
| 33 | 0.0 | 1.000 | NO | 0 | 0.0130870438336105 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.011284347273154771 |
| 35 | 0.0 | 0.000 | YES | 23 | 0.013918835064514983 |
| 36 | 1.0 | 0.000 | NO | 31 | 0.012152937609897432 |
| 37 | 1.0 | 1.000 | YES | 39 | 0.012907969460711271 |
| 38 | 1.0 | 1.000 | YES | 11 | 0.012035358165418916 |
| 39 | 0.0 | 0.000 | YES | 29 | 0.011762920239811795 |
| 40 | 0.0 | 0.000 | YES | 15 | 0.014250760572391925 |
| 41 | 0.0 | 1.000 | NO | 69 | 0.011757200693953425 |
| 42 | 1.0 | 1.000 | YES | 51 | 0.012086913136002683 |
| 43 | 1.0 | 1.000 | YES | 4 | 0.012493375935228701 |
| 44 | 0.0 | 0.000 | YES | 79 | 0.014365285296463392 |
| 45 | 0.0 | 1.000 | NO | 45 | 0.013113142284941046 |
| 46 | 1.0 | 1.000 | YES | 7 | 0.01708953001997325 |
| 47 | 1.0 | 1.000 | YES | 60 | 0.013073438527029354 |
| 48 | 1.0 | 1.000 | YES | 31 | 0.013015244252798732 |
| 49 | 0.0 | 0.000 | YES | 52 | 0.012132203590838204 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
