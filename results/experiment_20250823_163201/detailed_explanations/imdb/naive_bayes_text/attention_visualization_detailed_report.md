# Detailed Explanation Report

**Dataset:** imdb  
**Model:** naive_bayes_text  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 05:08:56  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8050
- **Average Feature Importance:** 0.0104
- **Feature Importance Std:** 0.0031
- **Max Feature Importance:** 0.1834

## Prediction Analysis

- **Correct Predictions:** 161 (80.5%)
- **Incorrect Predictions:** 39 (19.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 69 | 0.0138 | 34.5% |
| 2 | 49 | 0.0149 | 24.5% |
| 0 | 34 | 0.0126 | 17.0% |
| 98 | 27 | 0.0119 | 13.5% |
| 97 | 22 | 0.0119 | 11.0% |
| 50 | 20 | 0.0118 | 10.0% |
| 99 | 18 | 0.0117 | 9.0% |
| 31 | 17 | 0.0120 | 8.5% |
| 43 | 14 | 0.0139 | 7.0% |
| 21 | 14 | 0.0130 | 7.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.759', '0.241']
- **Top Features:**
  - Feature 50: 0.0124
  - Feature 39: 0.0117
  - Feature 48: 0.0117

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.364', '0.636']
- **Top Features:**
  - Feature 80: 0.0117
  - Feature 32: 0.0114
  - Feature 42: 0.0114

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.377', '0.623']
- **Top Features:**
  - Feature 32: 0.0115
  - Feature 77: 0.0115
  - Feature 98: 0.0113

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.306', '0.694']
- **Top Features:**
  - Feature 7: 0.0270
  - Feature 0: 0.0264
  - Feature 43: 0.0260

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.329', '0.671']
- **Top Features:**
  - Feature 41: 0.0131
  - Feature 73: 0.0120
  - Feature 46: 0.0115

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.559', '0.441']
- **Top Features:**
  - Feature 1: 0.0120
  - Feature 12: 0.0112
  - Feature 69: 0.0112

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.478', '0.522']
- **Top Features:**
  - Feature 92: 0.0129
  - Feature 30: 0.0127
  - Feature 81: 0.0121

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.593', '0.407']
- **Top Features:**
  - Feature 21: 0.0122
  - Feature 71: 0.0112
  - Feature 16: 0.0110

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 50 | 0.012396919469078992 |
| 1 | 1.0 | 1.000 | YES | 80 | 0.011687641811649063 |
| 2 | 1.0 | 0.000 | NO | 1 | 0.01198712400322135 |
| 3 | 1.0 | 1.000 | YES | 32 | 0.011486551564742728 |
| 4 | 1.0 | 1.000 | YES | 7 | 0.02701568822561661 |
| 5 | 1.0 | 1.000 | YES | 41 | 0.013123898256514216 |
| 6 | 1.0 | 1.000 | YES | 39 | 0.018729204564783566 |
| 7 | 0.0 | 1.000 | NO | 92 | 0.012920651197724209 |
| 8 | 1.0 | 0.000 | NO | 21 | 0.01219256693878532 |
| 9 | 1.0 | 1.000 | YES | 38 | 0.012348333468604809 |
| 10 | 0.0 | 0.000 | YES | 60 | 0.01231156552455833 |
| 11 | 0.0 | 0.000 | YES | 6 | 0.012784072035477389 |
| 12 | 1.0 | 1.000 | YES | 44 | 0.01737729496533612 |
| 13 | 1.0 | 1.000 | YES | 3 | 0.01455370930669723 |
| 14 | 0.0 | 0.000 | YES | 1 | 0.011533867408574693 |
| 15 | 0.0 | 0.000 | YES | 45 | 0.014890878376971834 |
| 16 | 1.0 | 1.000 | YES | 7 | 0.011750561843652254 |
| 17 | 0.0 | 1.000 | NO | 57 | 0.012367420339445162 |
| 18 | 1.0 | 1.000 | YES | 7 | 0.012354521604261348 |
| 19 | 0.0 | 0.000 | YES | 21 | 0.012916290439064572 |
| 20 | 1.0 | 1.000 | YES | 58 | 0.012048633787858476 |
| 21 | 0.0 | 0.000 | YES | 34 | 0.012203941985407214 |
| 22 | 1.0 | 1.000 | YES | 80 | 0.0120368221530242 |
| 23 | 1.0 | 0.000 | NO | 55 | 0.011555499846587625 |
| 24 | 0.0 | 0.000 | YES | 79 | 0.012509462138353581 |
| 25 | 1.0 | 1.000 | YES | 2 | 0.012404494952374084 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.012790624134486376 |
| 27 | 0.0 | 0.000 | YES | 19 | 0.01202848662217748 |
| 28 | 0.0 | 0.000 | YES | 51 | 0.019789125934358567 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.012460860526167418 |
| 30 | 0.0 | 0.000 | YES | 10 | 0.02947481243301179 |
| 31 | 0.0 | 0.000 | YES | 33 | 0.012990997716682651 |
| 32 | 0.0 | 0.000 | YES | 17 | 0.012431399508344636 |
| 33 | 0.0 | 0.000 | YES | 0 | 0.0130870438336105 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.011284347273154771 |
| 35 | 0.0 | 0.000 | YES | 79 | 0.011786958420722934 |
| 36 | 1.0 | 0.000 | NO | 31 | 0.013035626939841383 |
| 37 | 1.0 | 1.000 | YES | 39 | 0.012907969460711271 |
| 38 | 1.0 | 1.000 | YES | 11 | 0.012035358165418916 |
| 39 | 0.0 | 0.000 | YES | 29 | 0.0160505332919126 |
| 40 | 0.0 | 0.000 | YES | 68 | 0.011662282819221674 |
| 41 | 0.0 | 1.000 | NO | 69 | 0.011222419841523288 |
| 42 | 1.0 | 0.000 | NO | 60 | 0.014220617454666809 |
| 43 | 1.0 | 1.000 | YES | 4 | 0.012493375935228701 |
| 44 | 0.0 | 0.000 | YES | 59 | 0.012794512416438489 |
| 45 | 0.0 | 0.000 | YES | 45 | 0.013113142284941046 |
| 46 | 1.0 | 1.000 | YES | 7 | 0.012343338361697593 |
| 47 | 1.0 | 0.000 | NO | 15 | 0.014187941466151155 |
| 48 | 1.0 | 1.000 | YES | 31 | 0.013015244252798732 |
| 49 | 0.0 | 0.000 | YES | 52 | 0.013060455243080821 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
