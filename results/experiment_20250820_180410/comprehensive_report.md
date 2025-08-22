# Comprehensive XAI Benchmarking Report

Generated on: 2025-08-20 18:46:46

## Summary

- **Datasets**: 4
- **Models**: 8
- **Explanation Methods**: 17
- **Evaluation Metrics**: 16
- **Total Combinations**: 96

### Datasets
- **adult_income** (tabular)
- **compas** (tabular)
- **imdb** (text)
- **mnist** (image)

### Models
- **bert** (bert)
- **cnn** (cnn)
- **decision_tree** (decision_tree)
- **gradient_boosting** (gradient_boosting)
- **lstm** (lstm)
- **mlp** (mlp)
- **random_forest** (random_forest)
- **vit** (vit)

### Explanation Methods
- **attention_visualization**
- **bayesian_rule_list**
- **causal_shap**
- **concept_bottleneck**
- **corels**
- **counterfactual**
- **feature_ablation**
- **influence_functions**
- **integrated_gradients**
- **lime**
- **occlusion**
- **prototype**
- **shap**
- **shap_interactive**
- **shapley_flow**
- **tcav**
- **text_occlusion**

## Model Performance Summary

Training and test set performance for each model on each dataset.

| Dataset | Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss | Other Metrics |
|---------|-------|----------------|---------------|------------|-----------|---------------|
| adult_income | decision_tree | 0.8405 | 0.8326 | N/A | N/A | train_f1: 0.8247; test_f1: 0.8159; train_precision: 0.8365; test_precision: 0.8264; train_recall: 0.8405; test_recall: 0.8326; overfitting_gap: 0.0079; overfitting_severity: low; class_accuracies: [0.957845950121386, 0.45472703062583225]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 0.0283; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | random_forest | 0.8425 | 0.8333 | N/A | N/A | train_f1: 0.8267; test_f1: 0.8160; train_precision: 0.8392; test_precision: 0.8278; train_recall: 0.8425; test_recall: 0.8333; overfitting_gap: 0.0092; overfitting_severity: low; class_accuracies: [0.9602736702714633, 0.45006657789613846]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 0.8316; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | gradient_boosting | 0.8387 | 0.8356 | N/A | N/A | train_f1: 0.8229; test_f1: 0.8189; train_precision: 0.8340; test_precision: 0.8305; train_recall: 0.8387; test_recall: 0.8356; overfitting_gap: 0.0031; overfitting_severity: low; class_accuracies: [0.9607150739351137, 0.4580559254327563]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 1.0587; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | mlp | 0.8257 | 0.8236 | N/A | N/A | train_f1: 0.8112; test_f1: 0.8083; train_precision: 0.8161; test_precision: 0.8137; train_recall: 0.8257; test_recall: 0.8236; overfitting_gap: 0.0021; overfitting_severity: low; class_accuracies: [0.9452659457073493, 0.4567243675099867]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 8.2720; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | decision_tree | 0.7375 | 0.6736 | N/A | N/A | train_f1: 0.7347; test_f1: 0.6706; train_precision: 0.7381; test_precision: 0.6721; train_recall: 0.7375; test_recall: 0.6736; overfitting_gap: 0.0639; overfitting_severity: low; class_accuracies: [0.755359394703657, 0.5738461538461539]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.0063; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | random_forest | 0.7538 | 0.6826 | N/A | N/A | train_f1: 0.7516; test_f1: 0.6797; train_precision: 0.7543; test_precision: 0.6813; train_recall: 0.7538; test_recall: 0.6826; overfitting_gap: 0.0712; overfitting_severity: low; class_accuracies: [0.7629255989911727, 0.5846153846153846]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.3357; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | gradient_boosting | 0.7054 | 0.6951 | N/A | N/A | train_f1: 0.7025; test_f1: 0.6924; train_precision: 0.7049; test_precision: 0.6941; train_recall: 0.7054; test_recall: 0.6951; overfitting_gap: 0.0103; overfitting_severity: low; class_accuracies: [0.7730138713745272, 0.6]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.3213; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | mlp | 0.6881 | 0.6854 | N/A | N/A | train_f1: 0.6862; test_f1: 0.6837; train_precision: 0.6868; test_precision: 0.6840; train_recall: 0.6881; test_recall: 0.6854; overfitting_gap: 0.0027; overfitting_severity: low; class_accuracies: [0.7490542244640606, 0.6076923076923076]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 1.8557; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| mnist | cnn | 0.9930 | 0.9850 | N/A | N/A | train_f1: 0.9930; test_f1: 0.9850; train_precision: 0.9931; test_precision: 0.9861; train_recall: 0.9930; test_recall: 0.9850; overfitting_gap: 0.0080; overfitting_severity: low; class_accuracies: [1.0, 1.0, 1.0, 0.9375, 1.0, 1.0, 1.0, 0.9583333333333334, 0.9, 1.0]; n_classes: 10.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 6.2092; model_complexity: {'n_parameters': 688138, 'model_size_bytes': 2752552, 'model_size_mb': 2.6250381469726562, 'complexity_level': 'complex'} |
| mnist | vit | 0.8140 | 0.7250 | N/A | N/A | train_f1: 0.8102; test_f1: 0.7182; train_precision: 0.8185; test_precision: 0.7214; train_recall: 0.8140; test_recall: 0.7250; overfitting_gap: 0.0890; overfitting_severity: low; class_accuracies: [0.9411764705882353, 0.9642857142857143, 0.5, 0.625, 0.8571428571428571, 0.4, 0.5, 0.875, 0.6, 0.7142857142857143]; n_classes: 10.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 8.9200; model_complexity: {'n_parameters': 3231242, 'model_size_bytes': 12924968, 'model_size_mb': 12.326210021972656, 'complexity_level': 'complex'} |
| imdb | bert | 0.9180 | 0.8100 | N/A | N/A | train_f1: 0.9180; test_f1: 0.8099; train_precision: 0.9180; test_precision: 0.8105; train_recall: 0.9180; test_recall: 0.8100; overfitting_gap: 0.1080; overfitting_severity: moderate; class_accuracies: [0.79, 0.83]; n_classes: 2.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 0.6349; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| imdb | lstm | 0.8870 | 0.8150 | N/A | N/A | train_f1: 0.8870; test_f1: 0.8149; train_precision: 0.8870; test_precision: 0.8158; train_recall: 0.8870; test_recall: 0.8150; overfitting_gap: 0.0720; overfitting_severity: low; class_accuracies: [0.84, 0.79]; n_classes: 2.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 0.9098; model_complexity: {'n_parameters': 4, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |

## XAI Evaluation Results Table

Each row represents a unique combination of Dataset, Model, and Explanation Method with their evaluation metrics.

| Dataset | Model | Explanation Method | Detailed Report | Time Complexity | Faithfulness | Monotonicity | Completeness | Stability | Consistency | Sparsity | Simplicity | Advanced Identity | Advanced Separability | Advanced Non Sensitivity | Advanced Compactness | Advanced Correctness | Advanced Entropy | Advanced Gini Coefficient | Advanced Kl Divergence |
|---------|-------|-------------------|-----------------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|
| adult_income | decision_tree | shap | [View Details](#) | 0.0009 | 0.1900 | 0.0200 | 0.0100 | 0.0000 | 0.4651 | 0.0300 | 0.9520 | 0.9432 | 0.1706 | 1.0000 | 0.1775 | 0.6240 | 0.0215 | 0.1420 | 0.1685 |
| adult_income | decision_tree | lime | [View Details](#) | 0.0118 | 0.0800 | 0.0400 | 0.0000 | 0.0000 | 0.5001 | 0.0360 | 0.9376 | 0.8511 | 0.2137 | 1.0000 | 0.2200 | 0.5922 | 0.0340 | 0.1776 | 0.2060 |
| adult_income | decision_tree | causal_shap | [View Details](#) | 0.0164 | 0.2400 | 0.0200 | 0.0200 | 0.0000 | 0.5395 | 0.0360 | 0.9495 | 1.0000 | 0.1774 | 1.0000 | 0.1856 | 0.5810 | 0.0255 | 0.1495 | 0.1745 |
| adult_income | decision_tree | shapley_flow | [View Details](#) | 0.0069 | 0.1000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | shap_interactive | [View Details](#) | 0.0179 | 0.3000 | 0.0333 | 0.0186 | 0.0000 | 0.3819 | 0.0933 | 0.9408 | 0.8967 | 0.2790 | 1.0000 | 0.2800 | 0.6349 | 0.0861 | 0.2276 | 0.2472 |
| adult_income | decision_tree | prototype | [View Details](#) | 0.0007 | 0.7400 | 0.8209 | 1.0000 | 0.9024 | 0.9436 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | counterfactual | [View Details](#) | 0.0007 | 0.7000 | 0.1725 | 1.0000 | 0.7652 | 0.7043 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | bayesian_rule_list | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5670 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5670 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | feature_ablation | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4632 | 0.0240 | 0.9440 | 1.0000 | 0.2245 | 1.0000 | 0.2300 | 0.6040 | 0.0172 | 0.1840 | 0.2228 |
| adult_income | random_forest | shap | [View Details](#) | 0.0324 | 0.1900 | 0.0200 | 0.0000 | 0.0000 | 0.4696 | 0.0140 | 0.9440 | 0.9438 | 0.1647 | 1.0000 | 0.1675 | 0.6170 | 0.0291 | 0.1340 | 0.1609 |
| adult_income | random_forest | lime | [View Details](#) | 0.0224 | 0.1000 | 0.0200 | 0.0000 | 0.0000 | 0.4199 | 0.0360 | 0.9598 | 0.9302 | 0.1420 | 1.0000 | 0.1489 | 0.5711 | 0.0256 | 0.1198 | 0.1344 |
| adult_income | random_forest | causal_shap | [View Details](#) | 0.9478 | 0.2400 | 0.0200 | 0.0000 | 0.0000 | 0.4951 | 0.0360 | 0.9472 | 1.0000 | 0.1745 | 1.0000 | 0.1825 | 0.5800 | 0.0295 | 0.1472 | 0.1705 |
| adult_income | random_forest | shapley_flow | [View Details](#) | 0.5001 | 0.1333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | shap_interactive | [View Details](#) | 1.1197 | 0.2667 | 0.0333 | 0.0359 | 0.0000 | 0.4441 | 0.1000 | 0.9340 | 0.9200 | 0.2649 | 1.0000 | 0.2604 | 0.6240 | 0.1071 | 0.2157 | 0.2263 |
| adult_income | random_forest | prototype | [View Details](#) | 0.0059 | 0.7400 | 0.8033 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | counterfactual | [View Details](#) | 0.0058 | 0.7600 | 0.1943 | 1.0000 | 0.9246 | 0.3645 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | bayesian_rule_list | [View Details](#) | 0.0055 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | corels | [View Details](#) | 0.0044 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | feature_ablation | [View Details](#) | 0.0272 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4509 | 0.0120 | 0.9320 | 1.0000 | 0.2132 | 1.0000 | 0.2150 | 0.6040 | 0.0309 | 0.1720 | 0.2091 |
| adult_income | gradient_boosting | shap | [View Details](#) | 0.0022 | 0.2100 | 0.0300 | 0.0000 | 0.0000 | 0.4896 | 0.0220 | 0.9400 | 0.9432 | 0.1825 | 1.0000 | 0.1875 | 0.6440 | 0.0316 | 0.1500 | 0.1784 |
| adult_income | gradient_boosting | lime | [View Details](#) | 0.0152 | 0.1200 | 0.0400 | 0.0000 | 0.0000 | 0.4527 | 0.0240 | 0.9642 | 0.9302 | 0.1526 | 1.0000 | 0.1555 | 0.6043 | 0.0117 | 0.1242 | 0.1483 |
| adult_income | gradient_boosting | causal_shap | [View Details](#) | 0.0525 | 0.2600 | 0.0200 | 0.0000 | 0.0000 | 0.5578 | 0.0320 | 0.9569 | 1.0000 | 0.1819 | 1.0000 | 0.1878 | 0.6134 | 0.0314 | 0.1487 | 0.1686 |
| adult_income | gradient_boosting | shap_interactive | [View Details](#) | 0.0642 | 0.3333 | 0.0333 | 0.0047 | 0.0000 | 0.4397 | 0.0867 | 0.9339 | 0.9649 | 0.2734 | 1.0000 | 0.2769 | 0.6495 | 0.1033 | 0.2229 | 0.2300 |
| adult_income | gradient_boosting | prototype | [View Details](#) | 0.0020 | 0.7100 | 0.8037 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | counterfactual | [View Details](#) | 0.0009 | 0.7350 | 0.1819 | 1.0000 | 0.9699 | 0.6397 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0010 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5810 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | corels | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5810 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | feature_ablation | [View Details](#) | 0.0013 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4954 | 0.0200 | 0.9360 | 1.0000 | 0.2404 | 1.0000 | 0.2450 | 0.6380 | 0.0223 | 0.1960 | 0.2377 |
| adult_income | mlp | shap | [View Details](#) | 0.0012 | 0.2200 | 0.0250 | 0.0000 | 0.0000 | 0.4396 | 0.0260 | 0.9420 | 0.9032 | 0.1970 | 1.0000 | 0.2025 | 0.6400 | 0.0258 | 0.1620 | 0.1942 |
| adult_income | mlp | lime | [View Details](#) | 0.0140 | 0.0600 | 0.0233 | 0.0000 | 0.0000 | 0.6811 | 0.0840 | 0.9581 | 0.8723 | 0.1082 | 1.0000 | 0.1220 | 0.5715 | 0.0481 | 0.0981 | 0.0919 |
| adult_income | mlp | integrated_gradients | [View Details](#) | 0.0619 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5833 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | causal_shap | [View Details](#) | 0.0303 | 0.2400 | 0.0080 | 0.0000 | 0.0000 | 0.5950 | 0.0320 | 0.9683 | 1.0000 | 0.1605 | 1.0000 | 0.1629 | 0.5963 | 0.0359 | 0.1281 | 0.1441 |
| adult_income | mlp | shapley_flow | [View Details](#) | 0.0114 | 0.1000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5833 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | shap_interactive | [View Details](#) | 0.0319 | 0.3000 | 0.0150 | 0.0252 | 0.0000 | 0.4129 | 0.1200 | 0.9562 | 0.8743 | 0.2926 | 1.0000 | 0.2852 | 0.6485 | 0.1408 | 0.2324 | 0.2259 |
| adult_income | mlp | prototype | [View Details](#) | 0.0011 | 0.7350 | 0.8014 | 1.0000 | 0.9966 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | counterfactual | [View Details](#) | 0.0009 | 0.6800 | 0.2005 | 1.0000 | 0.9193 | 0.9471 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | influence_functions | [View Details](#) | 0.0274 | 0.0000 | 0.0000 | 0.0000 | 0.2615 | 0.4384 | 0.6000 | 0.4358 | 1.0000 | 0.4254 | 1.0000 | 0.5102 | 0.7454 | 0.7768 | 0.4358 | 0.2232 |
| adult_income | mlp | bayesian_rule_list | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5740 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | corels | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5740 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | feature_ablation | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4377 | 0.0240 | 0.9320 | 1.0000 | 0.2845 | 1.0000 | 0.2900 | 0.6360 | 0.0172 | 0.2320 | 0.2828 |
| compas | decision_tree | shap | [View Details](#) | 0.0007 | 0.6500 | 0.0300 | 0.0000 | 0.0000 | 0.6861 | 0.3500 | 0.7000 | 0.6292 | 0.3712 | 1.0000 | 0.5250 | 0.6090 | 0.1525 | 0.3500 | 0.4975 |
| compas | decision_tree | lime | [View Details](#) | 0.0123 | 0.3200 | 0.0800 | 0.0000 | 0.0000 | 0.7619 | 0.6133 | 0.6854 | 0.5102 | 0.6393 | 1.0000 | 0.9062 | 0.5900 | 0.0263 | 0.6054 | 0.8937 |
| compas | decision_tree | causal_shap | [View Details](#) | 0.0123 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.6457 | 0.3333 | 0.7593 | 0.9615 | 0.2387 | 1.0000 | 0.3202 | 0.4034 | 0.2437 | 0.2245 | 0.2563 |
| compas | decision_tree | shapley_flow | [View Details](#) | 0.0059 | 0.3333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3733 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | shap_interactive | [View Details](#) | 0.0133 | 0.6667 | 0.0222 | 0.0876 | 0.0000 | 0.6321 | 0.5667 | 0.6951 | 0.6557 | 0.4374 | 1.0000 | 0.4657 | 0.5065 | 0.5070 | 0.3363 | 0.3597 |
| compas | decision_tree | prototype | [View Details](#) | 0.0003 | 0.6700 | 0.7461 | 1.0000 | 0.8631 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | counterfactual | [View Details](#) | 0.0003 | 0.6150 | 0.2828 | 1.0000 | 0.9922 | 0.3214 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | bayesian_rule_list | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 1.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | feature_ablation | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6747 | 0.3667 | 0.6667 | 1.0000 | 0.3889 | 1.0000 | 0.5500 | 0.5260 | 0.1840 | 0.3667 | 0.5160 |
| compas | random_forest | shap | [View Details](#) | 0.0272 | 0.6300 | 0.0383 | 0.0000 | 0.0000 | 0.7164 | 0.3233 | 0.6933 | 0.6548 | 0.3429 | 1.0000 | 0.4850 | 0.6240 | 0.1777 | 0.3233 | 0.4523 |
| compas | random_forest | lime | [View Details](#) | 0.0271 | 0.3800 | 0.0667 | 0.0000 | 0.0000 | 0.7234 | 0.5067 | 0.6845 | 0.5897 | 0.4540 | 1.0000 | 0.6510 | 0.5493 | 0.1797 | 0.4445 | 0.5803 |
| compas | random_forest | causal_shap | [View Details](#) | 0.5518 | 0.4800 | 0.0300 | 0.0000 | 0.0000 | 0.6790 | 0.3200 | 0.7454 | 1.0000 | 0.2158 | 1.0000 | 0.2872 | 0.4501 | 0.2791 | 0.2059 | 0.2209 |
| compas | random_forest | shapley_flow | [View Details](#) | 0.2876 | 0.4333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3733 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | shap_interactive | [View Details](#) | 0.6383 | 0.6667 | 0.0556 | 0.0323 | 0.0000 | 0.6130 | 0.4667 | 0.6417 | 0.7947 | 0.3260 | 0.9999 | 0.3583 | 0.4584 | 0.5098 | 0.2641 | 0.2569 |
| compas | random_forest | prototype | [View Details](#) | 0.0048 | 0.6650 | 0.6974 | 1.0000 | 0.9834 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | counterfactual | [View Details](#) | 0.0049 | 0.6900 | 0.2980 | 1.0000 | 0.7833 | 0.5296 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | bayesian_rule_list | [View Details](#) | 0.0052 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4410 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | corels | [View Details](#) | 0.0045 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4410 | 1.0000 | 0.0000 | 0.0000 |
| compas | random_forest | feature_ablation | [View Details](#) | 0.0163 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.7118 | 0.2933 | 0.6333 | 1.0000 | 0.3111 | 1.0000 | 0.4400 | 0.5640 | 0.2671 | 0.2933 | 0.3929 |
| compas | gradient_boosting | shap | [View Details](#) | 0.0015 | 0.6100 | 0.0250 | 0.0000 | 0.0000 | 0.7096 | 0.3233 | 0.7133 | 0.6705 | 0.3429 | 0.9999 | 0.4850 | 0.6490 | 0.1551 | 0.3233 | 0.4549 |
| compas | gradient_boosting | lime | [View Details](#) | 0.0134 | 0.4000 | 0.1400 | 0.0000 | 0.3274 | 0.9141 | 0.5333 | 0.7232 | 0.5814 | 0.5514 | 1.0000 | 0.7843 | 0.6349 | 0.0420 | 0.5232 | 0.7580 |
| compas | gradient_boosting | causal_shap | [View Details](#) | 0.0308 | 0.4400 | 0.0300 | 0.0000 | 0.0000 | 0.6357 | 0.3067 | 0.6830 | 1.0000 | 0.1806 | 1.0000 | 0.2501 | 0.4544 | 0.3187 | 0.1830 | 0.1813 |
| compas | gradient_boosting | shap_interactive | [View Details](#) | 0.0345 | 0.6333 | 0.0611 | 0.0056 | 0.0000 | 0.6198 | 0.4889 | 0.6417 | 0.7625 | 0.3439 | 0.9999 | 0.4174 | 0.4802 | 0.4592 | 0.2986 | 0.3075 |
| compas | gradient_boosting | prototype | [View Details](#) | 0.0005 | 0.6950 | 0.6997 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | counterfactual | [View Details](#) | 0.0007 | 0.6500 | 0.3089 | 1.0000 | 0.9566 | 0.6421 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0014 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | corels | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 1.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | feature_ablation | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6815 | 0.3333 | 0.6933 | 1.0000 | 0.3536 | 0.9998 | 0.5000 | 0.5980 | 0.1767 | 0.3333 | 0.4633 |
| compas | mlp | shap | [View Details](#) | 0.0008 | 0.5800 | 0.0100 | 0.0000 | 0.0000 | 0.7432 | 0.3800 | 0.8000 | 0.6556 | 0.4031 | 1.0000 | 0.5700 | 0.6430 | 0.0126 | 0.3800 | 0.5674 |
| compas | mlp | lime | [View Details](#) | 0.0120 | 0.0400 | 0.0000 | 0.0000 | 0.0000 | 0.8377 | 0.3467 | 0.8019 | 0.6136 | 0.3354 | 1.0000 | 0.4774 | 0.5409 | 0.0701 | 0.3219 | 0.4499 |
| compas | mlp | integrated_gradients | [View Details](#) | 0.0331 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | causal_shap | [View Details](#) | 0.0166 | 0.3400 | 0.0000 | 0.0000 | 0.0000 | 0.5817 | 0.2933 | 0.8068 | 1.0000 | 0.2574 | 1.0000 | 0.3443 | 0.5074 | 0.1476 | 0.2353 | 0.3124 |
| compas | mlp | shapley_flow | [View Details](#) | 0.0071 | 0.2333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | shap_interactive | [View Details](#) | 0.0185 | 0.5000 | 0.0111 | 0.0694 | 0.0000 | 0.6732 | 0.5222 | 0.8019 | 0.6299 | 0.4594 | 1.0000 | 0.5136 | 0.5915 | 0.3744 | 0.3590 | 0.4256 |
| compas | mlp | prototype | [View Details](#) | 0.0004 | 0.6750 | 0.6829 | 1.0000 | 0.9431 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | counterfactual | [View Details](#) | 0.0005 | 0.6300 | 0.3208 | 1.0000 | 0.8206 | 0.3549 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | influence_functions | [View Details](#) | 0.0286 | 0.0000 | 0.0000 | 0.0000 | 0.3834 | 0.7184 | 0.6667 | 0.4325 | 1.0000 | 0.4194 | 1.0000 | 0.6078 | 0.6356 | 0.6415 | 0.4325 | 0.3585 |
| compas | mlp | bayesian_rule_list | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | corels | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 1.0000 | 0.0000 | 0.0000 |
| compas | mlp | feature_ablation | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.7167 | 0.3800 | 0.8000 | 1.0000 | 0.4031 | 1.0000 | 0.5700 | 0.5800 | 0.0126 | 0.3800 | 0.5674 |
| mnist | cnn | prototype | [View Details](#) | 0.0012 | 0.9850 | 0.6645614 | 1.0000 | 0.9581 | 0.9035 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | cnn | counterfactual | [View Details](#) | 0.0032 | 0.9850 | 0.4726406 | 1.0000 | 0.5869 | 0.1557 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | cnn | tcav | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | cnn | concept_bottleneck | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | cnn | occlusion | [View Details](#) | 0.0189 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | vit | tcav | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | vit | concept_bottleneck | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | vit | occlusion | [View Details](#) | 0.0863 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| imdb | bert | lime | [View Details](#) | 0.0899 | 0.8400 | 0.0000 | 0.0000 | 0.0684 | 0.1297 | 0.7400 | 0.4524 | 1.0000 | 0.4744 | 0.0000 | 0.4622 | 0.5944 | 0.9027 | 0.4524 | 0.0973 |
| imdb | bert | text_occlusion | [View Details](#) | 0.0481 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0552 | 0.0046 | 0.8016 | 1.0000 | 0.0890 | 0.0000 | 0.0824 | 0.6360 | 0.2137 | 0.0816 | 0.0663 |
| imdb | bert | attention_visualization | [View Details](#) | 0.1206 | 0.0000 | 0.0000 | 0.0000 | 0.7141 | 0.0947 | 0.7005 | 0.0381 | 1.0000 | 0.0360 | 0.0000 | 0.0055 | 0.5880 | 0.9994 | 0.0381 | 0.0006 |
| imdb | lstm | lime | [View Details](#) | 0.0920 | 0.8000 | 0.0000 | 0.0000 | 0.0000 | 0.1232 | 0.7400 | 0.4773 | 1.0000 | 0.5282 | 0.0000 | 0.5089 | 0.5678 | 0.8893 | 0.4773 | 0.1107 |
| imdb | lstm | text_occlusion | [View Details](#) | 0.0507 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0627 | 0.0062 | 0.7822 | 1.0000 | 0.1734 | 0.0000 | 0.1638 | 0.6500 | 0.2449 | 0.1622 | 0.1351 |
| imdb | lstm | attention_visualization | [View Details](#) | 0.1338 | 0.0000 | 0.0000 | 0.0000 | 0.7135 | 0.0924 | 0.6971 | 0.0385 | 1.0000 | 0.0371 | 0.0000 | 0.0059 | 0.5600 | 0.9994 | 0.0385 | 0.0006 |

## Detailed Explanation Analysis

Summary of detailed explanations generated for the entire test set.

| Dataset | Model | Method | Test Instances | Valid Explanations | Accuracy | Avg Feature Importance | Detailed Files |
|---------|-------|--------|----------------|-------------------|----------|----------------------|----------------|
| adult_income | decision_tree | shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\shap_detailed_explanations.json) |
| adult_income | decision_tree | lime | 6033 | 6033 | 0.833 | 0.0361 | [JSON](detailed_explanations\adult_income\decision_tree\lime_detailed_explanations.json) |
| adult_income | decision_tree | causal_shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\causal_shap_detailed_explanations.json) |
| adult_income | decision_tree | shapley_flow | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\shapley_flow_detailed_explanations.json) |
| adult_income | decision_tree | shap_interactive | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\shap_interactive_detailed_explanations.json) |
| adult_income | decision_tree | prototype | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\prototype_detailed_explanations.json) |
| adult_income | decision_tree | counterfactual | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\counterfactual_detailed_explanations.json) |
| adult_income | decision_tree | bayesian_rule_list | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| adult_income | decision_tree | corels | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\corels_detailed_explanations.json) |
| adult_income | decision_tree | feature_ablation | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\feature_ablation_detailed_explanations.json) |
| adult_income | random_forest | shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\shap_detailed_explanations.json) |
| adult_income | random_forest | lime | 6033 | 6033 | 0.833 | 0.0306 | [JSON](detailed_explanations\adult_income\random_forest\lime_detailed_explanations.json) |
| adult_income | random_forest | causal_shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\causal_shap_detailed_explanations.json) |
| adult_income | random_forest | shapley_flow | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\shapley_flow_detailed_explanations.json) |
| adult_income | random_forest | shap_interactive | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\shap_interactive_detailed_explanations.json) |
| adult_income | random_forest | prototype | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\prototype_detailed_explanations.json) |
| adult_income | random_forest | counterfactual | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\counterfactual_detailed_explanations.json) |
| adult_income | random_forest | bayesian_rule_list | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\bayesian_rule_list_detailed_explanations.json) |
| adult_income | random_forest | corels | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\corels_detailed_explanations.json) |
| adult_income | random_forest | feature_ablation | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\feature_ablation_detailed_explanations.json) |
| adult_income | gradient_boosting | shap | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\shap_detailed_explanations.json) |
| adult_income | gradient_boosting | lime | 6033 | 6033 | 0.836 | 0.0270 | [JSON](detailed_explanations\adult_income\gradient_boosting\lime_detailed_explanations.json) |
| adult_income | gradient_boosting | causal_shap | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\causal_shap_detailed_explanations.json) |
| adult_income | gradient_boosting | shap_interactive | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\shap_interactive_detailed_explanations.json) |
| adult_income | gradient_boosting | prototype | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\prototype_detailed_explanations.json) |
| adult_income | gradient_boosting | counterfactual | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\counterfactual_detailed_explanations.json) |
| adult_income | gradient_boosting | bayesian_rule_list | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| adult_income | gradient_boosting | corels | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\corels_detailed_explanations.json) |
| adult_income | gradient_boosting | feature_ablation | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\feature_ablation_detailed_explanations.json) |
| adult_income | mlp | shap | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\shap_detailed_explanations.json) |
| adult_income | mlp | lime | 6033 | 6033 | 0.824 | 0.0211 | [JSON](detailed_explanations\adult_income\mlp\lime_detailed_explanations.json) |
| adult_income | mlp | integrated_gradients | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\integrated_gradients_detailed_explanations.json) |
| adult_income | mlp | causal_shap | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\causal_shap_detailed_explanations.json) |
| adult_income | mlp | shapley_flow | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\shapley_flow_detailed_explanations.json) |
| adult_income | mlp | shap_interactive | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\shap_interactive_detailed_explanations.json) |
| adult_income | mlp | prototype | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\prototype_detailed_explanations.json) |
| adult_income | mlp | counterfactual | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\counterfactual_detailed_explanations.json) |
| adult_income | mlp | influence_functions | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\influence_functions_detailed_explanations.json) |
| adult_income | mlp | bayesian_rule_list | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\bayesian_rule_list_detailed_explanations.json) |
| adult_income | mlp | corels | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\corels_detailed_explanations.json) |
| adult_income | mlp | feature_ablation | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\feature_ablation_detailed_explanations.json) |
| compas | decision_tree | shap | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\shap_detailed_explanations.json) |
| compas | decision_tree | lime | 1443 | 1443 | 0.674 | 0.2675 | [JSON](detailed_explanations\compas\decision_tree\lime_detailed_explanations.json) |
| compas | decision_tree | causal_shap | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\causal_shap_detailed_explanations.json) |
| compas | decision_tree | shapley_flow | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\shapley_flow_detailed_explanations.json) |
| compas | decision_tree | shap_interactive | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\shap_interactive_detailed_explanations.json) |
| compas | decision_tree | prototype | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\prototype_detailed_explanations.json) |
| compas | decision_tree | counterfactual | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\counterfactual_detailed_explanations.json) |
| compas | decision_tree | bayesian_rule_list | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| compas | decision_tree | corels | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\corels_detailed_explanations.json) |
| compas | decision_tree | feature_ablation | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\feature_ablation_detailed_explanations.json) |
| compas | random_forest | shap | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\shap_detailed_explanations.json) |
| compas | random_forest | lime | 1443 | 1443 | 0.683 | 0.0705 | [JSON](detailed_explanations\compas\random_forest\lime_detailed_explanations.json) |
| compas | random_forest | causal_shap | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\causal_shap_detailed_explanations.json) |
| compas | random_forest | shapley_flow | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\shapley_flow_detailed_explanations.json) |
| compas | random_forest | shap_interactive | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\shap_interactive_detailed_explanations.json) |
| compas | random_forest | prototype | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\prototype_detailed_explanations.json) |
| compas | random_forest | counterfactual | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\counterfactual_detailed_explanations.json) |
| compas | random_forest | bayesian_rule_list | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\bayesian_rule_list_detailed_explanations.json) |
| compas | random_forest | corels | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\corels_detailed_explanations.json) |
| compas | random_forest | feature_ablation | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\feature_ablation_detailed_explanations.json) |
| compas | gradient_boosting | shap | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\shap_detailed_explanations.json) |
| compas | gradient_boosting | lime | 1443 | 1443 | 0.695 | 0.2229 | [JSON](detailed_explanations\compas\gradient_boosting\lime_detailed_explanations.json) |
| compas | gradient_boosting | causal_shap | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\causal_shap_detailed_explanations.json) |
| compas | gradient_boosting | shap_interactive | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\shap_interactive_detailed_explanations.json) |
| compas | gradient_boosting | prototype | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\prototype_detailed_explanations.json) |
| compas | gradient_boosting | counterfactual | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\counterfactual_detailed_explanations.json) |
| compas | gradient_boosting | bayesian_rule_list | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| compas | gradient_boosting | corels | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\corels_detailed_explanations.json) |
| compas | gradient_boosting | feature_ablation | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\feature_ablation_detailed_explanations.json) |
| compas | mlp | shap | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\shap_detailed_explanations.json) |
| compas | mlp | lime | 1443 | 1443 | 0.685 | 0.1060 | [JSON](detailed_explanations\compas\mlp\lime_detailed_explanations.json) |
| compas | mlp | integrated_gradients | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\integrated_gradients_detailed_explanations.json) |
| compas | mlp | causal_shap | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\causal_shap_detailed_explanations.json) |
| compas | mlp | shapley_flow | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\shapley_flow_detailed_explanations.json) |
| compas | mlp | shap_interactive | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\shap_interactive_detailed_explanations.json) |
| compas | mlp | prototype | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\prototype_detailed_explanations.json) |
| compas | mlp | counterfactual | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\counterfactual_detailed_explanations.json) |
| compas | mlp | influence_functions | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\influence_functions_detailed_explanations.json) |
| compas | mlp | bayesian_rule_list | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\bayesian_rule_list_detailed_explanations.json) |
| compas | mlp | corels | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\corels_detailed_explanations.json) |
| compas | mlp | feature_ablation | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\feature_ablation_detailed_explanations.json) |
| mnist | cnn | prototype | 200 | 200 | 0.985 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\prototype_detailed_explanations.json) |
| mnist | cnn | counterfactual | 200 | 200 | 0.985 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\counterfactual_detailed_explanations.json) |
| mnist | cnn | tcav | 200 | 200 | 0.985 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\tcav_detailed_explanations.json) |
| mnist | cnn | concept_bottleneck | 200 | 200 | 0.985 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\concept_bottleneck_detailed_explanations.json) |
| mnist | cnn | occlusion | 200 | 200 | 0.985 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\occlusion_detailed_explanations.json) |
| mnist | vit | tcav | 200 | 200 | 0.725 | 0.0000 | [JSON](detailed_explanations\mnist\vit\tcav_detailed_explanations.json) |
| mnist | vit | concept_bottleneck | 200 | 200 | 0.725 | 0.0000 | [JSON](detailed_explanations\mnist\vit\concept_bottleneck_detailed_explanations.json) |
| mnist | vit | occlusion | 200 | 200 | 0.725 | 0.0000 | [JSON](detailed_explanations\mnist\vit\occlusion_detailed_explanations.json) |
| imdb | bert | lime | 200 | 200 | 0.810 | 0.0200 | [JSON](detailed_explanations\imdb\bert\lime_detailed_explanations.json) |
| imdb | bert | text_occlusion | 200 | 200 | 0.810 | 0.0000 | [JSON](detailed_explanations\imdb\bert\text_occlusion_detailed_explanations.json) |
| imdb | bert | attention_visualization | 200 | 200 | 0.810 | 0.0104 | [JSON](detailed_explanations\imdb\bert\attention_visualization_detailed_explanations.json) |
| imdb | lstm | lime | 200 | 200 | 0.815 | 0.0200 | [JSON](detailed_explanations\imdb\lstm\lime_detailed_explanations.json) |
| imdb | lstm | text_occlusion | 200 | 200 | 0.815 | 0.0000 | [JSON](detailed_explanations\imdb\lstm\text_occlusion_detailed_explanations.json) |
| imdb | lstm | attention_visualization | 200 | 200 | 0.815 | 0.0104 | [JSON](detailed_explanations\imdb\lstm\attention_visualization_detailed_explanations.json) |

