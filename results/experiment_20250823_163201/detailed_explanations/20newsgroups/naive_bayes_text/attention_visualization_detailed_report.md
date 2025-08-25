# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** naive_bayes_text  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 15:37:01  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7350
- **Average Feature Importance:** 0.0480
- **Feature Importance Std:** 0.0804
- **Max Feature Importance:** 3.0000

## Prediction Analysis

- **Correct Predictions:** 147 (73.5%)
- **Incorrect Predictions:** 53 (26.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 66 | 0.1828 | 33.0% |
| 2 | 53 | 0.1485 | 26.5% |
| 0 | 52 | 0.4799 | 26.0% |
| 9 | 22 | 0.1717 | 11.0% |
| 3 | 19 | 0.1744 | 9.5% |
| 15 | 19 | 0.1040 | 9.5% |
| 13 | 19 | 0.1193 | 9.5% |
| 21 | 18 | 0.0768 | 9.0% |
| 4 | 18 | 0.1719 | 9.0% |
| 25 | 18 | 0.0644 | 9.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.109', '0.118', '0.643', '0.130']
- **Top Features:**
  - Feature 61: 0.0565
  - Feature 41: 0.0547
  - Feature 2: 0.0535

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.079', '0.067', '0.770', '0.084']
- **Top Features:**
  - Feature 21: 0.0353
  - Feature 64: 0.0353
  - Feature 55: 0.0345

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.493', '0.140', '0.154', '0.213']
- **Top Features:**
  - Feature 41: 0.0220
  - Feature 33: 0.0210
  - Feature 44: 0.0210

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.090', '0.077', '0.097', '0.736']
- **Top Features:**
  - Feature 1: 0.0606
  - Feature 4: 0.0606
  - Feature 14: 0.0606

#### Instance 6

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.091', '0.498', '0.218', '0.193']
- **Top Features:**
  - Feature 38: 0.0200
  - Feature 64: 0.0189
  - Feature 26: 0.0183

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.161', '0.150', '0.314', '0.375']
- **Top Features:**
  - Feature 28: 0.1047
  - Feature 46: 0.1009
  - Feature 2: 0.0985

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.376', '0.085', '0.153', '0.386']
- **Top Features:**
  - Feature 68: 0.1440
  - Feature 7: 0.1401
  - Feature 63: 0.1401

#### Instance 12

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.213', '0.145', '0.217', '0.425']
- **Top Features:**
  - Feature 11: 0.1211
  - Feature 31: 0.1211
  - Feature 34: 0.1211

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 61 | 0.056517311608961306 |
| 1 | 2.0 | 2.000 | YES | 21 | 0.03529600513396438 |
| 2 | 2.0 | 3.000 | NO | 28 | 0.1047170717648189 |
| 3 | 0.0 | 0.000 | YES | 41 | 0.022013207924754852 |
| 4 | 3.0 | 3.000 | YES | 1 | 0.06058484571059292 |
| 5 | 0.0 | 3.000 | NO | 68 | 0.14397062612728678 |
| 6 | 1.0 | 1.000 | YES | 38 | 0.019976693857166637 |
| 7 | 3.0 | 3.000 | YES | 72 | 0.07410401509027217 |
| 8 | 2.0 | 2.000 | YES | 4 | 0.7311411992263055 |
| 9 | 2.0 | 2.000 | YES | 0 | 3.0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0.025985013294657962 |
| 11 | 3.0 | 3.000 | YES | 25 | 0.062418584455058615 |
| 12 | 2.0 | 3.000 | NO | 11 | 0.12105141803089692 |
| 13 | 3.0 | 3.000 | YES | 15 | 0.0782119021134594 |
| 14 | 1.0 | 3.000 | NO | 31 | 0.06101198546558924 |
| 15 | 0.0 | 2.000 | NO | 98 | 0.03714178985004536 |
| 16 | 1.0 | 1.000 | YES | 48 | 0.012970168612191958 |
| 17 | 3.0 | 3.000 | YES | 1 | 0.0986635572697103 |
| 18 | 0.0 | 2.000 | NO | 1 | 0.24106400665004157 |
| 19 | 0.0 | 3.000 | NO | 45 | 0.0622055164381386 |
| 20 | 2.0 | 2.000 | YES | 35 | 0.037901219945517 |
| 21 | 3.0 | 3.000 | YES | 35 | 0.0620381603617514 |
| 22 | 1.0 | 1.000 | YES | 92 | 0.014242115971515767 |
| 23 | 0.0 | 3.000 | NO | 1 | 0.17845003399048265 |
| 24 | 2.0 | 2.000 | YES | 48 | 0.07114889808703434 |
| 25 | 1.0 | 1.000 | YES | 64 | 0.011656907395358924 |
| 26 | 1.0 | 1.000 | YES | 5 | 0.01611354909489852 |
| 27 | 3.0 | 3.000 | YES | 30 | 0.1510574018126888 |
| 28 | 2.0 | 2.000 | YES | 33 | 0.037359900373599 |
| 29 | 0.0 | 3.000 | NO | 17 | 0.3343465045592705 |
| 30 | 1.0 | 1.000 | YES | 2 | 0.024854117138534686 |
| 31 | 3.0 | 3.000 | YES | 38 | 0.06326047162700549 |
| 32 | 0.0 | 3.000 | NO | 32 | 0.17090206568583738 |
| 33 | 2.0 | 2.000 | YES | 5 | 0.08639648130694312 |
| 34 | 2.0 | 2.000 | YES | 97 | 0.0361100800678721 |
| 35 | 0.0 | 3.000 | NO | 29 | 0.06297229219143577 |
| 36 | 2.0 | 2.000 | YES | 5 | 0.554140127388535 |
| 37 | 0.0 | 2.000 | NO | 99 | 0.03410838686329504 |
| 38 | 2.0 | 3.000 | NO | 8 | 0.649671052631579 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.12327981651376148 |
| 40 | 2.0 | 2.000 | YES | 1 | 0.035151779388522535 |
| 41 | 0.0 | 3.000 | NO | 16 | 0.11912497292614249 |
| 42 | 2.0 | 2.000 | YES | 37 | 0.03546285594199853 |
| 43 | 3.0 | 3.000 | YES | 97 | 0.05988189193664109 |
| 44 | 2.0 | 3.000 | NO | 1 | 0.05960767313319605 |
| 45 | 2.0 | 2.000 | YES | 96 | 0.03597877749530231 |
| 46 | 3.0 | 3.000 | YES | 58 | 0.061529205863049656 |
| 47 | 1.0 | 1.000 | YES | 20 | 0.054723799690242644 |
| 48 | 3.0 | 1.000 | NO | 36 | 0.033191987132621725 |
| 49 | 1.0 | 1.000 | YES | 76 | 0.015407037268373931 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
