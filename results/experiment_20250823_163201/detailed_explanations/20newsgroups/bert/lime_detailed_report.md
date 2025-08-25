# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** bert  
**Explanation Method:** lime  
**Generated:** 2025-08-24 05:20:13  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7150
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0425
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 143 (71.5%)
- **Incorrect Predictions:** 57 (28.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 47 | 0.1351 | 23.5% |
| 2 | 46 | 0.0847 | 23.0% |
| 0 | 40 | 0.2430 | 20.0% |
| 4 | 37 | 0.0677 | 18.5% |
| 3 | 36 | 0.0815 | 18.0% |
| 7 | 28 | 0.0878 | 14.0% |
| 11 | 28 | 0.0913 | 14.0% |
| 5 | 28 | 0.0856 | 14.0% |
| 9 | 27 | 0.0972 | 13.5% |
| 8 | 25 | 0.0758 | 12.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.193', '0.173', '0.460', '0.174']
- **Top Features:**
  - Feature 22: 0.1573
  - Feature 7: 0.1313
  - Feature 10: 0.0754

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.657', '0.120', '0.119', '0.104']
- **Top Features:**
  - Feature 29: 0.0724
  - Feature 19: 0.0605
  - Feature 39: 0.0564

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.076', '0.050', '0.073', '0.801']
- **Top Features:**
  - Feature 18: 0.0781
  - Feature 10: 0.0763
  - Feature 28: 0.0727

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.430', '0.106', '0.139', '0.325']
- **Top Features:**
  - Feature 9: 0.1379
  - Feature 2: 0.1066
  - Feature 15: 0.0499

#### Instance 7

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.131', '0.074', '0.104', '0.691']
- **Top Features:**
  - Feature 7: 0.0670
  - Feature 47: 0.0622
  - Feature 14: 0.0595

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.412', '0.170', '0.355', '0.063']
- **Top Features:**
  - Feature 10: 0.1695
  - Feature 1: 0.0796
  - Feature 9: 0.0433

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.108', '0.152', '0.348', '0.391']
- **Top Features:**
  - Feature 11: 0.1195
  - Feature 2: 0.1165
  - Feature 48: 0.0652

#### Instance 6

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.149', '0.311', '0.314', '0.226']
- **Top Features:**
  - Feature 25: 0.7295
  - Feature 0: 0.0107
  - Feature 35: 0.0093

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 22 | 0.1572602855869321 |
| 1 | 2.0 | 0.000 | NO | 10 | 0.16949813871139277 |
| 2 | 2.0 | 3.000 | NO | 11 | 0.1194842403579796 |
| 3 | 0.0 | 0.000 | YES | 29 | 0.07236804645471473 |
| 4 | 3.0 | 3.000 | YES | 18 | 0.07813007743809192 |
| 5 | 0.0 | 0.000 | YES | 9 | 0.1379018895694835 |
| 6 | 1.0 | 2.000 | NO | 25 | 0.7295040131518237 |
| 7 | 3.0 | 3.000 | YES | 7 | 0.06698225025308141 |
| 8 | 2.0 | 1.000 | NO | 2 | 0.22198618844671075 |
| 9 | 2.0 | 1.000 | NO | 0 | 1.0 |
| 10 | 1.0 | 1.000 | YES | 11 | 0.05532093786545293 |
| 11 | 3.0 | 3.000 | YES | 7 | 0.11781582438460905 |
| 12 | 2.0 | 3.000 | NO | 42 | 0.11800616666718537 |
| 13 | 3.0 | 3.000 | YES | 4 | 0.03889894996376082 |
| 14 | 1.0 | 2.000 | NO | 23 | 0.14194183145431202 |
| 15 | 0.0 | 2.000 | NO | 21 | 0.1142173687167894 |
| 16 | 1.0 | 1.000 | YES | 23 | 0.09171515537101649 |
| 17 | 3.0 | 3.000 | YES | 44 | 0.07062637747667339 |
| 18 | 0.0 | 1.000 | NO | 9 | 0.20666515695741014 |
| 19 | 0.0 | 3.000 | NO | 10 | 0.10383915775889441 |
| 20 | 2.0 | 2.000 | YES | 2 | 0.1392632619028123 |
| 21 | 3.0 | 3.000 | YES | 30 | 0.08357632090993398 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.10442125672887292 |
| 23 | 0.0 | 3.000 | NO | 22 | 0.2062163971302841 |
| 24 | 2.0 | 2.000 | YES | 6 | 0.21850547362939868 |
| 25 | 1.0 | 1.000 | YES | 39 | 0.16627483781122934 |
| 26 | 1.0 | 1.000 | YES | 32 | 0.08668655948567074 |
| 27 | 3.0 | 3.000 | YES | 17 | 0.19727778944560084 |
| 28 | 2.0 | 2.000 | YES | 7 | 0.05299101558232541 |
| 29 | 0.0 | 0.000 | YES | 2 | 0.4680150831975873 |
| 30 | 1.0 | 1.000 | YES | 3 | 0.05545038119893737 |
| 31 | 3.0 | 3.000 | YES | 41 | 0.10106508548288733 |
| 32 | 0.0 | 3.000 | NO | 8 | 0.1114957155562875 |
| 33 | 2.0 | 2.000 | YES | 27 | 0.06843741814866981 |
| 34 | 2.0 | 2.000 | YES | 30 | 0.04350430582946264 |
| 35 | 0.0 | 3.000 | NO | 7 | 0.07666033334361982 |
| 36 | 2.0 | 1.000 | NO | 0 | 0.2857142857142857 |
| 37 | 0.0 | 3.000 | NO | 11 | 0.20982402801045968 |
| 38 | 2.0 | 0.000 | NO | 1 | 0.4121691552073223 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.40369550845168267 |
| 40 | 2.0 | 2.000 | YES | 23 | 0.0666236316816729 |
| 41 | 0.0 | 0.000 | YES | 9 | 0.11101800255356813 |
| 42 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 43 | 3.0 | 3.000 | YES | 5 | 0.07562974623057016 |
| 44 | 2.0 | 3.000 | NO | 14 | 0.16184770895584102 |
| 45 | 2.0 | 2.000 | YES | 13 | 0.0680500321982437 |
| 46 | 3.0 | 3.000 | YES | 40 | 0.13297098779934594 |
| 47 | 1.0 | 1.000 | YES | 1 | 0.17782780962516653 |
| 48 | 3.0 | 1.000 | NO | 33 | 0.07374048166782832 |
| 49 | 1.0 | 1.000 | YES | 40 | 0.12356427841185234 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