## Model Performance Analysis by Dataset

### adult_income

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 0.8405 | 0.8326 | N/A | N/A |
| random_forest | 0.8425 | 0.8333 | N/A | N/A |
| gradient_boosting | 0.8387 | 0.8356 | N/A | N/A |
| mlp | 0.8257 | 0.8236 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0009 | 0.1900 | 0.0200 |
| decision_tree | lime | 0.0118 | 0.0800 | 0.0400 |
| decision_tree | causal_shap | 0.0164 | 0.2400 | 0.0200 |
| decision_tree | shapley_flow | 0.0069 | 0.1000 | 0.0000 |
| decision_tree | shap_interactive | 0.0179 | 0.3000 | 0.0333 |
| decision_tree | prototype | 0.0007 | 0.7400 | 0.8209 |
| decision_tree | counterfactual | 0.0007 | 0.7000 | 0.1725 |
| decision_tree | bayesian_rule_list | 0.0009 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0003 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0007 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0324 | 0.1900 | 0.0200 |
| random_forest | lime | 0.0224 | 0.1000 | 0.0200 |
| random_forest | causal_shap | 0.9478 | 0.2400 | 0.0200 |
| random_forest | shapley_flow | 0.5001 | 0.1333 | 0.0000 |
| random_forest | shap_interactive | 1.1197 | 0.2667 | 0.0333 |
| random_forest | prototype | 0.0059 | 0.7400 | 0.8033 |
| random_forest | counterfactual | 0.0058 | 0.7600 | 0.1943 |
| random_forest | bayesian_rule_list | 0.0055 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0044 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0272 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0022 | 0.2100 | 0.0300 |
| gradient_boosting | lime | 0.0152 | 0.1200 | 0.0400 |
| gradient_boosting | causal_shap | 0.0525 | 0.2600 | 0.0200 |
| gradient_boosting | shap_interactive | 0.0642 | 0.3333 | 0.0333 |
| gradient_boosting | prototype | 0.0020 | 0.7100 | 0.8037 |
| gradient_boosting | counterfactual | 0.0009 | 0.7350 | 0.1819 |
| gradient_boosting | bayesian_rule_list | 0.0010 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0006 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0013 | 0.0000 | 0.0000 |
| mlp | shap | 0.0012 | 0.2200 | 0.0250 |
| mlp | lime | 0.0140 | 0.0600 | 0.0233 |
| mlp | integrated_gradients | 0.0619 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0303 | 0.2400 | 0.0080 |
| mlp | shapley_flow | 0.0114 | 0.1000 | 0.0000 |
| mlp | shap_interactive | 0.0319 | 0.3000 | 0.0150 |
| mlp | prototype | 0.0011 | 0.7350 | 0.8014 |
| mlp | counterfactual | 0.0009 | 0.6800 | 0.2005 |
| mlp | influence_functions | 0.0274 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0007 | 0.0000 | 0.0000 |
| mlp | corels | 0.0005 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0008 | 0.0000 | 0.0000 |

