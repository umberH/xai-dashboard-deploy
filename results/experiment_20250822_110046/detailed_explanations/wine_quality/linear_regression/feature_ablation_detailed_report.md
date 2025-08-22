# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** linear_regression  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-22 14:19:04  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.6375
- **Average Feature Importance:** 0.0705
- **Feature Importance Std:** 0.0894
- **Max Feature Importance:** 1.1417

## Prediction Analysis

- **Correct Predictions:** 204 (63.7%)
- **Incorrect Predictions:** 116 (36.2%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 10 | 288 | 0.2358 | 90.0% |
| 6 | 260 | 0.1286 | 81.2% |
| 1 | 245 | 0.1308 | 76.6% |
| 9 | 239 | 0.1239 | 74.7% |
| 0 | 171 | 0.0794 | 53.4% |
| 7 | 152 | 0.0858 | 47.5% |
| 5 | 101 | 0.0634 | 31.6% |
| 8 | 64 | 0.0516 | 20.0% |
| 3 | 42 | 0.0989 | 13.1% |
| 4 | 37 | 0.1139 | 11.6% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.2454908014455746
- **Prediction Probabilities:** ['1.245']
- **Top Features:**
  - Feature 10: 0.4715
  - Feature 1: 0.1209
  - Feature 0: 0.0721

#### Instance 2

- **True Label:** 0.0
- **Prediction:** -0.074243013988612
- **Prediction Probabilities:** ['-0.074']
- **Top Features:**
  - Feature 10: 0.3036
  - Feature 9: 0.2802
  - Feature 1: 0.2567

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.34263686960739365
- **Prediction Probabilities:** ['0.343']
- **Top Features:**
  - Feature 10: 0.2580
  - Feature 6: 0.1145
  - Feature 1: 0.0625

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.118043609529831
- **Prediction Probabilities:** ['1.118']
- **Top Features:**
  - Feature 10: 0.1979
  - Feature 1: 0.1856
  - Feature 9: 0.0843

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.04649308636080407
- **Prediction Probabilities:** ['0.046']
- **Top Features:**
  - Feature 10: 0.2124
  - Feature 6: 0.1625
  - Feature 9: 0.1014

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.64681275757956
- **Prediction Probabilities:** ['0.647']
- **Top Features:**
  - Feature 10: 0.1295
  - Feature 1: 0.0805
  - Feature 9: 0.0673

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.49436565303495084
- **Prediction Probabilities:** ['0.494']
- **Top Features:**
  - Feature 10: 0.1896
  - Feature 6: 0.0641
  - Feature 9: 0.0519

#### Instance 9

- **True Label:** 2.0
- **Prediction:** 0.8197238398038897
- **Prediction Probabilities:** ['0.820']
- **Top Features:**
  - Feature 10: 0.2435
  - Feature 1: 0.0949
  - Feature 7: 0.0763

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.245 | YES | 10 | 0.4714519324338362 |
| 1 | 0.0 | 0.647 | NO | 10 | 0.12953856279491704 |
| 2 | 0.0 | -0.074 | YES | 10 | 0.3035517054143805 |
| 3 | 0.0 | 0.343 | YES | 10 | 0.2579632561291911 |
| 4 | 1.0 | 0.494 | NO | 10 | 0.1895805822014075 |
| 5 | 1.0 | 1.118 | YES | 10 | 0.197921236722701 |
| 6 | 0.0 | 0.046 | YES | 10 | 0.21237480684400195 |
| 7 | 0.0 | 0.056 | YES | 1 | 0.2171287541297583 |
| 8 | 1.0 | 1.201 | YES | 10 | 0.5398346063616201 |
| 9 | 2.0 | 0.820 | NO | 10 | 0.24350968600789014 |
| 10 | 0.0 | 0.264 | YES | 10 | 0.280757480771786 |
| 11 | 1.0 | 1.062 | YES | 10 | 0.53983460636162 |
| 12 | 0.0 | 0.154 | YES | 10 | 0.21237480684400195 |
| 13 | 0.0 | -0.199 | YES | 6 | 0.34719847261651415 |
| 14 | 0.0 | 0.166 | YES | 10 | 0.2807574807717859 |
| 15 | 1.0 | 1.335 | YES | 10 | 0.3346865845782685 |
| 16 | 1.0 | 0.373 | NO | 10 | 0.12119790827362348 |
| 17 | 0.0 | 0.346 | YES | 10 | 0.23516903148659657 |
| 18 | 2.0 | 1.343 | NO | 1 | 0.20717083452224294 |
| 19 | 0.0 | -0.497 | YES | 1 | 0.5119810106506407 |
| 20 | 1.0 | 1.038 | YES | 10 | 0.4714519324338361 |
| 21 | 1.0 | 0.762 | YES | 6 | 0.06180172518463711 |
| 22 | 0.0 | 0.403 | YES | 1 | 0.11644749580555458 |
| 23 | 1.0 | 0.503 | YES | 10 | 0.12119790827362342 |
| 24 | 0.0 | 0.186 | YES | 10 | 0.2807574807717859 |
| 25 | 1.0 | 0.498 | NO | 10 | 0.12119790827362342 |
| 26 | 1.0 | 0.649 | YES | 6 | 0.1312607804310445 |
| 27 | 0.0 | -0.091 | YES | 6 | 0.3975626045162571 |
| 28 | 2.0 | 1.210 | NO | 10 | 0.15233278743751155 |
| 29 | 0.0 | 0.059 | YES | 10 | 0.2579632561291911 |
| 30 | 0.0 | 0.193 | YES | 10 | 0.257963256129191 |
| 31 | 0.0 | 0.358 | YES | 10 | 0.18958058220140744 |
| 32 | 1.0 | 0.279 | NO | 10 | 0.32634593005697493 |
| 33 | 1.0 | 1.024 | YES | 0 | 0.142402648056843 |
| 34 | 2.0 | 1.463 | NO | 10 | 0.28909813529307926 |
| 35 | 0.0 | 0.393 | YES | 9 | 0.36691841884500775 |
| 36 | 0.0 | 0.204 | YES | 10 | 0.2351690314865965 |
| 37 | 1.0 | 0.932 | YES | 10 | 0.15233278743751155 |
| 38 | 0.0 | 0.077 | YES | 10 | 0.166786357558813 |
| 39 | 0.0 | -0.179 | YES | 1 | 0.2926396978729112 |
| 40 | 0.0 | 0.316 | YES | 10 | 0.280757480771786 |
| 41 | 0.0 | 0.520 | NO | 1 | 0.15959660651592755 |
| 42 | 1.0 | 0.330 | NO | 10 | 0.280757480771786 |
| 43 | 1.0 | 0.745 | YES | 7 | 0.0701971782823233 |
| 44 | 2.0 | 1.532 | YES | 10 | 0.5626288310042146 |
| 45 | 2.0 | 1.108 | NO | 1 | 0.1927877976187854 |
| 46 | 1.0 | 0.055 | NO | 10 | 0.2579632561291911 |
| 47 | 1.0 | 0.885 | YES | 1 | 0.14963868690841242 |
| 48 | 1.0 | 0.157 | NO | 10 | 0.326345930056975 |
| 49 | 2.0 | 1.535 | YES | 10 | 0.5398346063616202 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
