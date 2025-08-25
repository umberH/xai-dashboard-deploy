# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** lstm  
**Explanation Method:** lime  
**Generated:** 2025-08-24 05:21:31  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7100
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0401
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 142 (71.0%)
- **Incorrect Predictions:** 58 (29.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 3 | 50 | 0.0778 | 25.0% |
| 1 | 49 | 0.1067 | 24.5% |
| 4 | 41 | 0.0930 | 20.5% |
| 2 | 39 | 0.0897 | 19.5% |
| 0 | 38 | 0.2472 | 19.0% |
| 15 | 30 | 0.0691 | 15.0% |
| 5 | 30 | 0.0972 | 15.0% |
| 7 | 29 | 0.0768 | 14.5% |
| 10 | 25 | 0.0622 | 12.5% |
| 14 | 25 | 0.0752 | 12.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.156', '0.104', '0.562', '0.178']
- **Top Features:**
  - Feature 22: 0.0824
  - Feature 7: 0.0749
  - Feature 34: 0.0614

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.599', '0.110', '0.108', '0.182']
- **Top Features:**
  - Feature 13: 0.0862
  - Feature 28: 0.0621
  - Feature 2: 0.0544

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.051', '0.016', '0.020', '0.913']
- **Top Features:**
  - Feature 28: 0.0455
  - Feature 31: 0.0432
  - Feature 3: 0.0403

#### Instance 6

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.151', '0.359', '0.241', '0.249']
- **Top Features:**
  - Feature 25: 0.2223
  - Feature 11: 0.0821
  - Feature 26: 0.0761

#### Instance 7

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.115', '0.031', '0.057', '0.797']
- **Top Features:**
  - Feature 32: 0.0568
  - Feature 45: 0.0552
  - Feature 1: 0.0514

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.417', '0.118', '0.345', '0.120']
- **Top Features:**
  - Feature 1: 0.0942
  - Feature 9: 0.0849
  - Feature 12: 0.0650

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.117', '0.114', '0.305', '0.464']
- **Top Features:**
  - Feature 2: 0.1465
  - Feature 48: 0.0867
  - Feature 45: 0.0661

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.389', '0.038', '0.082', '0.491']
- **Top Features:**
  - Feature 12: 0.1174
  - Feature 2: 0.0921
  - Feature 36: 0.0786

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 22 | 0.08235151431338449 |
| 1 | 2.0 | 0.000 | NO | 1 | 0.09417284496397503 |
| 2 | 2.0 | 3.000 | NO | 2 | 0.14650326123227717 |
| 3 | 0.0 | 0.000 | YES | 13 | 0.08619566495038358 |
| 4 | 3.0 | 3.000 | YES | 28 | 0.04552403863985014 |
| 5 | 0.0 | 3.000 | NO | 12 | 0.11739507970773373 |
| 6 | 1.0 | 1.000 | YES | 25 | 0.22234069642788132 |
| 7 | 3.0 | 3.000 | YES | 32 | 0.05680637616582883 |
| 8 | 2.0 | 2.000 | YES | 1 | 0.20912887479286937 |
| 9 | 2.0 | 2.000 | YES | 0 | 1.0 |
| 10 | 1.0 | 1.000 | YES | 44 | 0.04771824041611207 |
| 11 | 3.0 | 3.000 | YES | 4 | 0.08210062308445007 |
| 12 | 2.0 | 3.000 | NO | 0 | 0.041666666666666664 |
| 13 | 3.0 | 3.000 | YES | 31 | 0.047710625486130274 |
| 14 | 1.0 | 1.000 | YES | 23 | 0.2622732545873733 |
| 15 | 0.0 | 2.000 | NO | 49 | 0.10917399074779693 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.1504833012720103 |
| 17 | 3.0 | 3.000 | YES | 37 | 0.050646417772845176 |
| 18 | 0.0 | 3.000 | NO | 0 | 0.28028560509711287 |
| 19 | 0.0 | 3.000 | NO | 37 | 0.10077945192306505 |
| 20 | 2.0 | 2.000 | YES | 34 | 0.1790799096608676 |
| 21 | 3.0 | 3.000 | YES | 30 | 0.09298153905076252 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.08031693654781043 |
| 23 | 0.0 | 3.000 | NO | 22 | 0.17917032138280198 |
| 24 | 2.0 | 3.000 | NO | 4 | 0.14561961727993622 |
| 25 | 1.0 | 1.000 | YES | 0 | 0.5670355821474122 |
| 26 | 1.0 | 1.000 | YES | 26 | 0.09908752803334646 |
| 27 | 3.0 | 3.000 | YES | 17 | 0.13438521011492693 |
| 28 | 2.0 | 2.000 | YES | 19 | 0.05826404718530416 |
| 29 | 0.0 | 0.000 | YES | 2 | 0.2505969253326207 |
| 30 | 1.0 | 1.000 | YES | 0 | 0.05000918787991348 |
| 31 | 3.0 | 3.000 | YES | 17 | 0.05964134306254906 |
| 32 | 0.0 | 3.000 | NO | 8 | 0.07656233209946225 |
| 33 | 2.0 | 2.000 | YES | 9 | 0.11478883382787036 |
| 34 | 2.0 | 2.000 | YES | 21 | 0.03947262785648387 |
| 35 | 0.0 | 3.000 | NO | 48 | 0.1122588930795934 |
| 36 | 2.0 | 2.000 | YES | 1 | 0.1898434665127084 |
| 37 | 0.0 | 3.000 | NO | 11 | 0.1026997875085532 |
| 38 | 2.0 | 3.000 | NO | 4 | 0.3875119569019969 |
| 39 | 1.0 | 1.000 | YES | 6 | 0.3512789166646262 |
| 40 | 2.0 | 1.000 | NO | 5 | 0.10969887427438275 |
| 41 | 0.0 | 0.000 | YES | 9 | 0.11017862802575223 |
| 42 | 2.0 | 2.000 | YES | 7 | 0.05109623262301444 |
| 43 | 3.0 | 3.000 | YES | 21 | 0.05349924757309117 |
| 44 | 2.0 | 3.000 | NO | 14 | 0.09741153825692098 |
| 45 | 2.0 | 2.000 | YES | 44 | 0.07009238196947462 |
| 46 | 3.0 | 3.000 | YES | 32 | 0.07745200202099954 |
| 47 | 1.0 | 1.000 | YES | 5 | 0.22261325153285524 |
| 48 | 3.0 | 1.000 | NO | 31 | 0.10462474147338911 |
| 49 | 1.0 | 1.000 | YES | 40 | 0.12051850676572348 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
