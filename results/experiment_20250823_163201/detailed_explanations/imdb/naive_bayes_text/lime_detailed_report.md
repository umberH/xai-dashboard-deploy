# Detailed Explanation Report

**Dataset:** imdb  
**Model:** naive_bayes_text  
**Explanation Method:** lime  
**Generated:** 2025-08-24 05:08:01  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8050
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0198
- **Max Feature Importance:** 0.5636

## Prediction Analysis

- **Correct Predictions:** 161 (80.5%)
- **Incorrect Predictions:** 39 (19.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 41 | 0.0540 | 20.5% |
| 4 | 34 | 0.0606 | 17.0% |
| 3 | 32 | 0.0559 | 16.0% |
| 5 | 29 | 0.0757 | 14.5% |
| 29 | 27 | 0.0579 | 13.5% |
| 7 | 25 | 0.0650 | 12.5% |
| 38 | 24 | 0.0701 | 12.0% |
| 2 | 24 | 0.0555 | 12.0% |
| 6 | 24 | 0.0722 | 12.0% |
| 22 | 24 | 0.0654 | 12.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.759', '0.241']
- **Top Features:**
  - Feature 24: 0.0558
  - Feature 45: 0.0427
  - Feature 29: 0.0421

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.364', '0.636']
- **Top Features:**
  - Feature 25: 0.0657
  - Feature 46: 0.0565
  - Feature 32: 0.0441

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.377', '0.623']
- **Top Features:**
  - Feature 20: 0.0574
  - Feature 33: 0.0557
  - Feature 26: 0.0482

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.306', '0.694']
- **Top Features:**
  - Feature 33: 0.0448
  - Feature 28: 0.0383
  - Feature 15: 0.0361

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.329', '0.671']
- **Top Features:**
  - Feature 9: 0.0912
  - Feature 48: 0.0665
  - Feature 37: 0.0613

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.559', '0.441']
- **Top Features:**
  - Feature 23: 0.1204
  - Feature 4: 0.0722
  - Feature 32: 0.0682

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.478', '0.522']
- **Top Features:**
  - Feature 5: 0.0721
  - Feature 46: 0.0600
  - Feature 30: 0.0590

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.593', '0.407']
- **Top Features:**
  - Feature 7: 0.1170
  - Feature 15: 0.0930
  - Feature 16: 0.0787

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 24 | 0.05581265178668622 |
| 1 | 1.0 | 1.000 | YES | 25 | 0.06566025588923018 |
| 2 | 1.0 | 0.000 | NO | 23 | 0.12044451900280714 |
| 3 | 1.0 | 1.000 | YES | 20 | 0.0574108911820492 |
| 4 | 1.0 | 1.000 | YES | 33 | 0.04484338096545625 |
| 5 | 1.0 | 1.000 | YES | 9 | 0.09117619126325896 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 7 | 0.0 | 1.000 | NO | 5 | 0.07208121655886492 |
| 8 | 1.0 | 0.000 | NO | 7 | 0.11699762333379161 |
| 9 | 1.0 | 1.000 | YES | 28 | 0.07014583115471222 |
| 10 | 0.0 | 0.000 | YES | 30 | 0.11825607354069283 |
| 11 | 0.0 | 0.000 | YES | 9 | 0.0946729872032559 |
| 12 | 1.0 | 1.000 | YES | 20 | 0.12548906660667553 |
| 13 | 1.0 | 1.000 | YES | 3 | 0.0942372597424761 |
| 14 | 0.0 | 0.000 | YES | 17 | 0.06744174211576152 |
| 15 | 0.0 | 0.000 | YES | 47 | 0.08063684567905151 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.17369793927265587 |
| 17 | 0.0 | 1.000 | NO | 14 | 0.06108825800111392 |
| 18 | 1.0 | 1.000 | YES | 29 | 0.09269511405844198 |
| 19 | 0.0 | 0.000 | YES | 21 | 0.08285117631492749 |
| 20 | 1.0 | 1.000 | YES | 3 | 0.1330168507006683 |
| 21 | 0.0 | 0.000 | YES | 38 | 0.14592514906799017 |
| 22 | 1.0 | 1.000 | YES | 28 | 0.08606677471414449 |
| 23 | 1.0 | 0.000 | NO | 2 | 0.07523761432394782 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 25 | 1.0 | 1.000 | YES | 26 | 0.06314375912258838 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 27 | 0.0 | 0.000 | YES | 8 | 0.056063886029473674 |
| 28 | 0.0 | 0.000 | YES | 3 | 0.09217991475558412 |
| 29 | 1.0 | 1.000 | YES | 4 | 0.12373361476862108 |
| 30 | 0.0 | 0.000 | YES | 26 | 0.08163790972923408 |
| 31 | 0.0 | 0.000 | YES | 17 | 0.11005723357642763 |
| 32 | 0.0 | 0.000 | YES | 9 | 0.04671058584111869 |
| 33 | 0.0 | 0.000 | YES | 16 | 0.07952365424350105 |
| 34 | 0.0 | 0.000 | YES | 41 | 0.0390042691894387 |
| 35 | 0.0 | 0.000 | YES | 23 | 0.12037874874497029 |
| 36 | 1.0 | 0.000 | NO | 19 | 0.09680715262052507 |
| 37 | 1.0 | 1.000 | YES | 35 | 0.08536475528068292 |
| 38 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 39 | 0.0 | 0.000 | YES | 24 | 0.11858964000881295 |
| 40 | 0.0 | 0.000 | YES | 11 | 0.11469070380264983 |
| 41 | 0.0 | 1.000 | NO | 22 | 0.13154164442778393 |
| 42 | 1.0 | 0.000 | NO | 16 | 0.09209965832503396 |
| 43 | 1.0 | 1.000 | YES | 45 | 0.0789109020528263 |
| 44 | 0.0 | 0.000 | YES | 46 | 0.049839048201948566 |
| 45 | 0.0 | 0.000 | YES | 42 | 0.0759323320309165 |
| 46 | 1.0 | 1.000 | YES | 6 | 0.10881804362306165 |
| 47 | 1.0 | 0.000 | NO | 43 | 0.08261985298690291 |
| 48 | 1.0 | 1.000 | YES | 27 | 0.04568943121202384 |
| 49 | 0.0 | 0.000 | YES | 22 | 0.07177826620482357 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
