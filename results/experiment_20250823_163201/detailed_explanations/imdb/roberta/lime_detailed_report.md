# Detailed Explanation Report

**Dataset:** imdb  
**Model:** roberta  
**Explanation Method:** lime  
**Generated:** 2025-08-24 00:42:51  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8700
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0228
- **Max Feature Importance:** 0.9993

## Prediction Analysis

- **Correct Predictions:** 174 (87.0%)
- **Incorrect Predictions:** 26 (13.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 35 | 0.0485 | 17.5% |
| 2 | 33 | 0.0489 | 16.5% |
| 4 | 32 | 0.0529 | 16.0% |
| 3 | 30 | 0.0583 | 15.0% |
| 7 | 26 | 0.0604 | 13.0% |
| 21 | 25 | 0.0572 | 12.5% |
| 0 | 24 | 0.0456 | 12.0% |
| 45 | 24 | 0.0705 | 12.0% |
| 47 | 24 | 0.0588 | 12.0% |
| 17 | 23 | 0.0626 | 11.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.907', '0.093']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.053', '0.947']
- **Top Features:**
  - Feature 14: 0.0800
  - Feature 46: 0.0747
  - Feature 26: 0.0595

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.033', '0.967']
- **Top Features:**
  - Feature 4: 0.0650
  - Feature 10: 0.0647
  - Feature 19: 0.0526

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.029', '0.971']
- **Top Features:**
  - Feature 25: 0.0713
  - Feature 9: 0.0605
  - Feature 7: 0.0524

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.033', '0.967']
- **Top Features:**
  - Feature 37: 0.1013
  - Feature 6: 0.0761
  - Feature 15: 0.0703

### Incorrect Predictions (Sample)

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.523', '0.477']
- **Top Features:**
  - Feature 49: 0.1608
  - Feature 7: 0.1215
  - Feature 36: 0.0506

#### Instance 16

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.712', '0.288']
- **Top Features:**
  - Feature 21: 0.1147
  - Feature 42: 0.0907
  - Feature 32: 0.0810

#### Instance 23

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.515', '0.485']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 1 | 1.0 | 1.000 | YES | 14 | 0.08004461518051245 |
| 2 | 1.0 | 1.000 | YES | 4 | 0.0649550293401921 |
| 3 | 1.0 | 1.000 | YES | 25 | 0.07129654832930088 |
| 4 | 1.0 | 1.000 | YES | 37 | 0.10126069550360975 |
| 5 | 1.0 | 1.000 | YES | 48 | 0.08327487786062528 |
| 6 | 1.0 | 1.000 | YES | 2 | 0.08144110311960734 |
| 7 | 0.0 | 0.000 | YES | 8 | 0.10266194703182725 |
| 8 | 1.0 | 0.000 | NO | 49 | 0.16076497202247614 |
| 9 | 1.0 | 1.000 | YES | 17 | 0.0903156301315876 |
| 10 | 0.0 | 0.000 | YES | 3 | 0.11525997124955313 |
| 11 | 0.0 | 0.000 | YES | 6 | 0.10651642728478042 |
| 12 | 1.0 | 1.000 | YES | 44 | 0.16935793168749 |
| 13 | 1.0 | 1.000 | YES | 32 | 0.0466096588263705 |
| 14 | 0.0 | 0.000 | YES | 27 | 0.04819913984376689 |
| 15 | 0.0 | 0.000 | YES | 23 | 0.10601863662871559 |
| 16 | 1.0 | 0.000 | NO | 21 | 0.11474423340716039 |
| 17 | 0.0 | 0.000 | YES | 17 | 0.06832750045355943 |
| 18 | 1.0 | 1.000 | YES | 8 | 0.050854179713844316 |
| 19 | 0.0 | 0.000 | YES | 16 | 0.19967679204494573 |
| 20 | 1.0 | 1.000 | YES | 3 | 0.11848868195237985 |
| 21 | 0.0 | 0.000 | YES | 15 | 0.11543118426041664 |
| 22 | 1.0 | 1.000 | YES | 6 | 0.05154806299764088 |
| 23 | 1.0 | 0.000 | NO | 0 | 0.0392156862745098 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 25 | 1.0 | 1.000 | YES | 7 | 0.07126230081752648 |
| 26 | 1.0 | 1.000 | YES | 2 | 0.04913593624729159 |
| 27 | 0.0 | 0.000 | YES | 30 | 0.11004510071700666 |
| 28 | 0.0 | 0.000 | YES | 32 | 0.08967708291954787 |
| 29 | 1.0 | 1.000 | YES | 27 | 0.09825227044509312 |
| 30 | 0.0 | 0.000 | YES | 29 | 0.057270016765390154 |
| 31 | 0.0 | 0.000 | YES | 37 | 0.10908073049904633 |
| 32 | 0.0 | 0.000 | YES | 33 | 0.08676956086969272 |
| 33 | 0.0 | 0.000 | YES | 33 | 0.06984339981083801 |
| 34 | 0.0 | 0.000 | YES | 48 | 0.13741204880845395 |
| 35 | 0.0 | 0.000 | YES | 38 | 0.06680879760862458 |
| 36 | 1.0 | 1.000 | YES | 17 | 0.1219431136215864 |
| 37 | 1.0 | 1.000 | YES | 35 | 0.12781565181501003 |
| 38 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 39 | 0.0 | 0.000 | YES | 1 | 0.07233051679018491 |
| 40 | 0.0 | 0.000 | YES | 37 | 0.0811088247247192 |
| 41 | 0.0 | 0.000 | YES | 34 | 0.08119997456322703 |
| 42 | 1.0 | 0.000 | NO | 48 | 0.06775844754672358 |
| 43 | 1.0 | 0.000 | NO | 0 | 0.0392156862745098 |
| 44 | 0.0 | 0.000 | YES | 39 | 0.05363493861242571 |
| 45 | 0.0 | 0.000 | YES | 3 | 0.06860173600034496 |
| 46 | 1.0 | 1.000 | YES | 20 | 0.07578147043831863 |
| 47 | 1.0 | 0.000 | NO | 2 | 0.06457104557326686 |
| 48 | 1.0 | 1.000 | YES | 20 | 0.08411793776092502 |
| 49 | 0.0 | 0.000 | YES | 35 | 0.12387872413306521 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
