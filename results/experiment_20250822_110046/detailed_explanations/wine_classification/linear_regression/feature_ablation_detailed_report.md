# Detailed Explanation Report

**Dataset:** wine_classification  
**Model:** linear_regression  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-22 14:32:16  

## Summary Statistics

- **Total Instances:** 36
- **Valid Explanations:** 36
- **Errors:** 0
- **Model Accuracy:** 0.8611
- **Average Feature Importance:** 0.1087
- **Feature Importance Std:** 0.1678
- **Max Feature Importance:** 1.5755

## Prediction Analysis

- **Correct Predictions:** 31 (86.1%)
- **Incorrect Predictions:** 5 (13.9%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 6 | 33 | 0.5352 | 91.7% |
| 12 | 28 | 0.2433 | 77.8% |
| 11 | 26 | 0.2074 | 72.2% |
| 5 | 23 | 0.1481 | 63.9% |
| 3 | 21 | 0.1329 | 58.3% |
| 9 | 21 | 0.1677 | 58.3% |
| 0 | 11 | 0.0815 | 30.6% |
| 7 | 8 | 0.0874 | 22.2% |
| 8 | 7 | 0.0761 | 19.4% |
| 1 | 2 | 0.0938 | 5.6% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** -0.28420640024809407
- **Prediction Probabilities:** ['-0.284']
- **Top Features:**
  - Feature 6: 0.6795
  - Feature 12: 0.5414
  - Feature 11: 0.1344

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 1.788989754333345
- **Prediction Probabilities:** ['1.789']
- **Top Features:**
  - Feature 6: 0.7155
  - Feature 11: 0.2613
  - Feature 7: 0.1005

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.05887020624168804
- **Prediction Probabilities:** ['0.059']
- **Top Features:**
  - Feature 6: 0.5013
  - Feature 11: 0.1892
  - Feature 5: 0.1336

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.8408169627178115
- **Prediction Probabilities:** ['0.841']
- **Top Features:**
  - Feature 6: 0.0995
  - Feature 8: 0.0883
  - Feature 12: 0.0769

#### Instance 5

- **True Label:** 0.0
- **Prediction:** -0.14959092579272137
- **Prediction Probabilities:** ['-0.150']
- **Top Features:**
  - Feature 6: 0.5115
  - Feature 12: 0.3693
  - Feature 11: 0.1821

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 1.0
- **Prediction:** -0.1582246007544169
- **Prediction Probabilities:** ['-0.158']
- **Top Features:**
  - Feature 6: 1.5755
  - Feature 3: 0.3279
  - Feature 11: 0.2584

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.4844156137852371
- **Prediction Probabilities:** ['0.484']
- **Top Features:**
  - Feature 6: 0.6082
  - Feature 3: 0.1709
  - Feature 12: 0.1669

#### Instance 13

- **True Label:** 2.0
- **Prediction:** 1.401781527466775
- **Prediction Probabilities:** ['1.402']
- **Top Features:**
  - Feature 6: 0.3744
  - Feature 11: 0.3138
  - Feature 5: 0.1509

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | -0.284 | YES | 6 | 0.6794787822182015 |
| 1 | 2.0 | 1.789 | YES | 6 | 0.7154748088827791 |
| 2 | 0.0 | 0.059 | YES | 6 | 0.5012912797053025 |
| 3 | 1.0 | -0.158 | NO | 6 | 1.5755073662830648 |
| 4 | 1.0 | 0.841 | YES | 6 | 0.09945515733818555 |
| 5 | 0.0 | -0.150 | YES | 6 | 0.5114734227060396 |
| 6 | 0.0 | -0.131 | YES | 12 | 0.3903408286808232 |
| 7 | 1.0 | 0.484 | NO | 6 | 0.6082037812130419 |
| 8 | 1.0 | 1.202 | YES | 9 | 0.1535897961541539 |
| 9 | 2.0 | 2.068 | YES | 6 | 0.5423783778702487 |
| 10 | 1.0 | 0.907 | YES | 12 | 0.2118362516584611 |
| 11 | 2.0 | 1.668 | YES | 6 | 0.603471235874671 |
| 12 | 0.0 | -0.308 | YES | 6 | 0.8016644982270464 |
| 13 | 2.0 | 1.402 | NO | 6 | 0.3743730183580867 |
| 14 | 0.0 | -0.475 | YES | 6 | 0.842393070229995 |
| 15 | 1.0 | 1.083 | YES | 12 | 0.3003710382661039 |
| 16 | 1.0 | 0.905 | YES | 12 | 0.29826306715639817 |
| 17 | 0.0 | 0.047 | YES | 6 | 0.6031127097126732 |
| 18 | 1.0 | 0.710 | YES | 9 | 0.10859870847338882 |
| 19 | 0.0 | 0.159 | YES | 6 | 0.33328592019314063 |
| 20 | 1.0 | 0.911 | YES | 12 | 0.3158294930706129 |
| 21 | 1.0 | 1.126 | YES | 6 | 0.45583016236398355 |
| 22 | 0.0 | -0.225 | YES | 6 | 0.4554716362019854 |
| 23 | 0.0 | -0.568 | NO | 6 | 0.9900341437406825 |
| 24 | 1.0 | 0.356 | NO | 6 | 0.8983948567340486 |
| 25 | 1.0 | 1.057 | YES | 12 | 0.2701567856936544 |
| 26 | 0.0 | -0.129 | YES | 6 | 0.8576662847311002 |
| 27 | 2.0 | 1.799 | YES | 6 | 0.45583016236398355 |
| 28 | 1.0 | 0.730 | YES | 5 | 0.10349668107405785 |
| 29 | 2.0 | 2.085 | YES | 6 | 0.6900194513809363 |
| 30 | 0.0 | 0.318 | YES | 6 | 0.4758359222034597 |
| 31 | 2.0 | 1.847 | YES | 6 | 0.6645640938790938 |
| 32 | 1.0 | 1.109 | YES | 12 | 0.2771833560593402 |
| 33 | 2.0 | 2.184 | YES | 6 | 0.6238355218761451 |
| 34 | 2.0 | 2.021 | YES | 6 | 0.6645640938790938 |
| 35 | 2.0 | 1.882 | YES | 6 | 0.7002015943816735 |
