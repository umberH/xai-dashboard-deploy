# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:25:23  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.6067
- **Average Feature Importance:** 0.0989
- **Feature Importance Std:** 0.1987
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 54 (60.7%)
- **Incorrect Predictions:** 35 (39.3%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 61 | 0.2426 | 68.5% |
| 1 | 61 | 0.1564 | 68.5% |
| 8 | 55 | 0.3257 | 61.8% |
| 4 | 51 | 0.3658 | 57.3% |
| 3 | 50 | 0.1447 | 56.2% |
| 0 | 48 | 0.0205 | 53.9% |
| 6 | 38 | 0.2930 | 42.7% |
| 5 | 32 | 0.0847 | 36.0% |
| 7 | 29 | 0.0625 | 32.6% |
| 9 | 20 | 0.0272 | 22.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.9276103313847698
- **Prediction Probabilities:** ['0.928']
- **Top Features:**
  - Feature 2: 0.3521
  - Feature 8: 0.2234
  - Feature 4: 0.1867

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 1.6210881275497813
- **Prediction Probabilities:** ['1.621']
- **Top Features:**
  - Feature 2: 0.8056
  - Feature 3: 0.1758
  - Feature 6: 0.0186

#### Instance 4

- **True Label:** 0.0
- **Prediction:** -0.06895368981923744
- **Prediction Probabilities:** ['-0.069']
- **Top Features:**
  - Feature 6: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0498071549721701
- **Prediction Probabilities:** ['1.050']
- **Top Features:**
  - Feature 8: 0.3736
  - Feature 4: 0.3119
  - Feature 3: 0.1365

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 1.5272952281749965
- **Prediction Probabilities:** ['1.527']
- **Top Features:**
  - Feature 2: 0.5041
  - Feature 8: 0.4133
  - Feature 7: 0.0475

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 1.4652774878276795
- **Prediction Probabilities:** ['1.465']
- **Top Features:**
  - Feature 8: 0.4594
  - Feature 2: 0.4306
  - Feature 3: 0.0936

#### Instance 2

- **True Label:** 1.0
- **Prediction:** -0.020532226064083114
- **Prediction Probabilities:** ['-0.021']
- **Top Features:**
  - Feature 6: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 1.9841813068048744
- **Prediction Probabilities:** ['1.984']
- **Top Features:**
  - Feature 8: 0.3679
  - Feature 2: 0.2190
  - Feature 4: 0.1947

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 0.928 | YES | 2 | 0.352131688304315 |
| 1 | 0.0 | 1.465 | NO | 8 | 0.45937175660216895 |
| 2 | 1.0 | -0.021 | NO | 6 | 1.0 |
| 3 | 2.0 | 1.621 | YES | 2 | 0.8056479769109123 |
| 4 | 0.0 | -0.069 | YES | 6 | 1.0 |
| 5 | 1.0 | 1.050 | YES | 8 | 0.37363271108728097 |
| 6 | 2.0 | 1.527 | YES | 2 | 0.5040745907471279 |
| 7 | 1.0 | 1.984 | NO | 8 | 0.3678923409158473 |
| 8 | 1.0 | 0.881 | YES | 8 | 0.458226312166925 |
| 9 | 0.0 | -0.193 | YES | 6 | 1.0 |
| 10 | 1.0 | 0.370 | NO | 8 | 0.7546897592681407 |
| 11 | 0.0 | -0.348 | YES | 1 | 0.8677983370614023 |
| 12 | 0.0 | 0.798 | NO | 2 | 0.9652649977636122 |
| 13 | 2.0 | 0.864 | NO | 8 | 0.3298811538086287 |
| 14 | 1.0 | 0.670 | YES | 2 | 0.9957561337569194 |
| 15 | 2.0 | 1.599 | YES | 4 | 0.3281691669291493 |
| 16 | 0.0 | 0.556 | NO | 4 | 0.42436640553542293 |
| 17 | 0.0 | 1.317 | NO | 4 | 0.37021977478444706 |
| 18 | 0.0 | 0.294 | YES | 1 | 0.8744849695540855 |
| 19 | 0.0 | 0.239 | YES | 3 | 0.514257978076701 |
| 20 | 0.0 | 0.777 | NO | 8 | 0.3858466516770352 |
| 21 | 0.0 | 0.640 | NO | 1 | 0.23383687764667485 |
| 22 | 0.0 | -0.122 | YES | 4 | 0.888902149619334 |
| 23 | 0.0 | 0.200 | YES | 3 | 0.7249507613863736 |
| 24 | 0.0 | 0.947 | NO | 8 | 0.38176402746022975 |
| 25 | 2.0 | 1.277 | NO | 4 | 0.35981929446761063 |
| 26 | 1.0 | 0.925 | YES | 4 | 0.3731178069011578 |
| 27 | 1.0 | 1.705 | NO | 2 | 0.3830508232082731 |
| 28 | 2.0 | 1.559 | YES | 2 | 0.514301901225647 |
| 29 | 1.0 | 0.529 | YES | 4 | 0.6949795397050291 |
| 30 | 0.0 | 0.368 | YES | 2 | 0.3861255565451652 |
| 31 | 2.0 | 1.170 | NO | 4 | 0.3383887866419561 |
| 32 | 0.0 | -0.181 | YES | 6 | 1.0 |
| 33 | 1.0 | 0.098 | NO | 6 | 1.0 |
| 34 | 0.0 | 0.431 | YES | 3 | 0.5842519710579855 |
| 35 | 1.0 | 0.016 | NO | 6 | 1.0 |
| 36 | 1.0 | 1.198 | YES | 8 | 0.47117115454068603 |
| 37 | 0.0 | 0.612 | NO | 8 | 0.8101748589238595 |
| 38 | 0.0 | 0.362 | YES | 3 | 0.5473701724132565 |
| 39 | 1.0 | 0.725 | YES | 4 | 0.45218177647461044 |
| 40 | 0.0 | 0.308 | YES | 4 | 0.6000987437168743 |
| 41 | 0.0 | -0.012 | YES | 6 | 1.0 |
| 42 | 1.0 | 1.396 | YES | 8 | 0.4203236326067269 |
| 43 | 2.0 | 1.309 | NO | 8 | 0.4703735576793296 |
| 44 | 0.0 | 0.374 | YES | 3 | 0.8735933660602359 |
| 45 | 0.0 | 0.862 | NO | 8 | 0.30832146787903353 |
| 46 | 2.0 | 1.681 | YES | 8 | 0.2936512754132766 |
| 47 | 0.0 | 0.331 | YES | 6 | 1.0 |
| 48 | 0.0 | 0.180 | YES | 4 | 0.8320414864998502 |
| 49 | 1.0 | 1.117 | YES | 2 | 0.7361572582270411 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
