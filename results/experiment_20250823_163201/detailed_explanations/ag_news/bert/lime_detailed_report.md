# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** bert  
**Explanation Method:** lime  
**Generated:** 2025-08-24 15:43:16  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7900
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0282
- **Max Feature Importance:** 0.6430

## Prediction Analysis

- **Correct Predictions:** 158 (79.0%)
- **Incorrect Predictions:** 42 (21.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 56 | 0.0660 | 28.0% |
| 4 | 52 | 0.0746 | 26.0% |
| 3 | 47 | 0.0709 | 23.5% |
| 2 | 41 | 0.0652 | 20.5% |
| 1 | 39 | 0.0619 | 19.5% |
| 7 | 34 | 0.0803 | 17.0% |
| 9 | 31 | 0.0735 | 15.5% |
| 8 | 30 | 0.0903 | 15.0% |
| 12 | 30 | 0.0727 | 15.0% |
| 6 | 29 | 0.0838 | 14.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.164', '0.362', '0.216', '0.258']
- **Top Features:**
  - Feature 15: 0.3196
  - Feature 8: 0.0761
  - Feature 29: 0.0698

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.026', '0.902', '0.032', '0.040']
- **Top Features:**
  - Feature 32: 0.0536
  - Feature 14: 0.0461
  - Feature 4: 0.0435

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.536', '0.127', '0.219', '0.118']
- **Top Features:**
  - Feature 34: 0.0953
  - Feature 12: 0.0827
  - Feature 32: 0.0823

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.206', '0.622', '0.093', '0.079']
- **Top Features:**
  - Feature 29: 0.0819
  - Feature 15: 0.0733
  - Feature 24: 0.0658

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.165', '0.393', '0.237', '0.205']
- **Top Features:**
  - Feature 32: 0.1752
  - Feature 31: 0.1207
  - Feature 0: 0.0933

### Incorrect Predictions (Sample)

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.054', '0.047', '0.086', '0.813']
- **Top Features:**
  - Feature 28: 0.0595
  - Feature 25: 0.0537
  - Feature 21: 0.0490

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.432', '0.288', '0.139', '0.142']
- **Top Features:**
  - Feature 39: 0.1077
  - Feature 5: 0.1056
  - Feature 32: 0.0738

#### Instance 22

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.140', '0.208', '0.253', '0.398']
- **Top Features:**
  - Feature 28: 0.1279
  - Feature 17: 0.1046
  - Feature 3: 0.0896

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 15 | 0.3196025445035462 |
| 1 | 1.0 | 1.000 | YES | 32 | 0.053555787532930124 |
| 2 | 0.0 | 0.000 | YES | 34 | 0.09534078955866641 |
| 3 | 1.0 | 1.000 | YES | 29 | 0.08187287466199913 |
| 4 | 1.0 | 1.000 | YES | 32 | 0.1752037602520338 |
| 5 | 1.0 | 1.000 | YES | 35 | 0.1858618854912118 |
| 6 | 2.0 | 3.000 | NO | 28 | 0.05949566136535277 |
| 7 | 1.0 | 0.000 | NO | 39 | 0.10774542077644869 |
| 8 | 0.0 | 0.000 | YES | 0 | 0.15994966048007805 |
| 9 | 3.0 | 3.000 | YES | 14 | 0.15447237440000783 |
| 10 | 3.0 | 3.000 | YES | 5 | 0.07151441001104847 |
| 11 | 3.0 | 3.000 | YES | 25 | 0.1937462627741494 |
| 12 | 1.0 | 1.000 | YES | 39 | 0.06661168617479 |
| 13 | 2.0 | 2.000 | YES | 24 | 0.07211973164394368 |
| 14 | 3.0 | 3.000 | YES | 4 | 0.07154883931606498 |
| 15 | 3.0 | 3.000 | YES | 0 | 0.14321821204092897 |
| 16 | 2.0 | 2.000 | YES | 19 | 0.12068739323670614 |
| 17 | 0.0 | 0.000 | YES | 19 | 0.19778415777856562 |
| 18 | 1.0 | 1.000 | YES | 10 | 0.2166607470838231 |
| 19 | 2.0 | 2.000 | YES | 0 | 0.058823529411764705 |
| 20 | 1.0 | 1.000 | YES | 10 | 0.1373802004409965 |
| 21 | 2.0 | 2.000 | YES | 23 | 0.06702170314768438 |
| 22 | 2.0 | 3.000 | NO | 28 | 0.12794949553635965 |
| 23 | 3.0 | 3.000 | YES | 4 | 0.1326162481097411 |
| 24 | 0.0 | 0.000 | YES | 5 | 0.14865694559848433 |
| 25 | 2.0 | 3.000 | NO | 21 | 0.1717168419203109 |
| 26 | 0.0 | 0.000 | YES | 10 | 0.14034662282805227 |
| 27 | 2.0 | 2.000 | YES | 0 | 0.04081632653061224 |
| 28 | 3.0 | 3.000 | YES | 9 | 0.2572567552471128 |
| 29 | 2.0 | 2.000 | YES | 0 | 0.04081632653061224 |
| 30 | 3.0 | 3.000 | YES | 22 | 0.09792518527770036 |
| 31 | 0.0 | 0.000 | YES | 12 | 0.08682618827786592 |
| 32 | 2.0 | 3.000 | NO | 48 | 0.046026969545387854 |
| 33 | 3.0 | 3.000 | YES | 8 | 0.08476203692919494 |
| 34 | 0.0 | 1.000 | NO | 1 | 0.08690894082359632 |
| 35 | 1.0 | 1.000 | YES | 1 | 0.1023658745843846 |
| 36 | 3.0 | 3.000 | YES | 8 | 0.1778320566134197 |
| 37 | 2.0 | 2.000 | YES | 0 | 0.0625 |
| 38 | 3.0 | 3.000 | YES | 22 | 0.2161854376503056 |
| 39 | 3.0 | 0.000 | NO | 6 | 0.1993783242304213 |
| 40 | 2.0 | 2.000 | YES | 38 | 0.3062466188843617 |
| 41 | 2.0 | 2.000 | YES | 4 | 0.10253061260768065 |
| 42 | 2.0 | 2.000 | YES | 23 | 0.08865290208722384 |
| 43 | 2.0 | 2.000 | YES | 36 | 0.050673381737079894 |
| 44 | 2.0 | 2.000 | YES | 0 | 0.05263157894736842 |
| 45 | 1.0 | 1.000 | YES | 8 | 0.07257541424269318 |
| 46 | 2.0 | 2.000 | YES | 1 | 0.053787992707566006 |
| 47 | 1.0 | 1.000 | YES | 33 | 0.14463610340441652 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.05555555555555555 |
| 49 | 0.0 | 2.000 | NO | 14 | 0.19753941654858773 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
