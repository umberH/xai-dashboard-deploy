# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:32:53  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.6375
- **Average Feature Importance:** 0.0909
- **Feature Importance Std:** 0.2054
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 204 (63.7%)
- **Incorrect Predictions:** 116 (36.2%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 204 | 0.3185 | 63.7% |
| 0 | 176 | 0.0633 | 55.0% |
| 7 | 172 | 0.1129 | 53.8% |
| 8 | 162 | 0.0568 | 50.6% |
| 10 | 145 | 0.7127 | 45.3% |
| 4 | 144 | 0.0666 | 45.0% |
| 6 | 143 | 0.3870 | 44.7% |
| 9 | 133 | 0.2513 | 41.6% |
| 2 | 132 | 0.0165 | 41.2% |
| 5 | 99 | 0.0449 | 30.9% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.2454908014455746
- **Prediction Probabilities:** ['1.245']
- **Top Features:**
  - Feature 10: 0.8068
  - Feature 4: 0.0537
  - Feature 9: 0.0455

#### Instance 2

- **True Label:** 0.0
- **Prediction:** -0.074243013988612
- **Prediction Probabilities:** ['-0.074']
- **Top Features:**
  - Feature 1: 0.7165
  - Feature 7: 0.1662
  - Feature 8: 0.1173

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.34263686960739365
- **Prediction Probabilities:** ['0.343']
- **Top Features:**
  - Feature 1: 0.7647
  - Feature 7: 0.1686
  - Feature 3: 0.0351

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.118043609529831
- **Prediction Probabilities:** ['1.118']
- **Top Features:**
  - Feature 10: 0.8906
  - Feature 0: 0.0616
  - Feature 4: 0.0289

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.04649308636080407
- **Prediction Probabilities:** ['0.046']
- **Top Features:**
  - Feature 6: 0.6975
  - Feature 1: 0.1769
  - Feature 7: 0.0663

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.64681275757956
- **Prediction Probabilities:** ['0.647']
- **Top Features:**
  - Feature 10: 0.7469
  - Feature 1: 0.1758
  - Feature 4: 0.0470

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.49436565303495084
- **Prediction Probabilities:** ['0.494']
- **Top Features:**
  - Feature 9: 0.8704
  - Feature 7: 0.1045
  - Feature 8: 0.0251

#### Instance 9

- **True Label:** 2.0
- **Prediction:** 0.8197238398038897
- **Prediction Probabilities:** ['0.820']
- **Top Features:**
  - Feature 10: 0.5781
  - Feature 9: 0.0901
  - Feature 1: 0.0876

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.245 | YES | 10 | 0.8067775690039183 |
| 1 | 0.0 | 0.647 | NO | 10 | 0.7469031325520178 |
| 2 | 0.0 | -0.074 | YES | 1 | 0.7164980935634268 |
| 3 | 0.0 | 0.343 | YES | 1 | 0.7647118846209917 |
| 4 | 1.0 | 0.494 | NO | 9 | 0.8703903310093069 |
| 5 | 1.0 | 1.118 | YES | 10 | 0.8906000271628642 |
| 6 | 0.0 | 0.046 | YES | 6 | 0.6974980544798741 |
| 7 | 0.0 | 0.056 | YES | 6 | 0.553834702046782 |
| 8 | 1.0 | 1.201 | YES | 10 | 0.9274029622824193 |
| 9 | 2.0 | 0.820 | NO | 10 | 0.5781300501403928 |
| 10 | 0.0 | 0.264 | YES | 1 | 0.5540237840097346 |
| 11 | 1.0 | 1.062 | YES | 10 | 0.7418314517967782 |
| 12 | 0.0 | 0.154 | YES | 6 | 0.5354832675426081 |
| 13 | 0.0 | -0.199 | YES | 1 | 0.4188449917349712 |
| 14 | 0.0 | 0.166 | YES | 6 | 0.9603854618693795 |
| 15 | 1.0 | 1.335 | YES | 10 | 0.7843708420328939 |
| 16 | 1.0 | 0.373 | NO | 1 | 0.5094651811260424 |
| 17 | 0.0 | 0.346 | YES | 6 | 0.5095887776067739 |
| 18 | 2.0 | 1.343 | NO | 10 | 0.8176647012599307 |
| 19 | 0.0 | -0.497 | YES | 6 | 0.6076042736983657 |
| 20 | 1.0 | 1.038 | YES | 10 | 0.746380198853769 |
| 21 | 1.0 | 0.762 | YES | 10 | 0.6733518310988539 |
| 22 | 0.0 | 0.403 | YES | 1 | 0.2845507832141564 |
| 23 | 1.0 | 0.503 | YES | 6 | 0.9288909883274143 |
| 24 | 0.0 | 0.186 | YES | 6 | 0.6663976311879425 |
| 25 | 1.0 | 0.498 | NO | 1 | 0.504488620421345 |
| 26 | 1.0 | 0.649 | YES | 1 | 0.5284355849371519 |
| 27 | 0.0 | -0.091 | YES | 6 | 0.40161221506913736 |
| 28 | 2.0 | 1.210 | NO | 10 | 0.7662885433822612 |
| 29 | 0.0 | 0.059 | YES | 1 | 0.5321387865997327 |
| 30 | 0.0 | 0.193 | YES | 6 | 0.64410190106744 |
| 31 | 0.0 | 0.358 | YES | 1 | 0.48240279799639263 |
| 32 | 1.0 | 0.279 | NO | 1 | 0.696523911934236 |
| 33 | 1.0 | 1.024 | YES | 10 | 0.6855757301117416 |
| 34 | 2.0 | 1.463 | NO | 10 | 0.8201670730214259 |
| 35 | 0.0 | 0.393 | YES | 6 | 0.49296294960015796 |
| 36 | 0.0 | 0.204 | YES | 6 | 0.6222711521246923 |
| 37 | 1.0 | 0.932 | YES | 10 | 0.6503023940399001 |
| 38 | 0.0 | 0.077 | YES | 6 | 0.4195773637937925 |
| 39 | 0.0 | -0.179 | YES | 6 | 0.3180358062148331 |
| 40 | 0.0 | 0.316 | YES | 1 | 0.7097684835013623 |
| 41 | 0.0 | 0.520 | NO | 10 | 0.6607167243279894 |
| 42 | 1.0 | 0.330 | NO | 4 | 0.5643616282372923 |
| 43 | 1.0 | 0.745 | YES | 10 | 0.9702130657545011 |
| 44 | 2.0 | 1.532 | YES | 10 | 0.8296077995854353 |
| 45 | 2.0 | 1.108 | NO | 9 | 0.8106200994258475 |
| 46 | 1.0 | 0.055 | NO | 6 | 0.44465219748041246 |
| 47 | 1.0 | 0.885 | YES | 10 | 0.7363104362654382 |
| 48 | 1.0 | 0.157 | NO | 1 | 0.6995374584437577 |
| 49 | 2.0 | 1.535 | YES | 10 | 0.7302480934105958 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