### compas

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 0.7375 | 0.6736 | N/A | N/A |
| random_forest | 0.7538 | 0.6826 | N/A | N/A |
| gradient_boosting | 0.7054 | 0.6951 | N/A | N/A |
| mlp | 0.6881 | 0.6854 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0007 | 0.6500 | 0.0300 |
| decision_tree | lime | 0.0123 | 0.3200 | 0.0800 |
| decision_tree | causal_shap | 0.0123 | 0.5000 | 0.0000 |
| decision_tree | shapley_flow | 0.0059 | 0.3333 | 0.0000 |
| decision_tree | shap_interactive | 0.0133 | 0.6667 | 0.0222 |
| decision_tree | prototype | 0.0003 | 0.6700 | 0.7461 |
| decision_tree | counterfactual | 0.0003 | 0.6150 | 0.2828 |
| decision_tree | bayesian_rule_list | 0.0009 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0003 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0003 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0272 | 0.6300 | 0.0383 |
| random_forest | lime | 0.0271 | 0.3800 | 0.0667 |
| random_forest | causal_shap | 0.5518 | 0.4800 | 0.0300 |
| random_forest | shapley_flow | 0.2876 | 0.4333 | 0.0000 |
| random_forest | shap_interactive | 0.6383 | 0.6667 | 0.0556 |
| random_forest | prototype | 0.0048 | 0.6650 | 0.6974 |
| random_forest | counterfactual | 0.0049 | 0.6900 | 0.2980 |
| random_forest | bayesian_rule_list | 0.0052 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0045 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0163 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0015 | 0.6100 | 0.0250 |
| gradient_boosting | lime | 0.0134 | 0.4000 | 0.1400 |
| gradient_boosting | causal_shap | 0.0308 | 0.4400 | 0.0300 |
| gradient_boosting | shap_interactive | 0.0345 | 0.6333 | 0.0611 |
| gradient_boosting | prototype | 0.0005 | 0.6950 | 0.6997 |
| gradient_boosting | counterfactual | 0.0007 | 0.6500 | 0.3089 |
| gradient_boosting | bayesian_rule_list | 0.0014 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0005 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0009 | 0.0000 | 0.0000 |
| mlp | shap | 0.0008 | 0.5800 | 0.0100 |
| mlp | lime | 0.0120 | 0.0400 | 0.0000 |
| mlp | integrated_gradients | 0.0331 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0166 | 0.3400 | 0.0000 |
| mlp | shapley_flow | 0.0071 | 0.2333 | 0.0000 |
| mlp | shap_interactive | 0.0185 | 0.5000 | 0.0111 |
| mlp | prototype | 0.0004 | 0.6750 | 0.6829 |
| mlp | counterfactual | 0.0005 | 0.6300 | 0.3208 |
| mlp | influence_functions | 0.0286 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0004 | 0.0000 | 0.0000 |
| mlp | corels | 0.0004 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0008 | 0.0000 | 0.0000 |

