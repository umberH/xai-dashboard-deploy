# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** lstm  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 05:22:09  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7100
- **Average Feature Importance:** 0.0445
- **Feature Importance Std:** 0.0807
- **Max Feature Importance:** 3.0000

## Prediction Analysis

- **Correct Predictions:** 142 (71.0%)
- **Incorrect Predictions:** 58 (29.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 67 | 0.1786 | 33.5% |
| 2 | 52 | 0.1421 | 26.0% |
| 0 | 50 | 0.5024 | 25.0% |
| 3 | 23 | 0.1906 | 11.5% |
| 15 | 22 | 0.0792 | 11.0% |
| 9 | 21 | 0.1442 | 10.5% |
| 99 | 20 | 0.0397 | 10.0% |
| 25 | 19 | 0.0636 | 9.5% |
| 12 | 18 | 0.0942 | 9.0% |
| 21 | 17 | 0.0664 | 8.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.156', '0.104', '0.562', '0.178']
- **Top Features:**
  - Feature 61: 0.0565
  - Feature 41: 0.0547
  - Feature 2: 0.0535

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.599', '0.110', '0.108', '0.182']
- **Top Features:**
  - Feature 41: 0.0220
  - Feature 33: 0.0210
  - Feature 44: 0.0210

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.051', '0.016', '0.020', '0.913']
- **Top Features:**
  - Feature 1: 0.0606
  - Feature 4: 0.0606
  - Feature 14: 0.0606

#### Instance 6

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.151', '0.359', '0.241', '0.249']
- **Top Features:**
  - Feature 25: 0.0279
  - Feature 38: 0.0197
  - Feature 64: 0.0186

#### Instance 7

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.115', '0.031', '0.057', '0.797']
- **Top Features:**
  - Feature 72: 0.0741
  - Feature 70: 0.0724
  - Feature 44: 0.0707

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.417', '0.118', '0.345', '0.120']
- **Top Features:**
  - Feature 21: 0.0110
  - Feature 64: 0.0110
  - Feature 55: 0.0108

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.117', '0.114', '0.305', '0.464']
- **Top Features:**
  - Feature 28: 0.1047
  - Feature 46: 0.1009
  - Feature 2: 0.0985

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.389', '0.038', '0.082', '0.491']
- **Top Features:**
  - Feature 11: 0.0834
  - Feature 2: 0.0815
  - Feature 50: 0.0815

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 61 | 0.056517311608961306 |
| 1 | 2.0 | 0.000 | NO | 21 | 0.010951324245655496 |
| 2 | 2.0 | 3.000 | NO | 28 | 0.1047170717648189 |
| 3 | 0.0 | 0.000 | YES | 41 | 0.022013207924754852 |
| 4 | 3.0 | 3.000 | YES | 1 | 0.06058484571059292 |
| 5 | 0.0 | 3.000 | NO | 11 | 0.08343682086308599 |
| 6 | 1.0 | 1.000 | YES | 25 | 0.027928371940200425 |
| 7 | 3.0 | 3.000 | YES | 72 | 0.07410401509027217 |
| 8 | 2.0 | 2.000 | YES | 4 | 0.7311411992263055 |
| 9 | 2.0 | 2.000 | YES | 0 | 3.0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0.025985013294657962 |
| 11 | 3.0 | 3.000 | YES | 25 | 0.062418584455058615 |
| 12 | 2.0 | 3.000 | NO | 11 | 0.12105141803089692 |
| 13 | 3.0 | 3.000 | YES | 15 | 0.0782119021134594 |
| 14 | 1.0 | 1.000 | YES | 63 | 0.014474446023474918 |
| 15 | 0.0 | 2.000 | NO | 98 | 0.03714178985004536 |
| 16 | 1.0 | 1.000 | YES | 48 | 0.012970168612191958 |
| 17 | 3.0 | 3.000 | YES | 1 | 0.0986635572697103 |
| 18 | 0.0 | 3.000 | NO | 0 | 0.5082678232583356 |
| 19 | 0.0 | 3.000 | NO | 45 | 0.0622055164381386 |
| 20 | 2.0 | 2.000 | YES | 2 | 0.041044912255098695 |
| 21 | 3.0 | 3.000 | YES | 35 | 0.0620381603617514 |
| 22 | 1.0 | 1.000 | YES | 92 | 0.014242115971515767 |
| 23 | 0.0 | 3.000 | NO | 31 | 0.3394091766184789 |
| 24 | 2.0 | 3.000 | NO | 12 | 0.14691207450936908 |
| 25 | 1.0 | 1.000 | YES | 64 | 0.011656907395358924 |
| 26 | 1.0 | 1.000 | YES | 18 | 0.022425897035881437 |
| 27 | 3.0 | 3.000 | YES | 30 | 0.1510574018126888 |
| 28 | 2.0 | 2.000 | YES | 33 | 0.037359900373599 |
| 29 | 0.0 | 0.000 | YES | 2 | 0.1122224932910466 |
| 30 | 1.0 | 1.000 | YES | 2 | 0.024854117138534686 |
| 31 | 3.0 | 3.000 | YES | 38 | 0.06326047162700549 |
| 32 | 0.0 | 3.000 | NO | 32 | 0.17090206568583738 |
| 33 | 2.0 | 2.000 | YES | 17 | 0.08427827152926753 |
| 34 | 2.0 | 2.000 | YES | 97 | 0.0361100800678721 |
| 35 | 0.0 | 3.000 | NO | 29 | 0.055674066433812334 |
| 36 | 2.0 | 2.000 | YES | 5 | 0.554140127388535 |
| 37 | 0.0 | 3.000 | NO | 99 | 0.059099079470559396 |
| 38 | 2.0 | 3.000 | NO | 8 | 0.649671052631579 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.12327981651376148 |
| 40 | 2.0 | 1.000 | NO | 1 | 0.011195870811036474 |
| 41 | 0.0 | 0.000 | YES | 16 | 0.0238249945852285 |
| 42 | 2.0 | 2.000 | YES | 37 | 0.03546285594199853 |
| 43 | 3.0 | 3.000 | YES | 97 | 0.05988189193664109 |
| 44 | 2.0 | 3.000 | NO | 1 | 0.05960767313319605 |
| 45 | 2.0 | 2.000 | YES | 96 | 0.03597877749530231 |
| 46 | 3.0 | 3.000 | YES | 58 | 0.061529205863049656 |
| 47 | 1.0 | 1.000 | YES | 20 | 0.054723799690242644 |
| 48 | 3.0 | 1.000 | NO | 36 | 0.033191987132621725 |
| 49 | 1.0 | 1.000 | YES | 76 | 0.015407037268373931 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
