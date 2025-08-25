# Detailed Explanation Report

**Dataset:** wine_classification  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:37:53  

## Summary Statistics

- **Total Instances:** 36
- **Valid Explanations:** 36
- **Errors:** 0
- **Model Accuracy:** 0.8611
- **Average Feature Importance:** 0.0769
- **Feature Importance Std:** 0.1916
- **Max Feature Importance:** 0.9310

## Prediction Analysis

- **Correct Predictions:** 31 (86.1%)
- **Incorrect Predictions:** 5 (13.9%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 6 | 24 | 0.6680 | 66.7% |
| 11 | 21 | 0.0850 | 58.3% |
| 12 | 18 | 0.1302 | 50.0% |
| 5 | 18 | 0.0381 | 50.0% |
| 9 | 18 | 0.2184 | 50.0% |
| 7 | 14 | 0.1379 | 38.9% |
| 3 | 13 | 0.3246 | 36.1% |
| 1 | 12 | 0.0257 | 33.3% |
| 0 | 10 | 0.1500 | 27.8% |
| 10 | 10 | 0.0563 | 27.8% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** -0.28420640024809407
- **Prediction Probabilities:** ['-0.284']
- **Top Features:**
  - Feature 6: 0.7675
  - Feature 12: 0.0624
  - Feature 5: 0.0576

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 1.788989754333345
- **Prediction Probabilities:** ['1.789']
- **Top Features:**
  - Feature 9: 0.9258
  - Feature 7: 0.0742
  - Feature 0: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.05887020624168804
- **Prediction Probabilities:** ['0.059']
- **Top Features:**
  - Feature 6: 0.8051
  - Feature 12: 0.0625
  - Feature 8: 0.0240

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.8408169627178115
- **Prediction Probabilities:** ['0.841']
- **Top Features:**
  - Feature 0: 0.8862
  - Feature 10: 0.0906
  - Feature 6: 0.0232

#### Instance 5

- **True Label:** 0.0
- **Prediction:** -0.14959092579272137
- **Prediction Probabilities:** ['-0.150']
- **Top Features:**
  - Feature 6: 0.7483
  - Feature 12: 0.0665
  - Feature 11: 0.0467

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 1.0
- **Prediction:** -0.1582246007544169
- **Prediction Probabilities:** ['-0.158']
- **Top Features:**
  - Feature 6: 0.6758
  - Feature 9: 0.0856
  - Feature 11: 0.0834

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.4844156137852371
- **Prediction Probabilities:** ['0.484']
- **Top Features:**
  - Feature 6: 0.8713
  - Feature 11: 0.0365
  - Feature 5: 0.0335

#### Instance 13

- **True Label:** 2.0
- **Prediction:** 1.401781527466775
- **Prediction Probabilities:** ['1.402']
- **Top Features:**
  - Feature 4: 0.9202
  - Feature 0: 0.0755
  - Feature 2: 0.0043

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | -0.284 | YES | 6 | 0.76751254043729 |
| 1 | 2.0 | 1.789 | YES | 9 | 0.9257919199573096 |
| 2 | 0.0 | 0.059 | YES | 6 | 0.8051164937112776 |
| 3 | 1.0 | -0.158 | NO | 6 | 0.6757529163008394 |
| 4 | 1.0 | 0.841 | YES | 0 | 0.8861763593794558 |
| 5 | 0.0 | -0.150 | YES | 6 | 0.7483091388452116 |
| 6 | 0.0 | -0.131 | YES | 6 | 0.6276937368095225 |
| 7 | 1.0 | 0.484 | NO | 6 | 0.8712807554738937 |
| 8 | 1.0 | 1.202 | YES | 3 | 0.7329270434607811 |
| 9 | 2.0 | 2.068 | YES | 9 | 0.5023838802226022 |
| 10 | 1.0 | 0.907 | YES | 6 | 0.8624503605237088 |
| 11 | 2.0 | 1.668 | YES | 3 | 0.6238624975884713 |
| 12 | 0.0 | -0.308 | YES | 6 | 0.6217999166948905 |
| 13 | 2.0 | 1.402 | NO | 4 | 0.9201605518912038 |
| 14 | 0.0 | -0.475 | YES | 6 | 0.6556146715515814 |
| 15 | 1.0 | 1.083 | YES | 6 | 0.823613943472621 |
| 16 | 1.0 | 0.905 | YES | 11 | 0.45732902278203424 |
| 17 | 0.0 | 0.047 | YES | 6 | 0.6267957416326309 |
| 18 | 1.0 | 0.710 | YES | 6 | 0.9309571863169431 |
| 19 | 0.0 | 0.159 | YES | 6 | 0.7714481783567394 |
| 20 | 1.0 | 0.911 | YES | 6 | 0.8897762034753237 |
| 21 | 1.0 | 1.126 | YES | 7 | 0.7720497362198083 |
| 22 | 0.0 | -0.225 | YES | 6 | 0.699418522035146 |
| 23 | 0.0 | -0.568 | NO | 6 | 0.6162792851760345 |
| 24 | 1.0 | 0.356 | NO | 6 | 0.8451627088815844 |
| 25 | 1.0 | 1.057 | YES | 7 | 0.5635752072965735 |
| 26 | 0.0 | -0.129 | YES | 6 | 0.5985972315020602 |
| 27 | 2.0 | 1.799 | YES | 3 | 0.4993865588615928 |
| 28 | 1.0 | 0.730 | YES | 6 | 0.8762374970598511 |
| 29 | 2.0 | 2.085 | YES | 9 | 0.41391224971850804 |
| 30 | 0.0 | 0.318 | YES | 6 | 0.7003530503803574 |
| 31 | 2.0 | 1.847 | YES | 12 | 0.5465198604686244 |
| 32 | 1.0 | 1.109 | YES | 6 | 0.8707166810156114 |
| 33 | 2.0 | 2.184 | YES | 3 | 0.5808171982980759 |
| 34 | 2.0 | 2.021 | YES | 3 | 0.4026792279850747 |
| 35 | 2.0 | 1.882 | YES | 12 | 0.40124987387405475 |
