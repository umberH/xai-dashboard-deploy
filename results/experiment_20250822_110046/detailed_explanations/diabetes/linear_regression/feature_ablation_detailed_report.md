# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** linear_regression  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-22 14:25:32  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.6067
- **Average Feature Importance:** 0.1184
- **Feature Importance Std:** 0.1292
- **Max Feature Importance:** 0.7868

## Prediction Analysis

- **Correct Predictions:** 54 (60.7%)
- **Incorrect Predictions:** 35 (39.3%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 4 | 76 | 0.2700 | 85.4% |
| 1 | 74 | 0.1286 | 83.1% |
| 8 | 69 | 0.2797 | 77.5% |
| 2 | 62 | 0.2689 | 69.7% |
| 3 | 55 | 0.1670 | 61.8% |
| 5 | 52 | 0.1515 | 58.4% |
| 7 | 50 | 0.1369 | 56.2% |
| 6 | 5 | 0.0753 | 5.6% |
| 0 | 1 | 0.0562 | 1.1% |
| 9 | 1 | 0.0337 | 1.1% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.9276103313847698
- **Prediction Probabilities:** ['0.928']
- **Top Features:**
  - Feature 4: 0.7286
  - Feature 8: 0.3849
  - Feature 5: 0.3581

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 1.6210881275497813
- **Prediction Probabilities:** ['1.621']
- **Top Features:**
  - Feature 2: 0.6735
  - Feature 3: 0.1964
  - Feature 4: 0.1848

#### Instance 4

- **True Label:** 0.0
- **Prediction:** -0.06895368981923744
- **Prediction Probabilities:** ['-0.069']
- **Top Features:**
  - Feature 2: 0.3505
  - Feature 3: 0.2595
  - Feature 8: 0.2183

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0498071549721701
- **Prediction Probabilities:** ['1.050']
- **Top Features:**
  - Feature 8: 0.2624
  - Feature 3: 0.1855
  - Feature 7: 0.1657

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 1.5272952281749965
- **Prediction Probabilities:** ['1.527']
- **Top Features:**
  - Feature 8: 0.3135
  - Feature 2: 0.2924
  - Feature 4: 0.2707

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 1.4652774878276795
- **Prediction Probabilities:** ['1.465']
- **Top Features:**
  - Feature 8: 0.3902
  - Feature 2: 0.2412
  - Feature 5: 0.1317

#### Instance 2

- **True Label:** 1.0
- **Prediction:** -0.020532226064083114
- **Prediction Probabilities:** ['-0.021']
- **Top Features:**
  - Feature 8: 0.5190
  - Feature 4: 0.4268
  - Feature 2: 0.2936

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 1.9841813068048744
- **Prediction Probabilities:** ['1.984']
- **Top Features:**
  - Feature 8: 0.6031
  - Feature 7: 0.3285
  - Feature 4: 0.3149

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 0.928 | YES | 4 | 0.7286456271535423 |
| 1 | 0.0 | 1.465 | NO | 8 | 0.39015163097507544 |
| 2 | 1.0 | -0.021 | NO | 8 | 0.5189862535615395 |
| 3 | 2.0 | 1.621 | YES | 2 | 0.6735209900780234 |
| 4 | 0.0 | -0.069 | YES | 2 | 0.3504668478268314 |
| 5 | 1.0 | 1.050 | YES | 8 | 0.26243336453162014 |
| 6 | 2.0 | 1.527 | YES | 8 | 0.31349861268647294 |
| 7 | 1.0 | 1.984 | NO | 8 | 0.6030705544371564 |
| 8 | 1.0 | 0.881 | YES | 8 | 0.14353846709980267 |
| 9 | 0.0 | -0.193 | YES | 8 | 0.49207497807604456 |
| 10 | 1.0 | 0.370 | NO | 2 | 0.3504668478268315 |
| 11 | 0.0 | -0.348 | YES | 8 | 0.756555464199883 |
| 12 | 0.0 | 0.798 | NO | 8 | 0.3638052510693621 |
| 13 | 2.0 | 0.864 | NO | 4 | 0.15358067187598112 |
| 14 | 1.0 | 0.670 | YES | 4 | 0.4268366052037095 |
| 15 | 2.0 | 1.599 | YES | 8 | 0.4310148587102218 |
| 16 | 0.0 | 0.556 | NO | 4 | 0.40073850716026804 |
| 17 | 0.0 | 1.317 | NO | 4 | 0.6818017528687887 |
| 18 | 0.0 | 0.294 | YES | 4 | 0.1770026090183578 |
| 19 | 0.0 | 0.239 | YES | 2 | 0.2992674559315889 |
| 20 | 0.0 | 0.777 | NO | 4 | 0.627150566203243 |
| 21 | 0.0 | 0.640 | NO | 3 | 0.17468349035455233 |
| 22 | 0.0 | -0.122 | YES | 2 | 0.3447780265051378 |
| 23 | 0.0 | 0.200 | YES | 8 | 0.25979978884468324 |
| 24 | 0.0 | 0.947 | NO | 1 | 0.1371546486552616 |
| 25 | 2.0 | 1.277 | NO | 4 | 0.44758238144502127 |
| 26 | 1.0 | 0.925 | YES | 7 | 0.16573792827675982 |
| 27 | 1.0 | 1.705 | NO | 2 | 0.7190315606515723 |
| 28 | 2.0 | 1.559 | YES | 4 | 0.5022335681105674 |
| 29 | 1.0 | 0.529 | YES | 1 | 0.11901249936223751 |
| 30 | 0.0 | 0.368 | YES | 4 | 0.2133630100212543 |
| 31 | 2.0 | 1.170 | NO | 8 | 0.2885725952285966 |
| 32 | 0.0 | -0.181 | YES | 2 | 0.39597741840038075 |
| 33 | 1.0 | 0.098 | NO | 8 | 0.4070949052827092 |
| 34 | 0.0 | 0.431 | YES | 8 | 0.2345428950488706 |
| 35 | 1.0 | 0.016 | NO | 2 | 0.40735506104376784 |
| 36 | 1.0 | 1.198 | YES | 8 | 0.368534376896563 |
| 37 | 0.0 | 0.612 | NO | 2 | 0.20824631478449052 |
| 38 | 0.0 | 0.362 | YES | 4 | 0.20823185854152682 |
| 39 | 1.0 | 0.725 | YES | 8 | 0.4058682570270549 |
| 40 | 0.0 | 0.308 | YES | 1 | 0.1371546486552615 |
| 41 | 0.0 | -0.012 | YES | 3 | 0.35720711652045045 |
| 42 | 1.0 | 1.396 | YES | 8 | 0.3875046202715837 |
| 43 | 2.0 | 1.309 | NO | 8 | 0.7868172141045102 |
| 44 | 0.0 | 0.374 | YES | 2 | 0.3163339198966698 |
| 45 | 0.0 | 0.862 | NO | 4 | 0.34608732049472224 |
| 46 | 2.0 | 1.681 | YES | 8 | 0.7325534946829387 |
| 47 | 0.0 | 0.331 | YES | 4 | 0.3878000432997482 |
| 48 | 0.0 | 0.180 | YES | 2 | 0.37891095443529976 |
| 49 | 1.0 | 1.117 | YES | 3 | 0.2832325937984307 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
