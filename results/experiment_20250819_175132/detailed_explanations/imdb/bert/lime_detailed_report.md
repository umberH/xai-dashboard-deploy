# Detailed Explanation Report

**Dataset:** imdb  
**Model:** bert  
**Explanation Method:** lime  
**Generated:** 2025-08-19 18:34:26  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8100
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0211
- **Max Feature Importance:** 0.3130

## Prediction Analysis

- **Correct Predictions:** 162 (81.0%)
- **Incorrect Predictions:** 38 (19.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 47 | 0.0528 | 23.5% |
| 3 | 45 | 0.0592 | 22.5% |
| 2 | 44 | 0.0533 | 22.0% |
| 4 | 43 | 0.0635 | 21.5% |
| 0 | 36 | 0.0475 | 18.0% |
| 15 | 30 | 0.0697 | 15.0% |
| 43 | 29 | 0.0669 | 14.5% |
| 13 | 27 | 0.0794 | 13.5% |
| 8 | 24 | 0.0684 | 12.0% |
| 20 | 24 | 0.0627 | 12.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.753', '0.247']
- **Top Features:**
  - Feature 4: 0.1015
  - Feature 39: 0.0804
  - Feature 13: 0.0785

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.320', '0.680']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.350', '0.650']
- **Top Features:**
  - Feature 4: 0.0772
  - Feature 30: 0.0719
  - Feature 0: 0.0548

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.259', '0.741']
- **Top Features:**
  - Feature 12: 0.0424
  - Feature 30: 0.0410
  - Feature 9: 0.0401

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.371', '0.629']
- **Top Features:**
  - Feature 48: 0.0629
  - Feature 22: 0.0560
  - Feature 44: 0.0515

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.510', '0.490']
- **Top Features:**
  - Feature 4: 0.1139
  - Feature 23: 0.0690
  - Feature 1: 0.0546

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.405', '0.595']
- **Top Features:**
  - Feature 18: 0.0516
  - Feature 24: 0.0503
  - Feature 46: 0.0492

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.656', '0.344']
- **Top Features:**
  - Feature 49: 0.1690
  - Feature 7: 0.1609
  - Feature 22: 0.0424

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 4 | 0.10153612260425886 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 2 | 1.0 | 0.000 | NO | 4 | 0.11387387173194048 |
| 3 | 1.0 | 1.000 | YES | 4 | 0.07716745136621209 |
| 4 | 1.0 | 1.000 | YES | 12 | 0.04236981234227909 |
| 5 | 1.0 | 1.000 | YES | 48 | 0.06287178912812436 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 7 | 0.0 | 1.000 | NO | 18 | 0.05157279802617171 |
| 8 | 1.0 | 0.000 | NO | 49 | 0.16897242629477985 |
| 9 | 1.0 | 1.000 | YES | 47 | 0.067373452309047 |
| 10 | 0.0 | 0.000 | YES | 30 | 0.09145903646850312 |
| 11 | 0.0 | 0.000 | YES | 46 | 0.14210313125651983 |
| 12 | 1.0 | 1.000 | YES | 20 | 0.07455659795251873 |
| 13 | 1.0 | 1.000 | YES | 3 | 0.10729266418776315 |
| 14 | 0.0 | 0.000 | YES | 17 | 0.06893942982585345 |
| 15 | 0.0 | 0.000 | YES | 23 | 0.11015938024040386 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.1490779348610734 |
| 17 | 0.0 | 1.000 | NO | 7 | 0.0487015638822328 |
| 18 | 1.0 | 1.000 | YES | 26 | 0.1330394890195744 |
| 19 | 0.0 | 1.000 | NO | 16 | 0.07701680529360964 |
| 20 | 1.0 | 1.000 | YES | 3 | 0.20647466092038408 |
| 21 | 0.0 | 0.000 | YES | 29 | 0.048768065298841756 |
| 22 | 1.0 | 1.000 | YES | 25 | 0.07979126235252462 |
| 23 | 1.0 | 1.000 | YES | 15 | 0.06801467466156856 |
| 24 | 0.0 | 0.000 | YES | 42 | 0.05986979734303476 |
| 25 | 1.0 | 1.000 | YES | 22 | 0.09865446104652353 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 27 | 0.0 | 0.000 | YES | 8 | 0.10789713960570271 |
| 28 | 0.0 | 1.000 | NO | 21 | 0.05287764327685022 |
| 29 | 1.0 | 1.000 | YES | 14 | 0.10041671306495153 |
| 30 | 0.0 | 0.000 | YES | 26 | 0.0843716347225745 |
| 31 | 0.0 | 0.000 | YES | 17 | 0.313015338397424 |
| 32 | 0.0 | 0.000 | YES | 11 | 0.054502545233701835 |
| 33 | 0.0 | 1.000 | NO | 16 | 0.10706854448564378 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 35 | 0.0 | 0.000 | YES | 23 | 0.21147816121325916 |
| 36 | 1.0 | 1.000 | YES | 17 | 0.14463291609440765 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 38 | 1.0 | 1.000 | YES | 38 | 0.06488862372301485 |
| 39 | 0.0 | 0.000 | YES | 12 | 0.07603152963847377 |
| 40 | 0.0 | 0.000 | YES | 43 | 0.1374029967042339 |
| 41 | 0.0 | 1.000 | NO | 48 | 0.17268080909122918 |
| 42 | 1.0 | 1.000 | YES | 45 | 0.08448041646818047 |
| 43 | 1.0 | 1.000 | YES | 22 | 0.08486701872647942 |
| 44 | 0.0 | 0.000 | YES | 39 | 0.09502206905479937 |
| 45 | 0.0 | 0.000 | YES | 34 | 0.13605121766771802 |
| 46 | 1.0 | 1.000 | YES | 6 | 0.06838707934730816 |
| 47 | 1.0 | 1.000 | YES | 33 | 0.07910247436484232 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 49 | 0.0 | 0.000 | YES | 23 | 0.08052212337343143 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
