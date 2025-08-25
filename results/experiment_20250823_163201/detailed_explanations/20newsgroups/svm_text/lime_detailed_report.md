# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** svm_text  
**Explanation Method:** lime  
**Generated:** 2025-08-24 15:38:29  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7950
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0384
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 159 (79.5%)
- **Incorrect Predictions:** 41 (20.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 4 | 48 | 0.0819 | 24.0% |
| 2 | 47 | 0.0851 | 23.5% |
| 3 | 47 | 0.0741 | 23.5% |
| 0 | 39 | 0.2424 | 19.5% |
| 1 | 39 | 0.1054 | 19.5% |
| 7 | 30 | 0.0859 | 15.0% |
| 8 | 29 | 0.0993 | 14.5% |
| 5 | 28 | 0.0786 | 14.0% |
| 23 | 26 | 0.0608 | 13.0% |
| 11 | 25 | 0.0699 | 12.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.017', '0.018', '0.953', '0.012']
- **Top Features:**
  - Feature 22: 0.0791
  - Feature 2: 0.0629
  - Feature 12: 0.0496

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.001', '0.001', '0.997', '0.000']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.060', '0.025', '0.502', '0.412']
- **Top Features:**
  - Feature 31: 0.0778
  - Feature 23: 0.0741
  - Feature 48: 0.0700

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.979', '0.006', '0.004', '0.012']
- **Top Features:**
  - Feature 48: 0.0454
  - Feature 0: 0.0439
  - Feature 7: 0.0395

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.024', '0.003', '0.006', '0.968']
- **Top Features:**
  - Feature 47: 0.0767
  - Feature 10: 0.0670
  - Feature 27: 0.0582

### Incorrect Predictions (Sample)

#### Instance 11

- **True Label:** 3.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.550', '0.009', '0.039', '0.402']
- **Top Features:**
  - Feature 7: 0.1075
  - Feature 31: 0.0714
  - Feature 42: 0.0701

#### Instance 12

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.327', '0.027', '0.173', '0.473']
- **Top Features:**
  - Feature 40: 0.0883
  - Feature 3: 0.0877
  - Feature 1: 0.0773

#### Instance 14

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.341', '0.160', '0.242', '0.257']
- **Top Features:**
  - Feature 7: 0.0933
  - Feature 40: 0.0824
  - Feature 2: 0.0760

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 22 | 0.0791403885414087 |
| 1 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 2 | 2.0 | 2.000 | YES | 31 | 0.07775743147948937 |
| 3 | 0.0 | 0.000 | YES | 48 | 0.04543721477897095 |
| 4 | 3.0 | 3.000 | YES | 47 | 0.07667592055855312 |
| 5 | 0.0 | 0.000 | YES | 11 | 0.0772204436206706 |
| 6 | 1.0 | 1.000 | YES | 25 | 0.12618039218582733 |
| 7 | 3.0 | 3.000 | YES | 14 | 0.07168152571926303 |
| 8 | 2.0 | 2.000 | YES | 4 | 0.2250260720651966 |
| 9 | 2.0 | 2.000 | YES | 0 | 1.0 |
| 10 | 1.0 | 1.000 | YES | 15 | 0.04796573843262435 |
| 11 | 3.0 | 0.000 | NO | 7 | 0.10745032706200947 |
| 12 | 2.0 | 3.000 | NO | 40 | 0.08834404420255991 |
| 13 | 3.0 | 3.000 | YES | 27 | 0.05522685000899579 |
| 14 | 1.0 | 0.000 | NO | 7 | 0.09332248053510787 |
| 15 | 0.0 | 2.000 | NO | 6 | 0.08046159592755289 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.1092026601833317 |
| 17 | 3.0 | 3.000 | YES | 41 | 0.0803557534880027 |
| 18 | 0.0 | 1.000 | NO | 9 | 0.2173898938095872 |
| 19 | 0.0 | 3.000 | NO | 10 | 0.07407077319645437 |
| 20 | 2.0 | 2.000 | YES | 34 | 0.09717807225961099 |
| 21 | 3.0 | 3.000 | YES | 4 | 0.14162889402913872 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.1982066413034007 |
| 23 | 0.0 | 3.000 | NO | 22 | 0.17866695747642655 |
| 24 | 2.0 | 2.000 | YES | 41 | 0.11176613162726878 |
| 25 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 26 | 1.0 | 1.000 | YES | 20 | 0.07200151628451798 |
| 27 | 3.0 | 3.000 | YES | 9 | 0.20809646749468352 |
| 28 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 29 | 0.0 | 0.000 | YES | 2 | 0.34092541976579976 |
| 30 | 1.0 | 1.000 | YES | 34 | 0.04006998161603659 |
| 31 | 3.0 | 3.000 | YES | 41 | 0.08241081739722743 |
| 32 | 0.0 | 3.000 | NO | 29 | 0.10909065548126554 |
| 33 | 2.0 | 2.000 | YES | 37 | 0.0741932025088443 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 35 | 0.0 | 0.000 | YES | 27 | 0.06279880107871214 |
| 36 | 2.0 | 2.000 | YES | 0 | 0.2857142857142857 |
| 37 | 0.0 | 0.000 | YES | 35 | 0.08865023211320244 |
| 38 | 2.0 | 2.000 | YES | 2 | 0.6283812277486182 |
| 39 | 1.0 | 1.000 | YES | 6 | 0.39839573715614024 |
| 40 | 2.0 | 2.000 | YES | 19 | 0.09420513839541805 |
| 41 | 0.0 | 0.000 | YES | 18 | 0.0765962774020782 |
| 42 | 2.0 | 2.000 | YES | 49 | 0.05438964617676806 |
| 43 | 3.0 | 3.000 | YES | 19 | 0.07475671913978521 |
| 44 | 2.0 | 3.000 | NO | 30 | 0.05049283247511729 |
| 45 | 2.0 | 2.000 | YES | 40 | 0.05397628272455576 |
| 46 | 3.0 | 3.000 | YES | 40 | 0.10993802502608496 |
| 47 | 1.0 | 1.000 | YES | 16 | 0.2595082875009329 |
| 48 | 3.0 | 1.000 | NO | 31 | 0.13939446761723331 |
| 49 | 1.0 | 1.000 | YES | 40 | 0.08056003348475634 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
