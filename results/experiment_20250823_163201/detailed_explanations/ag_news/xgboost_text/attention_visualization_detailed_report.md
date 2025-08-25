# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** xgboost_text  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 19:04:47  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7100
- **Average Feature Importance:** 0.0680
- **Feature Importance Std:** 0.0514
- **Max Feature Importance:** 0.4629

## Prediction Analysis

- **Correct Predictions:** 142 (71.0%)
- **Incorrect Predictions:** 58 (29.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 127 | 0.0880 | 63.5% |
| 1 | 105 | 0.0928 | 52.5% |
| 2 | 101 | 0.0886 | 50.5% |
| 19 | 26 | 0.0802 | 13.0% |
| 17 | 21 | 0.0929 | 10.5% |
| 9 | 21 | 0.1114 | 10.5% |
| 10 | 20 | 0.0759 | 10.0% |
| 12 | 20 | 0.0808 | 10.0% |
| 6 | 20 | 0.1016 | 10.0% |
| 28 | 20 | 0.0972 | 10.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.178', '0.393', '0.211', '0.219']
- **Top Features:**
  - Feature 15: 0.0525
  - Feature 0: 0.0350
  - Feature 2: 0.0327

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.007', '0.971', '0.008', '0.014']
- **Top Features:**
  - Feature 42: 0.0286
  - Feature 0: 0.0259
  - Feature 43: 0.0256

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.657', '0.047', '0.166', '0.131']
- **Top Features:**
  - Feature 18: 0.0313
  - Feature 1: 0.0306
  - Feature 2: 0.0306

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.150', '0.654', '0.097', '0.098']
- **Top Features:**
  - Feature 0: 0.0363
  - Feature 1: 0.0363
  - Feature 31: 0.0350

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.193', '0.364', '0.248', '0.196']
- **Top Features:**
  - Feature 32: 0.0536
  - Feature 31: 0.0406
  - Feature 2: 0.0335

### Incorrect Predictions (Sample)

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.292', '0.094', '0.426', '0.189']
- **Top Features:**
  - Feature 14: 0.1156
  - Feature 0: 0.0959
  - Feature 33: 0.0946

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.014', '0.018', '0.041', '0.927']
- **Top Features:**
  - Feature 19: 0.1645
  - Feature 0: 0.1555
  - Feature 35: 0.1500

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.793', '0.120', '0.043', '0.045']
- **Top Features:**
  - Feature 11: 0.0293
  - Feature 0: 0.0269
  - Feature 36: 0.0269

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 15 | 0.052519409346932555 |
| 1 | 1.0 | 1.000 | YES | 42 | 0.028645511791579203 |
| 2 | 0.0 | 0.000 | YES | 18 | 0.03131808278867102 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.036339610175090846 |
| 4 | 1.0 | 1.000 | YES | 32 | 0.05358502055107322 |
| 5 | 1.0 | 2.000 | NO | 14 | 0.11556912341910158 |
| 6 | 2.0 | 3.000 | NO | 19 | 0.16450096765275088 |
| 7 | 1.0 | 0.000 | NO | 11 | 0.029307607766516055 |
| 8 | 0.0 | 3.000 | NO | 26 | 0.13917004048582993 |
| 9 | 3.0 | 3.000 | YES | 1 | 0.1697667552406259 |
| 10 | 3.0 | 3.000 | YES | 11 | 0.1544223945327901 |
| 11 | 3.0 | 2.000 | NO | 25 | 0.15933572710951524 |
| 12 | 1.0 | 1.000 | YES | 1 | 0.02889414236931967 |
| 13 | 2.0 | 2.000 | YES | 40 | 0.09387121799844839 |
| 14 | 3.0 | 2.000 | NO | 15 | 0.09409397561841637 |
| 15 | 3.0 | 3.000 | YES | 1 | 0.15102698348771645 |
| 16 | 2.0 | 2.000 | YES | 2 | 0.14361429304154555 |
| 17 | 0.0 | 1.000 | NO | 5 | 0.033672022684310014 |
| 18 | 1.0 | 1.000 | YES | 12 | 0.04546249344290959 |
| 19 | 2.0 | 2.000 | YES | 30 | 0.10392720306513407 |
| 20 | 1.0 | 1.000 | YES | 10 | 0.042991563919532766 |
| 21 | 2.0 | 2.000 | YES | 32 | 0.07412398921832883 |
| 22 | 2.0 | 2.000 | YES | 28 | 0.1460131170176044 |
| 23 | 3.0 | 3.000 | YES | 8 | 0.24407976734524303 |
| 24 | 0.0 | 0.000 | YES | 5 | 0.09771986970684039 |
| 25 | 2.0 | 3.000 | NO | 21 | 0.36384217335058205 |
| 26 | 0.0 | 0.000 | YES | 20 | 0.027065343472096916 |
| 27 | 2.0 | 2.000 | YES | 20 | 0.07500833425936215 |
| 28 | 3.0 | 3.000 | YES | 9 | 0.2643234747821117 |
| 29 | 2.0 | 2.000 | YES | 35 | 0.07492507492507491 |
| 30 | 3.0 | 3.000 | YES | 7 | 0.1990379830817714 |
| 31 | 0.0 | 0.000 | YES | 18 | 0.062268979243673576 |
| 32 | 2.0 | 3.000 | NO | 53 | 0.11740659758532179 |
| 33 | 3.0 | 3.000 | YES | 28 | 0.15990696322139844 |
| 34 | 0.0 | 1.000 | NO | 25 | 0.043540768124871634 |
| 35 | 1.0 | 1.000 | YES | 0 | 0.03186558516801854 |
| 36 | 3.0 | 3.000 | YES | 2 | 0.203756201275691 |
| 37 | 2.0 | 2.000 | YES | 30 | 0.11455108359133125 |
| 38 | 3.0 | 3.000 | YES | 30 | 0.185501795178663 |
| 39 | 3.0 | 3.000 | YES | 0 | 0.3785329744279946 |
| 40 | 2.0 | 3.000 | NO | 38 | 0.20176376269374663 |
| 41 | 2.0 | 3.000 | NO | 1 | 0.1883070301291248 |
| 42 | 2.0 | 2.000 | YES | 23 | 0.1059926620464737 |
| 43 | 2.0 | 2.000 | YES | 40 | 0.08102818371607515 |
| 44 | 2.0 | 2.000 | YES | 1 | 0.09477311889718551 |
| 45 | 1.0 | 1.000 | YES | 1 | 0.03065031982942431 |
| 46 | 2.0 | 0.000 | NO | 0 | 0.026623451788401434 |
| 47 | 1.0 | 0.000 | NO | 8 | 0.04376367614879649 |
| 48 | 1.0 | 1.000 | YES | 15 | 0.036041447664814534 |
| 49 | 0.0 | 2.000 | NO | 2 | 0.14439411098527744 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
