# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** xgboost_text  
**Explanation Method:** lime  
**Generated:** 2025-08-24 19:03:56  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7100
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0503
- **Max Feature Importance:** 0.9993

## Prediction Analysis

- **Correct Predictions:** 142 (71.0%)
- **Incorrect Predictions:** 58 (29.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 44 | 0.0676 | 22.0% |
| 2 | 40 | 0.0703 | 20.0% |
| 3 | 36 | 0.0874 | 18.0% |
| 24 | 36 | 0.1329 | 18.0% |
| 10 | 34 | 0.1392 | 17.0% |
| 1 | 32 | 0.1003 | 16.0% |
| 5 | 31 | 0.1297 | 15.5% |
| 18 | 31 | 0.1742 | 15.5% |
| 9 | 30 | 0.1190 | 15.0% |
| 8 | 30 | 0.1005 | 15.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.178', '0.393', '0.211', '0.219']
- **Top Features:**
  - Feature 15: 0.9974
  - Feature 32: 0.0002
  - Feature 3: 0.0002

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.007', '0.971', '0.008', '0.014']
- **Top Features:**
  - Feature 36: 0.0937
  - Feature 41: 0.0913
  - Feature 10: 0.0906

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.657', '0.047', '0.166', '0.131']
- **Top Features:**
  - Feature 11: 0.1557
  - Feature 2: 0.0666
  - Feature 37: 0.0639

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.150', '0.654', '0.097', '0.098']
- **Top Features:**
  - Feature 7: 0.1968
  - Feature 10: 0.0780
  - Feature 24: 0.0698

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.193', '0.364', '0.248', '0.196']
- **Top Features:**
  - Feature 32: 0.4764
  - Feature 31: 0.1706
  - Feature 23: 0.0367

### Incorrect Predictions (Sample)

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.292', '0.094', '0.426', '0.189']
- **Top Features:**
  - Feature 29: 0.1107
  - Feature 14: 0.1026
  - Feature 33: 0.0759

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.014', '0.018', '0.041', '0.927']
- **Top Features:**
  - Feature 0: 0.0835
  - Feature 21: 0.0805
  - Feature 35: 0.0619

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.793', '0.120', '0.043', '0.045']
- **Top Features:**
  - Feature 5: 0.1047
  - Feature 39: 0.1015
  - Feature 7: 0.0588

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 15 | 0.9974406003033066 |
| 1 | 1.0 | 1.000 | YES | 36 | 0.09370254850160338 |
| 2 | 0.0 | 0.000 | YES | 11 | 0.15574413083618546 |
| 3 | 1.0 | 1.000 | YES | 7 | 0.19675387145954806 |
| 4 | 1.0 | 1.000 | YES | 32 | 0.4764259006628293 |
| 5 | 1.0 | 2.000 | NO | 29 | 0.11069883051655476 |
| 6 | 2.0 | 3.000 | NO | 0 | 0.08351836650816155 |
| 7 | 1.0 | 0.000 | NO | 5 | 0.10468347159788031 |
| 8 | 0.0 | 3.000 | NO | 29 | 0.0522437360577434 |
| 9 | 3.0 | 3.000 | YES | 0 | 0.05405405405405406 |
| 10 | 3.0 | 3.000 | YES | 13 | 0.08531654509143638 |
| 11 | 3.0 | 2.000 | NO | 2 | 0.20815272391919667 |
| 12 | 1.0 | 1.000 | YES | 28 | 0.08234953722165646 |
| 13 | 2.0 | 2.000 | YES | 28 | 0.22299364663617968 |
| 14 | 3.0 | 2.000 | NO | 16 | 0.1106750928360635 |
| 15 | 3.0 | 3.000 | YES | 24 | 0.07536604713700447 |
| 16 | 2.0 | 2.000 | YES | 1 | 0.5230108881595167 |
| 17 | 0.0 | 1.000 | NO | 25 | 0.07093234577308975 |
| 18 | 1.0 | 1.000 | YES | 12 | 0.5831576179526772 |
| 19 | 2.0 | 2.000 | YES | 3 | 0.10154180147929921 |
| 20 | 1.0 | 1.000 | YES | 10 | 0.662431753713064 |
| 21 | 2.0 | 2.000 | YES | 23 | 0.08168409197454789 |
| 22 | 2.0 | 2.000 | YES | 14 | 0.1639082559710519 |
| 23 | 3.0 | 3.000 | YES | 3 | 0.08716031572282097 |
| 24 | 0.0 | 0.000 | YES | 5 | 0.3213535105438092 |
| 25 | 2.0 | 3.000 | NO | 11 | 0.14767897185743512 |
| 26 | 0.0 | 0.000 | YES | 10 | 0.19061420786310182 |
| 27 | 2.0 | 2.000 | YES | 19 | 0.06834648072839322 |
| 28 | 3.0 | 3.000 | YES | 9 | 0.201651496675423 |
| 29 | 2.0 | 2.000 | YES | 43 | 0.061768245110483726 |
| 30 | 3.0 | 3.000 | YES | 0 | 0.06060606060606061 |
| 31 | 0.0 | 0.000 | YES | 18 | 0.9975222337168554 |
| 32 | 2.0 | 3.000 | NO | 0 | 0.0392156862745098 |
| 33 | 3.0 | 3.000 | YES | 8 | 0.14709343524290816 |
| 34 | 0.0 | 1.000 | NO | 22 | 0.12639687196798077 |
| 35 | 1.0 | 1.000 | YES | 33 | 0.26771383429892637 |
| 36 | 3.0 | 3.000 | YES | 8 | 0.1269459175155084 |
| 37 | 2.0 | 2.000 | YES | 1 | 0.08442738013727523 |
| 38 | 3.0 | 3.000 | YES | 22 | 0.1532605360939314 |
| 39 | 3.0 | 3.000 | YES | 0 | 0.3086708986086758 |
| 40 | 2.0 | 3.000 | NO | 38 | 0.3031882634511958 |
| 41 | 2.0 | 3.000 | NO | 18 | 0.30844187486131663 |
| 42 | 2.0 | 2.000 | YES | 35 | 0.10018162193276156 |
| 43 | 2.0 | 2.000 | YES | 31 | 0.10286455123202574 |
| 44 | 2.0 | 2.000 | YES | 35 | 0.053982147148499963 |
| 45 | 1.0 | 1.000 | YES | 9 | 0.07116536911499216 |
| 46 | 2.0 | 0.000 | NO | 24 | 0.39261852013116744 |
| 47 | 1.0 | 0.000 | NO | 33 | 0.27404466397230337 |
| 48 | 1.0 | 1.000 | YES | 22 | 0.11071872347902846 |
| 49 | 0.0 | 2.000 | NO | 10 | 0.1791278394644075 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
