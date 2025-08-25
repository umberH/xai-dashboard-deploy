# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:35:49  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.6067
- **Average Feature Importance:** 0.0989
- **Feature Importance Std:** 0.2001
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 54 (60.7%)
- **Incorrect Predictions:** 35 (39.3%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 61 | 0.2669 | 68.5% |
| 3 | 54 | 0.1422 | 60.7% |
| 8 | 53 | 0.3191 | 59.6% |
| 4 | 52 | 0.3510 | 58.4% |
| 1 | 52 | 0.1669 | 58.4% |
| 0 | 44 | 0.0183 | 49.4% |
| 5 | 43 | 0.0752 | 48.3% |
| 6 | 42 | 0.2633 | 47.2% |
| 7 | 27 | 0.0776 | 30.3% |
| 9 | 17 | 0.0249 | 19.1% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.9276103313847698
- **Prediction Probabilities:** ['0.928']
- **Top Features:**
  - Feature 2: 0.3616
  - Feature 4: 0.2070
  - Feature 8: 0.1804

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 1.6210881275497813
- **Prediction Probabilities:** ['1.621']
- **Top Features:**
  - Feature 2: 0.7686
  - Feature 3: 0.2101
  - Feature 6: 0.0213

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
  - Feature 8: 0.5255
  - Feature 4: 0.2507
  - Feature 3: 0.0731

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 1.5272952281749965
- **Prediction Probabilities:** ['1.527']
- **Top Features:**
  - Feature 2: 0.5619
  - Feature 8: 0.3483
  - Feature 7: 0.0611

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 1.4652774878276795
- **Prediction Probabilities:** ['1.465']
- **Top Features:**
  - Feature 2: 0.4403
  - Feature 8: 0.3804
  - Feature 3: 0.1502

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
  - Feature 2: 0.3871
  - Feature 4: 0.1834
  - Feature 8: 0.1813

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 0.928 | YES | 2 | 0.36155955651756055 |
| 1 | 0.0 | 1.465 | NO | 2 | 0.4402855126310777 |
| 2 | 1.0 | -0.021 | NO | 6 | 1.0 |
| 3 | 2.0 | 1.621 | YES | 2 | 0.7685826641117572 |
| 4 | 0.0 | -0.069 | YES | 6 | 1.0 |
| 5 | 1.0 | 1.050 | YES | 8 | 0.5254622997065167 |
| 6 | 2.0 | 1.527 | YES | 2 | 0.5619040142199623 |
| 7 | 1.0 | 1.984 | NO | 2 | 0.3871447962961335 |
| 8 | 1.0 | 0.881 | YES | 4 | 0.4956435930510832 |
| 9 | 0.0 | -0.193 | YES | 6 | 1.0 |
| 10 | 1.0 | 0.370 | NO | 8 | 0.7458857212498118 |
| 11 | 0.0 | -0.348 | YES | 1 | 0.905088710579205 |
| 12 | 0.0 | 0.798 | NO | 2 | 0.9724556037106016 |
| 13 | 2.0 | 0.864 | NO | 2 | 0.3785725012984786 |
| 14 | 1.0 | 0.670 | YES | 2 | 0.9918613714180493 |
| 15 | 2.0 | 1.599 | YES | 4 | 0.32383748613893515 |
| 16 | 0.0 | 0.556 | NO | 4 | 0.4174364623255147 |
| 17 | 0.0 | 1.317 | NO | 2 | 0.4334005453736399 |
| 18 | 0.0 | 0.294 | YES | 1 | 0.9136893218161468 |
| 19 | 0.0 | 0.239 | YES | 3 | 0.5465664017796953 |
| 20 | 0.0 | 0.777 | NO | 4 | 0.326802375904747 |
| 21 | 0.0 | 0.640 | NO | 4 | 0.2847913934100769 |
| 22 | 0.0 | -0.122 | YES | 4 | 0.9039654118426906 |
| 23 | 0.0 | 0.200 | YES | 3 | 0.7713692603955442 |
| 24 | 0.0 | 0.947 | NO | 8 | 0.40192825558526984 |
| 25 | 2.0 | 1.277 | NO | 4 | 0.3430849067474374 |
| 26 | 1.0 | 0.925 | YES | 8 | 0.5255447487312151 |
| 27 | 1.0 | 1.705 | NO | 2 | 0.5145624876843761 |
| 28 | 2.0 | 1.559 | YES | 8 | 0.28825897839642334 |
| 29 | 1.0 | 0.529 | YES | 4 | 0.7661878943162636 |
| 30 | 0.0 | 0.368 | YES | 4 | 0.40043759273199847 |
| 31 | 2.0 | 1.170 | NO | 8 | 0.35189235778177097 |
| 32 | 0.0 | -0.181 | YES | 6 | 1.0 |
| 33 | 1.0 | 0.098 | NO | 6 | 1.0 |
| 34 | 0.0 | 0.431 | YES | 1 | 0.5597776274030299 |
| 35 | 1.0 | 0.016 | NO | 6 | 1.0 |
| 36 | 1.0 | 1.198 | YES | 8 | 0.5491838330008374 |
| 37 | 0.0 | 0.612 | NO | 8 | 0.795276667927504 |
| 38 | 0.0 | 0.362 | YES | 3 | 0.5858649464070583 |
| 39 | 1.0 | 0.725 | YES | 4 | 0.4550017523689944 |
| 40 | 0.0 | 0.308 | YES | 4 | 0.6612984578772528 |
| 41 | 0.0 | -0.012 | YES | 6 | 0.9999956312154819 |
| 42 | 1.0 | 1.396 | YES | 2 | 0.5188403402283053 |
| 43 | 2.0 | 1.309 | NO | 8 | 0.42726505699187667 |
| 44 | 0.0 | 0.374 | YES | 3 | 0.8420753994480457 |
| 45 | 0.0 | 0.862 | NO | 2 | 0.44838540532083765 |
| 46 | 2.0 | 1.681 | YES | 2 | 0.27383012368635895 |
| 47 | 0.0 | 0.331 | YES | 6 | 1.0 |
| 48 | 0.0 | 0.180 | YES | 4 | 0.7729170647809527 |
| 49 | 1.0 | 1.117 | YES | 2 | 0.7057001395184778 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