### imdb

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| bert | 0.9180 | 0.8100 | N/A | N/A |
| lstm | 0.8870 | 0.8150 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| bert | lime | 0.0899 | 0.8400 | 0.0000 |
| bert | text_occlusion | 0.0481 | 0.0000 | 0.0000 |
| bert | attention_visualization | 0.1206 | 0.0000 | 0.0000 |
| lstm | lime | 0.0920 | 0.8000 | 0.0000 |
| lstm | text_occlusion | 0.0507 | 0.0000 | 0.0000 |
| lstm | attention_visualization | 0.1338 | 0.0000 | 0.0000 |

### mnist

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| cnn | 0.9930 | 0.9850 | N/A | N/A |
| vit | 0.8140 | 0.7250 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| cnn | prototype | 0.0012 | 0.9850 | 0.6645614 |
| cnn | counterfactual | 0.0032 | 0.9850 | 0.4726406 |
| cnn | tcav | 0.0000 | 0.0000 | 0.0000 |
| cnn | concept_bottleneck | 0.0000 | 0.0000 | 0.0000 |
| cnn | occlusion | 0.0189 | 0.0000 | 0.0000 |
| vit | tcav | 0.0000 | 0.0000 | 0.0000 |
| vit | concept_bottleneck | 0.0000 | 0.0000 | 0.0000 |
| vit | occlusion | 0.0863 | 0.0000 | 0.0000 |

