# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** bert  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 05:20:48  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7150
- **Average Feature Importance:** 0.0411
- **Feature Importance Std:** 0.0484
- **Max Feature Importance:** 1.7629

## Prediction Analysis

- **Correct Predictions:** 143 (71.5%)
- **Incorrect Predictions:** 57 (28.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 70 | 0.1269 | 35.0% |
| 2 | 50 | 0.1013 | 25.0% |
| 0 | 50 | 0.2413 | 25.0% |
| 9 | 25 | 0.1339 | 12.5% |
| 4 | 20 | 0.1154 | 10.0% |
| 21 | 19 | 0.0703 | 9.5% |
| 3 | 19 | 0.1547 | 9.5% |
| 15 | 19 | 0.1036 | 9.5% |
| 25 | 18 | 0.0610 | 9.0% |
| 48 | 17 | 0.0507 | 8.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.193', '0.173', '0.460', '0.174']
- **Top Features:**
  - Feature 61: 0.0565
  - Feature 41: 0.0547
  - Feature 2: 0.0535

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.657', '0.120', '0.119', '0.104']
- **Top Features:**
  - Feature 41: 0.0220
  - Feature 33: 0.0210
  - Feature 44: 0.0210

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.076', '0.050', '0.073', '0.801']
- **Top Features:**
  - Feature 1: 0.0606
  - Feature 4: 0.0606
  - Feature 14: 0.0606

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.430', '0.106', '0.139', '0.325']
- **Top Features:**
  - Feature 9: 0.0339
  - Feature 11: 0.0164
  - Feature 2: 0.0160

#### Instance 7

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.131', '0.074', '0.104', '0.691']
- **Top Features:**
  - Feature 72: 0.0741
  - Feature 70: 0.0724
  - Feature 44: 0.0707

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.412', '0.170', '0.355', '0.063']
- **Top Features:**
  - Feature 21: 0.0110
  - Feature 64: 0.0110
  - Feature 55: 0.0108

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.108', '0.152', '0.348', '0.391']
- **Top Features:**
  - Feature 46: 0.1362
  - Feature 2: 0.1338
  - Feature 48: 0.1197

#### Instance 6

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.149', '0.311', '0.314', '0.226']
- **Top Features:**
  - Feature 64: 0.0719
  - Feature 11: 0.0679
  - Feature 65: 0.0660

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 61 | 0.056517311608961306 |
| 1 | 2.0 | 0.000 | NO | 21 | 0.010951324245655496 |
| 2 | 2.0 | 3.000 | NO | 46 | 0.1361630200018781 |
| 3 | 0.0 | 0.000 | YES | 41 | 0.022013207924754852 |
| 4 | 3.0 | 3.000 | YES | 1 | 0.06058484571059292 |
| 5 | 0.0 | 0.000 | YES | 9 | 0.03390734532154831 |
| 6 | 1.0 | 2.000 | NO | 64 | 0.07187451225222412 |
| 7 | 3.0 | 3.000 | YES | 72 | 0.07410401509027217 |
| 8 | 2.0 | 1.000 | NO | 4 | 0.24371373307543517 |
| 9 | 2.0 | 1.000 | NO | 0 | 1.0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0.025985013294657962 |
| 11 | 3.0 | 3.000 | YES | 25 | 0.05992885864522116 |
| 12 | 2.0 | 3.000 | NO | 11 | 0.12105141803089692 |
| 13 | 3.0 | 3.000 | YES | 15 | 0.0782119021134594 |
| 14 | 1.0 | 2.000 | NO | 31 | 0.03441699693077863 |
| 15 | 0.0 | 2.000 | NO | 98 | 0.03714178985004536 |
| 16 | 1.0 | 1.000 | YES | 48 | 0.012970168612191958 |
| 17 | 3.0 | 3.000 | YES | 1 | 0.0986635572697103 |
| 18 | 0.0 | 1.000 | NO | 4 | 0.07509209407764239 |
| 19 | 0.0 | 3.000 | NO | 45 | 0.0622055164381386 |
| 20 | 2.0 | 2.000 | YES | 35 | 0.03532632694515588 |
| 21 | 3.0 | 3.000 | YES | 35 | 0.0620381603617514 |
| 22 | 1.0 | 1.000 | YES | 92 | 0.014242115971515767 |
| 23 | 0.0 | 3.000 | NO | 31 | 0.3394091766184789 |
| 24 | 2.0 | 2.000 | YES | 6 | 0.11016308456636786 |
| 25 | 1.0 | 1.000 | YES | 68 | 0.015115525804361908 |
| 26 | 1.0 | 1.000 | YES | 5 | 0.01611354909489852 |
| 27 | 3.0 | 3.000 | YES | 17 | 0.2700617283950617 |
| 28 | 2.0 | 2.000 | YES | 33 | 0.037359900373599 |
| 29 | 0.0 | 0.000 | YES | 2 | 0.08110300081103002 |
| 30 | 1.0 | 1.000 | YES | 2 | 0.024854117138534686 |
| 31 | 3.0 | 3.000 | YES | 38 | 0.06326047162700549 |
| 32 | 0.0 | 3.000 | NO | 32 | 0.17090206568583738 |
| 33 | 2.0 | 2.000 | YES | 40 | 0.07668548301203536 |
| 34 | 2.0 | 2.000 | YES | 97 | 0.0361100800678721 |
| 35 | 0.0 | 3.000 | NO | 29 | 0.055674066433812334 |
| 36 | 2.0 | 1.000 | NO | 5 | 0.18471337579617833 |
| 37 | 0.0 | 3.000 | NO | 99 | 0.059099079470559396 |
| 38 | 2.0 | 0.000 | NO | 1 | 0.200089928057554 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.12327981651376148 |
| 40 | 2.0 | 2.000 | YES | 1 | 0.035151779388522535 |
| 41 | 0.0 | 0.000 | YES | 16 | 0.0238249945852285 |
| 42 | 2.0 | 2.000 | YES | 37 | 0.03546285594199853 |
| 43 | 3.0 | 3.000 | YES | 97 | 0.05988189193664109 |
| 44 | 2.0 | 3.000 | NO | 48 | 0.0701413618215172 |
| 45 | 2.0 | 2.000 | YES | 96 | 0.03597877749530231 |
| 46 | 3.0 | 3.000 | YES | 58 | 0.061529205863049656 |
| 47 | 1.0 | 1.000 | YES | 20 | 0.054723799690242644 |
| 48 | 3.0 | 1.000 | NO | 36 | 0.033191987132621725 |
| 49 | 1.0 | 1.000 | YES | 76 | 0.015407037268373931 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
