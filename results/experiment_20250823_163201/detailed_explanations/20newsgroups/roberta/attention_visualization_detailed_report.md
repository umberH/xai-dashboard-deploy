# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** roberta  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 15:35:28  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8400
- **Average Feature Importance:** 0.0379
- **Feature Importance Std:** 0.0402
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 168 (84.0%)
- **Incorrect Predictions:** 32 (16.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 69 | 0.0976 | 34.5% |
| 2 | 51 | 0.0902 | 25.5% |
| 0 | 50 | 0.1938 | 25.0% |
| 9 | 21 | 0.1119 | 10.5% |
| 15 | 19 | 0.0758 | 9.5% |
| 8 | 19 | 0.1457 | 9.5% |
| 4 | 18 | 0.1244 | 9.0% |
| 50 | 18 | 0.0455 | 9.0% |
| 3 | 18 | 0.1061 | 9.0% |
| 25 | 18 | 0.0632 | 9.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.002', '0.001', '0.995', '0.002']
- **Top Features:**
  - Feature 61: 0.0565
  - Feature 41: 0.0547
  - Feature 2: 0.0535

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.001', '0.001', '0.996', '0.002']
- **Top Features:**
  - Feature 21: 0.0353
  - Feature 64: 0.0353
  - Feature 55: 0.0345

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.003', '0.004', '0.990', '0.003']
- **Top Features:**
  - Feature 28: 0.0628
  - Feature 46: 0.0605
  - Feature 2: 0.0591

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.984', '0.004', '0.007', '0.005']
- **Top Features:**
  - Feature 41: 0.0220
  - Feature 33: 0.0210
  - Feature 44: 0.0210

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.017', '0.001', '0.003', '0.979']
- **Top Features:**
  - Feature 1: 0.0606
  - Feature 4: 0.0606
  - Feature 14: 0.0606

### Incorrect Predictions (Sample)

#### Instance 8

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.106', '0.820', '0.037', '0.037']
- **Top Features:**
  - Feature 4: 0.2980
  - Feature 3: 0.1813
  - Feature 0: 0.1795

#### Instance 9

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.196', '0.355', '0.242', '0.207']
- **Top Features:**
  - Feature 0: 1.0000

#### Instance 12

- **True Label:** 2.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.599', '0.015', '0.257', '0.129']
- **Top Features:**
  - Feature 4: 0.0384
  - Feature 5: 0.0372
  - Feature 11: 0.0233

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 61 | 0.056517311608961306 |
| 1 | 2.0 | 2.000 | YES | 21 | 0.03529600513396438 |
| 2 | 2.0 | 2.000 | YES | 28 | 0.06283024305889134 |
| 3 | 0.0 | 0.000 | YES | 41 | 0.022013207924754852 |
| 4 | 3.0 | 3.000 | YES | 1 | 0.06058484571059292 |
| 5 | 0.0 | 0.000 | YES | 11 | 0.016687364172617198 |
| 6 | 1.0 | 1.000 | YES | 38 | 0.019976693857166637 |
| 7 | 3.0 | 3.000 | YES | 72 | 0.07410401509027217 |
| 8 | 2.0 | 1.000 | NO | 4 | 0.29802513464991026 |
| 9 | 2.0 | 1.000 | NO | 0 | 1.0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0.025985013294657962 |
| 11 | 3.0 | 3.000 | YES | 25 | 0.062418584455058615 |
| 12 | 2.0 | 0.000 | NO | 4 | 0.03835890593729152 |
| 13 | 3.0 | 3.000 | YES | 15 | 0.0782119021134594 |
| 14 | 1.0 | 0.000 | NO | 31 | 0.012202397093117847 |
| 15 | 0.0 | 2.000 | NO | 98 | 0.03714178985004536 |
| 16 | 1.0 | 1.000 | YES | 48 | 0.012970168612191958 |
| 17 | 3.0 | 3.000 | YES | 1 | 0.0986635572697103 |
| 18 | 0.0 | 2.000 | NO | 8 | 0.19135981443896782 |
| 19 | 0.0 | 3.000 | NO | 63 | 0.11762245804798996 |
| 20 | 2.0 | 2.000 | YES | 35 | 0.03869095598903756 |
| 21 | 3.0 | 3.000 | YES | 35 | 0.0620381603617514 |
| 22 | 1.0 | 1.000 | YES | 92 | 0.014242115971515767 |
| 23 | 0.0 | 3.000 | NO | 31 | 0.3049124788255223 |
| 24 | 2.0 | 2.000 | YES | 48 | 0.07114889808703434 |
| 25 | 1.0 | 1.000 | YES | 64 | 0.011656907395358924 |
| 26 | 1.0 | 1.000 | YES | 5 | 0.01611354909489852 |
| 27 | 3.0 | 3.000 | YES | 30 | 0.1510574018126888 |
| 28 | 2.0 | 2.000 | YES | 33 | 0.037359900373599 |
| 29 | 0.0 | 0.000 | YES | 17 | 0.0668693009118541 |
| 30 | 1.0 | 1.000 | YES | 2 | 0.024854117138534686 |
| 31 | 3.0 | 3.000 | YES | 38 | 0.06326047162700549 |
| 32 | 0.0 | 3.000 | NO | 21 | 0.2015236070511117 |
| 33 | 2.0 | 2.000 | YES | 40 | 0.07668548301203536 |
| 34 | 2.0 | 2.000 | YES | 97 | 0.0361100800678721 |
| 35 | 0.0 | 0.000 | YES | 29 | 0.012594458438287152 |
| 36 | 2.0 | 2.000 | YES | 5 | 0.554140127388535 |
| 37 | 0.0 | 0.000 | YES | 99 | 0.01181981589411188 |
| 38 | 2.0 | 2.000 | YES | 8 | 0.38980263157894735 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.12327981651376148 |
| 40 | 2.0 | 2.000 | YES | 1 | 0.035151779388522535 |
| 41 | 0.0 | 3.000 | NO | 31 | 0.21618282890673252 |
| 42 | 2.0 | 2.000 | YES | 37 | 0.03546285594199853 |
| 43 | 3.0 | 3.000 | YES | 97 | 0.05988189193664109 |
| 44 | 2.0 | 2.000 | YES | 1 | 0.03576460387991763 |
| 45 | 2.0 | 2.000 | YES | 96 | 0.03597877749530231 |
| 46 | 3.0 | 3.000 | YES | 58 | 0.061529205863049656 |
| 47 | 1.0 | 1.000 | YES | 20 | 0.054723799690242644 |
| 48 | 3.0 | 1.000 | NO | 36 | 0.033191987132621725 |
| 49 | 1.0 | 1.000 | YES | 76 | 0.015407037268373931 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