## Best Performing Models by Dataset

Ranking models by test accuracy on each dataset.

### adult_income - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | gradient_boosting | 0.8356 |
| 2 | random_forest | 0.8333 |
| 3 | decision_tree | 0.8326 |
| 4 | mlp | 0.8236 |

### compas - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | gradient_boosting | 0.6951 |
| 2 | mlp | 0.6854 |
| 3 | random_forest | 0.6826 |
| 4 | decision_tree | 0.6736 |

### imdb - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | lstm | 0.8150 |
| 2 | bert | 0.8100 |

### mnist - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | cnn | 0.9850 |
| 2 | vit | 0.7250 |

## Top Performing XAI Combinations

### Best Time Complexity

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | adult_income | random_forest | shap_interactive | 1.1197 |
| 2 | adult_income | random_forest | causal_shap | 0.9478 |
| 3 | compas | random_forest | shap_interactive | 0.6383 |
| 4 | compas | random_forest | causal_shap | 0.5518 |
| 5 | adult_income | random_forest | shapley_flow | 0.5001 |
| 6 | compas | random_forest | shapley_flow | 0.2876 |
| 7 | imdb | lstm | attention_visualization | 0.1338 |
| 8 | imdb | bert | attention_visualization | 0.1206 |
| 9 | imdb | lstm | lime | 0.0920 |
| 10 | imdb | bert | lime | 0.0899 |

### Best Faithfulness

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | mnist | cnn | prototype | 0.9850 |
| 2 | mnist | cnn | counterfactual | 0.9850 |
| 3 | imdb | bert | lime | 0.8400 |
| 4 | imdb | lstm | lime | 0.8000 |
| 5 | adult_income | random_forest | counterfactual | 0.7600 |
| 6 | adult_income | decision_tree | prototype | 0.7400 |
| 7 | adult_income | random_forest | prototype | 0.7400 |
| 8 | adult_income | gradient_boosting | counterfactual | 0.7350 |
| 9 | adult_income | mlp | prototype | 0.7350 |
| 10 | adult_income | gradient_boosting | prototype | 0.7100 |

### Best Monotonicity

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | adult_income | decision_tree | prototype | 0.8209 |
| 2 | adult_income | gradient_boosting | prototype | 0.8037 |
| 3 | adult_income | random_forest | prototype | 0.8033 |
| 4 | adult_income | mlp | prototype | 0.8014 |
| 5 | compas | decision_tree | prototype | 0.7461 |
| 6 | compas | gradient_boosting | prototype | 0.6997 |
| 7 | compas | random_forest | prototype | 0.6974 |
| 8 | compas | mlp | prototype | 0.6829 |
| 9 | compas | mlp | counterfactual | 0.3208 |
| 10 | compas | gradient_boosting | counterfactual | 0.3089 |

### Best Completeness

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | adult_income | decision_tree | prototype | 1.0000 |
| 2 | adult_income | decision_tree | counterfactual | 1.0000 |
| 3 | adult_income | random_forest | prototype | 1.0000 |
| 4 | adult_income | random_forest | counterfactual | 1.0000 |
| 5 | adult_income | gradient_boosting | prototype | 1.0000 |
| 6 | adult_income | gradient_boosting | counterfactual | 1.0000 |
| 7 | adult_income | mlp | prototype | 1.0000 |
| 8 | adult_income | mlp | counterfactual | 1.0000 |
| 9 | compas | decision_tree | prototype | 1.0000 |
| 10 | compas | decision_tree | counterfactual | 1.0000 |

### Best Stability

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | adult_income | decision_tree | shapley_flow | 1.0000 |
| 2 | adult_income | decision_tree | bayesian_rule_list | 1.0000 |
| 3 | adult_income | random_forest | shapley_flow | 1.0000 |
| 4 | adult_income | random_forest | bayesian_rule_list | 1.0000 |
| 5 | adult_income | gradient_boosting | bayesian_rule_list | 1.0000 |
| 6 | adult_income | mlp | integrated_gradients | 1.0000 |
| 7 | adult_income | mlp | shapley_flow | 1.0000 |
| 8 | adult_income | mlp | bayesian_rule_list | 1.0000 |
| 9 | compas | decision_tree | shapley_flow | 1.0000 |
| 10 | compas | decision_tree | bayesian_rule_list | 1.0000 |

