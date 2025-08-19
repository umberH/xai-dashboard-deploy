# Comprehensive XAI Benchmarking Report

Generated on: 2025-08-19 18:36:21

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
| adult_income | decision_tree | 0.8405 | 0.8326 | N/A | N/A | train_f1: 0.8247; test_f1: 0.8159; train_precision: 0.8365; test_precision: 0.8264; train_recall: 0.8405; test_recall: 0.8326; overfitting_gap: 0.0079; overfitting_severity: low; class_accuracies: [0.957845950121386, 0.45472703062583225]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 0.0293; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | random_forest | 0.8425 | 0.8333 | N/A | N/A | train_f1: 0.8267; test_f1: 0.8160; train_precision: 0.8392; test_precision: 0.8278; train_recall: 0.8425; test_recall: 0.8333; overfitting_gap: 0.0092; overfitting_severity: low; class_accuracies: [0.9602736702714633, 0.45006657789613846]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 0.9797; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | gradient_boosting | 0.8387 | 0.8356 | N/A | N/A | train_f1: 0.8229; test_f1: 0.8189; train_precision: 0.8340; test_precision: 0.8305; train_recall: 0.8387; test_recall: 0.8356; overfitting_gap: 0.0031; overfitting_severity: low; class_accuracies: [0.9607150739351137, 0.4580559254327563]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 0.9546; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | mlp | 0.8257 | 0.8236 | N/A | N/A | train_f1: 0.8112; test_f1: 0.8083; train_precision: 0.8161; test_precision: 0.8137; train_recall: 0.8257; test_recall: 0.8236; overfitting_gap: 0.0021; overfitting_severity: low; class_accuracies: [0.9452659457073493, 0.4567243675099867]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 7.7590; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | decision_tree | 0.7375 | 0.6736 | N/A | N/A | train_f1: 0.7347; test_f1: 0.6706; train_precision: 0.7381; test_precision: 0.6721; train_recall: 0.7375; test_recall: 0.6736; overfitting_gap: 0.0639; overfitting_severity: low; class_accuracies: [0.755359394703657, 0.5738461538461539]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.0053; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | random_forest | 0.7538 | 0.6826 | N/A | N/A | train_f1: 0.7516; test_f1: 0.6797; train_precision: 0.7543; test_precision: 0.6813; train_recall: 0.7538; test_recall: 0.6826; overfitting_gap: 0.0712; overfitting_severity: low; class_accuracies: [0.7629255989911727, 0.5846153846153846]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.4624; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | gradient_boosting | 0.7054 | 0.6951 | N/A | N/A | train_f1: 0.7025; test_f1: 0.6924; train_precision: 0.7049; test_precision: 0.6941; train_recall: 0.7054; test_recall: 0.6951; overfitting_gap: 0.0103; overfitting_severity: low; class_accuracies: [0.7730138713745272, 0.6]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.3383; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | mlp | 0.6881 | 0.6854 | N/A | N/A | train_f1: 0.6862; test_f1: 0.6837; train_precision: 0.6868; test_precision: 0.6840; train_recall: 0.6881; test_recall: 0.6854; overfitting_gap: 0.0027; overfitting_severity: low; class_accuracies: [0.7490542244640606, 0.6076923076923076]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 1.3701; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| mnist | cnn | 1.0000 | 0.9800 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9805; train_precision: 1.0000; test_precision: 0.9832; train_recall: 1.0000; test_recall: 0.9800; overfitting_gap: 0.0200; overfitting_severity: low; class_accuracies: [1.0, 1.0, 1.0, 1.0, 0.9285714285714286, 1.0, 1.0, 0.9583333333333334, 0.9, 1.0]; n_classes: 10.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 6.3928; model_complexity: {'n_parameters': 688138, 'model_size_bytes': 2752552, 'model_size_mb': 2.6250381469726562, 'complexity_level': 'complex'} |
| mnist | vit | 0.7870 | 0.7250 | N/A | N/A | train_f1: 0.7830; test_f1: 0.7174; train_precision: 0.8108; test_precision: 0.7505; train_recall: 0.7870; test_recall: 0.7250; overfitting_gap: 0.0620; overfitting_severity: low; class_accuracies: [0.9411764705882353, 1.0, 0.625, 0.5, 0.7142857142857143, 0.5, 0.4, 0.8333333333333334, 0.8, 0.8095238095238095]; n_classes: 10.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 8.8283; model_complexity: {'n_parameters': 3231242, 'model_size_bytes': 12924968, 'model_size_mb': 12.326210021972656, 'complexity_level': 'complex'} |
| imdb | bert | 0.9180 | 0.8100 | N/A | N/A | train_f1: 0.9180; test_f1: 0.8099; train_precision: 0.9180; test_precision: 0.8105; train_recall: 0.9180; test_recall: 0.8100; overfitting_gap: 0.1080; overfitting_severity: moderate; class_accuracies: [0.79, 0.83]; n_classes: 2.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 0.4216; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| imdb | lstm | 0.8870 | 0.8150 | N/A | N/A | train_f1: 0.8870; test_f1: 0.8149; train_precision: 0.8870; test_precision: 0.8158; train_recall: 0.8870; test_recall: 0.8150; overfitting_gap: 0.0720; overfitting_severity: low; class_accuracies: [0.84, 0.79]; n_classes: 2.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 0.7605; model_complexity: {'n_parameters': 4, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |

## XAI Evaluation Results Table

Each row represents a unique combination of Dataset, Model, and Explanation Method with their evaluation metrics.

| Dataset | Model | Explanation Method | Detailed Report | Time Complexity | Faithfulness | Monotonicity | Completeness | Stability | Consistency | Sparsity | Simplicity | Advanced Identity | Advanced Separability | Advanced Non Sensitivity | Advanced Compactness | Advanced Correctness | Advanced Entropy | Advanced Gini Coefficient | Advanced Kl Divergence |
|---------|-------|-------------------|-----------------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|
| adult_income | decision_tree | shap | [View Details](#) | 0.0008 | 0.1900 | 0.0200 | 0.0100 | 0.0000 | 0.4651 | 0.0300 | 0.9520 | 0.9432 | 0.1706 | 1.0000 | 0.1775 | 0.6240 | 0.0215 | 0.1420 | 0.1685 |
| adult_income | decision_tree | lime | [View Details](#) | 0.0110 | 0.0800 | 0.0267 | 0.0000 | 0.0000 | 0.4831 | 0.0360 | 0.9432 | 0.8511 | 0.2491 | 1.0000 | 0.2538 | 0.6044 | 0.0171 | 0.2032 | 0.2429 |
| adult_income | decision_tree | causal_shap | [View Details](#) | 0.0176 | 0.2400 | 0.0200 | 0.0200 | 0.0000 | 0.5455 | 0.0360 | 0.9497 | 1.0000 | 0.1774 | 1.0000 | 0.1856 | 0.5810 | 0.0254 | 0.1497 | 0.1746 |
| adult_income | decision_tree | shapley_flow | [View Details](#) | 0.0087 | 0.1000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | shap_interactive | [View Details](#) | 0.0206 | 0.2333 | 0.0333 | 0.0360 | 0.0000 | 0.3905 | 0.1000 | 0.9418 | 0.9163 | 0.2800 | 1.0000 | 0.2815 | 0.6256 | 0.0846 | 0.2293 | 0.2487 |
| adult_income | decision_tree | prototype | [View Details](#) | 0.0009 | 0.6600 | 0.8132 | 1.0000 | 0.9015 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | counterfactual | [View Details](#) | 0.0006 | 0.7100 | 0.1704 | 1.0000 | 0.8185 | 0.7944 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | bayesian_rule_list | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5670 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | corels | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5670 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | feature_ablation | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4632 | 0.0240 | 0.9440 | 1.0000 | 0.2245 | 1.0000 | 0.2300 | 0.6040 | 0.0172 | 0.1840 | 0.2228 |
| adult_income | random_forest | shap | [View Details](#) | 0.0323 | 0.1900 | 0.0200 | 0.0000 | 0.0000 | 0.4696 | 0.0140 | 0.9440 | 0.9438 | 0.1647 | 1.0000 | 0.1675 | 0.6170 | 0.0291 | 0.1340 | 0.1609 |
| adult_income | random_forest | lime | [View Details](#) | 0.0306 | 0.0800 | 0.0400 | 0.0000 | 0.0000 | 0.4039 | 0.0360 | 0.9543 | 0.8696 | 0.1863 | 1.0000 | 0.1921 | 0.5850 | 0.0195 | 0.1543 | 0.1805 |
| adult_income | random_forest | causal_shap | [View Details](#) | 0.8681 | 0.2400 | 0.0200 | 0.0000 | 0.0000 | 0.5256 | 0.0360 | 0.9420 | 1.0000 | 0.1685 | 1.0000 | 0.1744 | 0.5784 | 0.0375 | 0.1420 | 0.1625 |
| adult_income | random_forest | shapley_flow | [View Details](#) | 0.3964 | 0.1333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | shap_interactive | [View Details](#) | 0.8175 | 0.2667 | 0.0333 | 0.0278 | 0.0000 | 0.3427 | 0.0800 | 0.9280 | 0.9256 | 0.2659 | 1.0000 | 0.2603 | 0.6229 | 0.1046 | 0.2130 | 0.2288 |
| adult_income | random_forest | prototype | [View Details](#) | 0.0052 | 0.7050 | 0.7844 | 1.0000 | 0.8772 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | counterfactual | [View Details](#) | 0.0063 | 0.7100 | 0.2008 | 1.0000 | 0.8791 | 0.7503 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | bayesian_rule_list | [View Details](#) | 0.0041 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | corels | [View Details](#) | 0.0038 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | feature_ablation | [View Details](#) | 0.0201 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4509 | 0.0120 | 0.9320 | 1.0000 | 0.2132 | 1.0000 | 0.2150 | 0.6040 | 0.0309 | 0.1720 | 0.2091 |
| adult_income | gradient_boosting | shap | [View Details](#) | 0.0021 | 0.2100 | 0.0300 | 0.0000 | 0.0000 | 0.4896 | 0.0220 | 0.9400 | 0.9432 | 0.1825 | 1.0000 | 0.1875 | 0.6440 | 0.0316 | 0.1500 | 0.1784 |
| adult_income | gradient_boosting | lime | [View Details](#) | 0.0170 | 0.1200 | 0.0300 | 0.0000 | 0.0000 | 0.4818 | 0.0600 | 0.9484 | 0.9091 | 0.1749 | 1.0000 | 0.1849 | 0.6074 | 0.0347 | 0.1484 | 0.1653 |
| adult_income | gradient_boosting | causal_shap | [View Details](#) | 0.0526 | 0.2600 | 0.0200 | 0.0000 | 0.0000 | 0.5880 | 0.0400 | 0.9487 | 0.9877 | 0.1888 | 1.0000 | 0.1925 | 0.6109 | 0.0502 | 0.1537 | 0.1698 |
| adult_income | gradient_boosting | shap_interactive | [View Details](#) | 0.0594 | 0.3333 | 0.0333 | 0.0000 | 0.0000 | 0.4847 | 0.0867 | 0.9280 | 0.9544 | 0.2741 | 1.0000 | 0.2776 | 0.6531 | 0.0989 | 0.2245 | 0.2345 |
| adult_income | gradient_boosting | prototype | [View Details](#) | 0.0012 | 0.7500 | 0.8349 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | counterfactual | [View Details](#) | 0.0009 | 0.6950 | 0.1989 | 1.0000 | 0.8134 | 0.6070 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0014 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5810 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | corels | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5810 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | feature_ablation | [View Details](#) | 0.0010 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4954 | 0.0200 | 0.9360 | 1.0000 | 0.2404 | 1.0000 | 0.2450 | 0.6380 | 0.0223 | 0.1960 | 0.2377 |
| adult_income | mlp | shap | [View Details](#) | 0.0009 | 0.2200 | 0.0250 | 0.0000 | 0.0000 | 0.4396 | 0.0260 | 0.9420 | 0.9032 | 0.1970 | 1.0000 | 0.2025 | 0.6400 | 0.0258 | 0.1620 | 0.1942 |
| adult_income | mlp | lime | [View Details](#) | 0.0143 | 0.0600 | 0.0250 | 0.0000 | 0.0000 | 0.5280 | 0.0720 | 0.9585 | 0.8723 | 0.1085 | 1.0000 | 0.1217 | 0.5720 | 0.0438 | 0.0985 | 0.0962 |
| adult_income | mlp | integrated_gradients | [View Details](#) | 0.0560 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5833 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | causal_shap | [View Details](#) | 0.0402 | 0.2400 | 0.0090 | 0.0000 | 0.0000 | 0.5159 | 0.0440 | 0.9680 | 0.9880 | 0.1726 | 1.0000 | 0.1718 | 0.5969 | 0.0511 | 0.1375 | 0.1489 |
| adult_income | mlp | shapley_flow | [View Details](#) | 0.0366 | 0.1000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5833 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | shap_interactive | [View Details](#) | 0.0528 | 0.3000 | 0.0250 | 0.0895 | 0.0000 | 0.4185 | 0.1267 | 0.9536 | 0.8587 | 0.2872 | 1.0000 | 0.2718 | 0.6578 | 0.1477 | 0.2241 | 0.2190 |
| adult_income | mlp | prototype | [View Details](#) | 0.0013 | 0.7200 | 0.8121 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | counterfactual | [View Details](#) | 0.0007 | 0.7450 | 0.2062 | 1.0000 | 0.8868 | 0.7602 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | influence_functions | [View Details](#) | 0.0245 | 0.0000 | 0.0000 | 0.0000 | 0.2615 | 0.4384 | 0.6000 | 0.4358 | 1.0000 | 0.4254 | 1.0000 | 0.5102 | 0.7454 | 0.7768 | 0.4358 | 0.2232 |
| adult_income | mlp | bayesian_rule_list | [View Details](#) | 0.0010 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5740 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | corels | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5740 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | feature_ablation | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4377 | 0.0240 | 0.9320 | 1.0000 | 0.2845 | 1.0000 | 0.2900 | 0.6360 | 0.0172 | 0.2320 | 0.2828 |
| compas | decision_tree | shap | [View Details](#) | 0.0006 | 0.6500 | 0.0300 | 0.0000 | 0.0000 | 0.6861 | 0.3500 | 0.7000 | 0.6292 | 0.3712 | 1.0000 | 0.5250 | 0.6090 | 0.1525 | 0.3500 | 0.4975 |
| compas | decision_tree | lime | [View Details](#) | 0.0118 | 0.3200 | 0.0800 | 0.0000 | 0.0000 | 0.7431 | 0.6267 | 0.6812 | 0.5102 | 0.6563 | 1.0000 | 0.9308 | 0.5974 | 0.0251 | 0.6212 | 0.9149 |
| compas | decision_tree | causal_shap | [View Details](#) | 0.0116 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.6276 | 0.3133 | 0.7499 | 1.0000 | 0.2183 | 1.0000 | 0.2933 | 0.3951 | 0.2406 | 0.2080 | 0.2394 |
| compas | decision_tree | shapley_flow | [View Details](#) | 0.0066 | 0.3333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3733 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | shap_interactive | [View Details](#) | 0.0139 | 0.6000 | 0.0222 | 0.0758 | 0.0000 | 0.7064 | 0.5556 | 0.7079 | 0.6648 | 0.4515 | 1.0000 | 0.5132 | 0.5125 | 0.4832 | 0.3594 | 0.3835 |
| compas | decision_tree | prototype | [View Details](#) | 0.0009 | 0.6550 | 0.7293 | 1.0000 | 0.9475 | 0.3605 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | counterfactual | [View Details](#) | 0.0010 | 0.6900 | 0.2535 | 1.0000 | 0.9081 | 0.7413 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | bayesian_rule_list | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | corels | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 1.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | feature_ablation | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6747 | 0.3667 | 0.6667 | 1.0000 | 0.3889 | 1.0000 | 0.5500 | 0.5260 | 0.1840 | 0.3667 | 0.5160 |
| compas | random_forest | shap | [View Details](#) | 0.0299 | 0.6300 | 0.0383 | 0.0000 | 0.0000 | 0.7164 | 0.3233 | 0.6933 | 0.6548 | 0.3429 | 0.9999 | 0.4850 | 0.6240 | 0.1777 | 0.3233 | 0.4523 |
| compas | random_forest | lime | [View Details](#) | 0.0226 | 0.3400 | 0.0867 | 0.0000 | 0.0000 | 0.7961 | 0.4800 | 0.7039 | 0.6389 | 0.4352 | 1.0000 | 0.6227 | 0.5441 | 0.1593 | 0.4239 | 0.5607 |
| compas | random_forest | causal_shap | [View Details](#) | 0.4191 | 0.4800 | 0.0300 | 0.0000 | 0.0000 | 0.6526 | 0.3200 | 0.7416 | 1.0000 | 0.2136 | 0.9991 | 0.2834 | 0.4489 | 0.2812 | 0.2042 | 0.2188 |
| compas | random_forest | shapley_flow | [View Details](#) | 0.2084 | 0.4333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3733 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | shap_interactive | [View Details](#) | 0.4574 | 0.6333 | 0.0556 | 0.0290 | 0.0000 | 0.6972 | 0.4889 | 0.6404 | 0.7547 | 0.3216 | 1.0000 | 0.3489 | 0.4600 | 0.5169 | 0.2634 | 0.2498 |
| compas | random_forest | prototype | [View Details](#) | 0.0035 | 0.6550 | 0.6888 | 1.0000 | 0.9037 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | counterfactual | [View Details](#) | 0.0037 | 0.6900 | 0.3143 | 1.0000 | 0.9367 | 0.7377 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | bayesian_rule_list | [View Details](#) | 0.0064 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4410 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | corels | [View Details](#) | 0.0052 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4410 | 1.0000 | 0.0000 | 0.0000 |
| compas | random_forest | feature_ablation | [View Details](#) | 0.0324 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.7118 | 0.2933 | 0.6333 | 1.0000 | 0.3111 | 1.0000 | 0.4400 | 0.5640 | 0.2671 | 0.2933 | 0.3929 |
| compas | gradient_boosting | shap | [View Details](#) | 0.0016 | 0.6100 | 0.0250 | 0.0000 | 0.0000 | 0.7096 | 0.3233 | 0.7133 | 0.6705 | 0.3429 | 1.0000 | 0.4850 | 0.6490 | 0.1551 | 0.3233 | 0.4549 |
| compas | gradient_boosting | lime | [View Details](#) | 0.0102 | 0.3800 | 0.1300 | 0.0000 | 0.3344 | 0.9104 | 0.5467 | 0.7186 | 0.5682 | 0.5678 | 1.0000 | 0.8063 | 0.6428 | 0.0343 | 0.5386 | 0.7857 |
| compas | gradient_boosting | causal_shap | [View Details](#) | 0.0263 | 0.4400 | 0.0300 | 0.0000 | 0.0000 | 0.6292 | 0.3267 | 0.6868 | 1.0000 | 0.1828 | 1.0000 | 0.2515 | 0.4548 | 0.3180 | 0.1868 | 0.1820 |
| compas | gradient_boosting | shap_interactive | [View Details](#) | 0.0268 | 0.6000 | 0.0611 | 0.0164 | 0.0000 | 0.6303 | 0.5000 | 0.6507 | 0.7283 | 0.3366 | 0.9980 | 0.3865 | 0.4924 | 0.4950 | 0.2825 | 0.2717 |
| compas | gradient_boosting | prototype | [View Details](#) | 0.0005 | 0.7150 | 0.6930 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | counterfactual | [View Details](#) | 0.0004 | 0.6700 | 0.2981 | 1.0000 | 0.9125 | 0.2818 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | corels | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 1.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | feature_ablation | [View Details](#) | 0.0014 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6815 | 0.3333 | 0.6933 | 1.0000 | 0.3536 | 0.9999 | 0.5000 | 0.5980 | 0.1767 | 0.3333 | 0.4633 |
| compas | mlp | shap | [View Details](#) | 0.0006 | 0.5800 | 0.0100 | 0.0000 | 0.0000 | 0.7432 | 0.3800 | 0.8000 | 0.6556 | 0.4031 | 1.0000 | 0.5700 | 0.6430 | 0.0126 | 0.3800 | 0.5674 |
| compas | mlp | lime | [View Details](#) | 0.0096 | 0.0400 | 0.0000 | 0.0000 | 0.0000 | 0.8175 | 0.3600 | 0.7909 | 0.6136 | 0.3439 | 1.0000 | 0.4891 | 0.5431 | 0.0794 | 0.3309 | 0.4606 |
| compas | mlp | integrated_gradients | [View Details](#) | 0.0270 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | causal_shap | [View Details](#) | 0.0137 | 0.3400 | 0.0000 | 0.0000 | 0.0000 | 0.5894 | 0.3000 | 0.7997 | 1.0000 | 0.2560 | 1.0000 | 0.3455 | 0.5040 | 0.1463 | 0.2362 | 0.3137 |
| compas | mlp | shapley_flow | [View Details](#) | 0.0088 | 0.2333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | shap_interactive | [View Details](#) | 0.0187 | 0.5333 | 0.0111 | 0.0147 | 0.0000 | 0.6732 | 0.5111 | 0.8171 | 0.6004 | 0.4620 | 1.0000 | 0.5055 | 0.6017 | 0.3785 | 0.3538 | 0.4215 |
| compas | mlp | prototype | [View Details](#) | 0.0003 | 0.6400 | 0.7072 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | counterfactual | [View Details](#) | 0.0003 | 0.6850 | 0.3153 | 1.0000 | 0.7364 | 0.5201 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | influence_functions | [View Details](#) | 0.0228 | 0.0000 | 0.0000 | 0.0000 | 0.3834 | 0.7184 | 0.6667 | 0.4325 | 1.0000 | 0.4194 | 1.0000 | 0.6078 | 0.6356 | 0.6415 | 0.4325 | 0.3585 |
| compas | mlp | bayesian_rule_list | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 1.0000 | 0.0000 | 0.0000 |
| compas | mlp | feature_ablation | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.7167 | 0.3800 | 0.8000 | 1.0000 | 0.4031 | 1.0000 | 0.5700 | 0.5800 | 0.0126 | 0.3800 | 0.5674 |
| mnist | cnn | prototype | [View Details](#) | 0.0015 | 0.9800 | 0.65812224 | 1.0000 | 0.5177 | 0.3078 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | cnn | counterfactual | [View Details](#) | 0.0034 | 0.9800 | 0.46375066 | 1.0000 | 0.6910 | 0.3697 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | cnn | tcav | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | cnn | concept_bottleneck | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | cnn | occlusion | [View Details](#) | 0.0186 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | vit | tcav | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | vit | concept_bottleneck | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | vit | occlusion | [View Details](#) | 0.1082 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| imdb | bert | lime | [View Details](#) | 0.0633 | 0.8400 | 0.0000 | 0.0000 | 0.0694 | 0.1329 | 0.7400 | 0.4551 | 1.0000 | 0.4748 | 0.0000 | 0.4631 | 0.5942 | 0.9024 | 0.4551 | 0.0976 |
| imdb | bert | text_occlusion | [View Details](#) | 0.0347 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0552 | 0.0046 | 0.8016 | 1.0000 | 0.0890 | 0.0000 | 0.0824 | 0.6360 | 0.2137 | 0.0816 | 0.0663 |
| imdb | bert | attention_visualization | [View Details](#) | 0.0861 | 0.0000 | 0.0000 | 0.0000 | 0.7141 | 0.0947 | 0.7005 | 0.0381 | 1.0000 | 0.0360 | 0.0000 | 0.0055 | 0.5880 | 0.9994 | 0.0381 | 0.0006 |
| imdb | lstm | lime | [View Details](#) | 0.0670 | 0.8000 | 0.0000 | 0.0000 | 0.0000 | 0.1174 | 0.7400 | 0.4716 | 1.0000 | 0.5278 | 0.0000 | 0.5052 | 0.5680 | 0.8901 | 0.4716 | 0.1099 |
| imdb | lstm | text_occlusion | [View Details](#) | 0.0586 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0627 | 0.0062 | 0.7822 | 1.0000 | 0.1734 | 0.0000 | 0.1638 | 0.6500 | 0.2449 | 0.1622 | 0.1351 |
| imdb | lstm | attention_visualization | [View Details](#) | 0.2054 | 0.0000 | 0.0000 | 0.0000 | 0.7135 | 0.0924 | 0.6971 | 0.0385 | 1.0000 | 0.0371 | 0.0000 | 0.0059 | 0.5600 | 0.9994 | 0.0385 | 0.0006 |

## Detailed Explanation Analysis

Summary of detailed explanations generated for the entire test set.

| Dataset | Model | Method | Test Instances | Valid Explanations | Accuracy | Avg Feature Importance | Detailed Files |
|---------|-------|--------|----------------|-------------------|----------|----------------------|----------------|
| adult_income | decision_tree | shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\shap_detailed_explanations.json) |
| adult_income | decision_tree | lime | 6033 | 6033 | 0.833 | 0.0358 | [JSON](detailed_explanations\adult_income\decision_tree\lime_detailed_explanations.json) |
| adult_income | decision_tree | causal_shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\causal_shap_detailed_explanations.json) |
| adult_income | decision_tree | shapley_flow | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\shapley_flow_detailed_explanations.json) |
| adult_income | decision_tree | shap_interactive | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\shap_interactive_detailed_explanations.json) |
| adult_income | decision_tree | prototype | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\prototype_detailed_explanations.json) |
| adult_income | decision_tree | counterfactual | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\counterfactual_detailed_explanations.json) |
| adult_income | decision_tree | bayesian_rule_list | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| adult_income | decision_tree | corels | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\corels_detailed_explanations.json) |
| adult_income | decision_tree | feature_ablation | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\feature_ablation_detailed_explanations.json) |
| adult_income | random_forest | shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\shap_detailed_explanations.json) |
| adult_income | random_forest | lime | 6033 | 6033 | 0.833 | 0.0297 | [JSON](detailed_explanations\adult_income\random_forest\lime_detailed_explanations.json) |
| adult_income | random_forest | causal_shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\causal_shap_detailed_explanations.json) |
| adult_income | random_forest | shapley_flow | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\shapley_flow_detailed_explanations.json) |
| adult_income | random_forest | shap_interactive | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\shap_interactive_detailed_explanations.json) |
| adult_income | random_forest | prototype | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\prototype_detailed_explanations.json) |
| adult_income | random_forest | counterfactual | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\counterfactual_detailed_explanations.json) |
| adult_income | random_forest | bayesian_rule_list | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\bayesian_rule_list_detailed_explanations.json) |
| adult_income | random_forest | corels | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\corels_detailed_explanations.json) |
| adult_income | random_forest | feature_ablation | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\feature_ablation_detailed_explanations.json) |
| adult_income | gradient_boosting | shap | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\shap_detailed_explanations.json) |
| adult_income | gradient_boosting | lime | 6033 | 6033 | 0.836 | 0.0276 | [JSON](detailed_explanations\adult_income\gradient_boosting\lime_detailed_explanations.json) |
| adult_income | gradient_boosting | causal_shap | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\causal_shap_detailed_explanations.json) |
| adult_income | gradient_boosting | shap_interactive | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\shap_interactive_detailed_explanations.json) |
| adult_income | gradient_boosting | prototype | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\prototype_detailed_explanations.json) |
| adult_income | gradient_boosting | counterfactual | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\counterfactual_detailed_explanations.json) |
| adult_income | gradient_boosting | bayesian_rule_list | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| adult_income | gradient_boosting | corels | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\corels_detailed_explanations.json) |
| adult_income | gradient_boosting | feature_ablation | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\feature_ablation_detailed_explanations.json) |
| adult_income | mlp | shap | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\shap_detailed_explanations.json) |
| adult_income | mlp | lime | 6033 | 6033 | 0.824 | 0.0213 | [JSON](detailed_explanations\adult_income\mlp\lime_detailed_explanations.json) |
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
| compas | decision_tree | lime | 1443 | 1443 | 0.674 | 0.2640 | [JSON](detailed_explanations\compas\decision_tree\lime_detailed_explanations.json) |
| compas | decision_tree | causal_shap | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\causal_shap_detailed_explanations.json) |
| compas | decision_tree | shapley_flow | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\shapley_flow_detailed_explanations.json) |
| compas | decision_tree | shap_interactive | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\shap_interactive_detailed_explanations.json) |
| compas | decision_tree | prototype | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\prototype_detailed_explanations.json) |
| compas | decision_tree | counterfactual | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\counterfactual_detailed_explanations.json) |
| compas | decision_tree | bayesian_rule_list | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| compas | decision_tree | corels | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\corels_detailed_explanations.json) |
| compas | decision_tree | feature_ablation | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\feature_ablation_detailed_explanations.json) |
| compas | random_forest | shap | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\shap_detailed_explanations.json) |
| compas | random_forest | lime | 1443 | 1443 | 0.683 | 0.0663 | [JSON](detailed_explanations\compas\random_forest\lime_detailed_explanations.json) |
| compas | random_forest | causal_shap | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\causal_shap_detailed_explanations.json) |
| compas | random_forest | shapley_flow | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\shapley_flow_detailed_explanations.json) |
| compas | random_forest | shap_interactive | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\shap_interactive_detailed_explanations.json) |
| compas | random_forest | prototype | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\prototype_detailed_explanations.json) |
| compas | random_forest | counterfactual | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\counterfactual_detailed_explanations.json) |
| compas | random_forest | bayesian_rule_list | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\bayesian_rule_list_detailed_explanations.json) |
| compas | random_forest | corels | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\corels_detailed_explanations.json) |
| compas | random_forest | feature_ablation | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\feature_ablation_detailed_explanations.json) |
| compas | gradient_boosting | shap | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\shap_detailed_explanations.json) |
| compas | gradient_boosting | lime | 1443 | 1443 | 0.695 | 0.2292 | [JSON](detailed_explanations\compas\gradient_boosting\lime_detailed_explanations.json) |
| compas | gradient_boosting | causal_shap | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\causal_shap_detailed_explanations.json) |
| compas | gradient_boosting | shap_interactive | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\shap_interactive_detailed_explanations.json) |
| compas | gradient_boosting | prototype | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\prototype_detailed_explanations.json) |
| compas | gradient_boosting | counterfactual | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\counterfactual_detailed_explanations.json) |
| compas | gradient_boosting | bayesian_rule_list | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| compas | gradient_boosting | corels | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\corels_detailed_explanations.json) |
| compas | gradient_boosting | feature_ablation | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\feature_ablation_detailed_explanations.json) |
| compas | mlp | shap | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\shap_detailed_explanations.json) |
| compas | mlp | lime | 1443 | 1443 | 0.685 | 0.1139 | [JSON](detailed_explanations\compas\mlp\lime_detailed_explanations.json) |
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
| mnist | cnn | prototype | 200 | 200 | 0.980 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\prototype_detailed_explanations.json) |
| mnist | cnn | counterfactual | 200 | 200 | 0.980 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\counterfactual_detailed_explanations.json) |
| mnist | cnn | tcav | 200 | 200 | 0.980 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\tcav_detailed_explanations.json) |
| mnist | cnn | concept_bottleneck | 200 | 200 | 0.980 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\concept_bottleneck_detailed_explanations.json) |
| mnist | cnn | occlusion | 200 | 200 | 0.980 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\occlusion_detailed_explanations.json) |
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
| decision_tree | shap | 0.0008 | 0.1900 | 0.0200 |
| decision_tree | lime | 0.0110 | 0.0800 | 0.0267 |
| decision_tree | causal_shap | 0.0176 | 0.2400 | 0.0200 |
| decision_tree | shapley_flow | 0.0087 | 0.1000 | 0.0000 |
| decision_tree | shap_interactive | 0.0206 | 0.2333 | 0.0333 |
| decision_tree | prototype | 0.0009 | 0.6600 | 0.8132 |
| decision_tree | counterfactual | 0.0006 | 0.7100 | 0.1704 |
| decision_tree | bayesian_rule_list | 0.0006 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0005 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0005 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0323 | 0.1900 | 0.0200 |
| random_forest | lime | 0.0306 | 0.0800 | 0.0400 |
| random_forest | causal_shap | 0.8681 | 0.2400 | 0.0200 |
| random_forest | shapley_flow | 0.3964 | 0.1333 | 0.0000 |
| random_forest | shap_interactive | 0.8175 | 0.2667 | 0.0333 |
| random_forest | prototype | 0.0052 | 0.7050 | 0.7844 |
| random_forest | counterfactual | 0.0063 | 0.7100 | 0.2008 |
| random_forest | bayesian_rule_list | 0.0041 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0038 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0201 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0021 | 0.2100 | 0.0300 |
| gradient_boosting | lime | 0.0170 | 0.1200 | 0.0300 |
| gradient_boosting | causal_shap | 0.0526 | 0.2600 | 0.0200 |
| gradient_boosting | shap_interactive | 0.0594 | 0.3333 | 0.0333 |
| gradient_boosting | prototype | 0.0012 | 0.7500 | 0.8349 |
| gradient_boosting | counterfactual | 0.0009 | 0.6950 | 0.1989 |
| gradient_boosting | bayesian_rule_list | 0.0014 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0008 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0010 | 0.0000 | 0.0000 |
| mlp | shap | 0.0009 | 0.2200 | 0.0250 |
| mlp | lime | 0.0143 | 0.0600 | 0.0250 |
| mlp | integrated_gradients | 0.0560 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0402 | 0.2400 | 0.0090 |
| mlp | shapley_flow | 0.0366 | 0.1000 | 0.0000 |
| mlp | shap_interactive | 0.0528 | 0.3000 | 0.0250 |
| mlp | prototype | 0.0013 | 0.7200 | 0.8121 |
| mlp | counterfactual | 0.0007 | 0.7450 | 0.2062 |
| mlp | influence_functions | 0.0245 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0010 | 0.0000 | 0.0000 |
| mlp | corels | 0.0004 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0005 | 0.0000 | 0.0000 |

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
| decision_tree | shap | 0.0006 | 0.6500 | 0.0300 |
| decision_tree | lime | 0.0118 | 0.3200 | 0.0800 |
| decision_tree | causal_shap | 0.0116 | 0.5000 | 0.0000 |
| decision_tree | shapley_flow | 0.0066 | 0.3333 | 0.0000 |
| decision_tree | shap_interactive | 0.0139 | 0.6000 | 0.0222 |
| decision_tree | prototype | 0.0009 | 0.6550 | 0.7293 |
| decision_tree | counterfactual | 0.0010 | 0.6900 | 0.2535 |
| decision_tree | bayesian_rule_list | 0.0007 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0005 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0004 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0299 | 0.6300 | 0.0383 |
| random_forest | lime | 0.0226 | 0.3400 | 0.0867 |
| random_forest | causal_shap | 0.4191 | 0.4800 | 0.0300 |
| random_forest | shapley_flow | 0.2084 | 0.4333 | 0.0000 |
| random_forest | shap_interactive | 0.4574 | 0.6333 | 0.0556 |
| random_forest | prototype | 0.0035 | 0.6550 | 0.6888 |
| random_forest | counterfactual | 0.0037 | 0.6900 | 0.3143 |
| random_forest | bayesian_rule_list | 0.0064 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0052 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0324 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0016 | 0.6100 | 0.0250 |
| gradient_boosting | lime | 0.0102 | 0.3800 | 0.1300 |
| gradient_boosting | causal_shap | 0.0263 | 0.4400 | 0.0300 |
| gradient_boosting | shap_interactive | 0.0268 | 0.6000 | 0.0611 |
| gradient_boosting | prototype | 0.0005 | 0.7150 | 0.6930 |
| gradient_boosting | counterfactual | 0.0004 | 0.6700 | 0.2981 |
| gradient_boosting | bayesian_rule_list | 0.0007 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0004 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0014 | 0.0000 | 0.0000 |
| mlp | shap | 0.0006 | 0.5800 | 0.0100 |
| mlp | lime | 0.0096 | 0.0400 | 0.0000 |
| mlp | integrated_gradients | 0.0270 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0137 | 0.3400 | 0.0000 |
| mlp | shapley_flow | 0.0088 | 0.2333 | 0.0000 |
| mlp | shap_interactive | 0.0187 | 0.5333 | 0.0111 |
| mlp | prototype | 0.0003 | 0.6400 | 0.7072 |
| mlp | counterfactual | 0.0003 | 0.6850 | 0.3153 |
| mlp | influence_functions | 0.0228 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0004 | 0.0000 | 0.0000 |
| mlp | corels | 0.0003 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0003 | 0.0000 | 0.0000 |

### imdb

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| bert | 0.9180 | 0.8100 | N/A | N/A |
| lstm | 0.8870 | 0.8150 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| bert | lime | 0.0633 | 0.8400 | 0.0000 |
| bert | text_occlusion | 0.0347 | 0.0000 | 0.0000 |
| bert | attention_visualization | 0.0861 | 0.0000 | 0.0000 |
| lstm | lime | 0.0670 | 0.8000 | 0.0000 |
| lstm | text_occlusion | 0.0586 | 0.0000 | 0.0000 |
| lstm | attention_visualization | 0.2054 | 0.0000 | 0.0000 |

### mnist

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| cnn | 1.0000 | 0.9800 | N/A | N/A |
| vit | 0.7870 | 0.7250 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| cnn | prototype | 0.0015 | 0.9800 | 0.65812224 |
| cnn | counterfactual | 0.0034 | 0.9800 | 0.46375066 |
| cnn | tcav | 0.0000 | 0.0000 | 0.0000 |
| cnn | concept_bottleneck | 0.0000 | 0.0000 | 0.0000 |
| cnn | occlusion | 0.0186 | 0.0000 | 0.0000 |
| vit | tcav | 0.0000 | 0.0000 | 0.0000 |
| vit | concept_bottleneck | 0.0000 | 0.0000 | 0.0000 |
| vit | occlusion | 0.1082 | 0.0000 | 0.0000 |

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
| 1 | cnn | 0.9800 |
| 2 | vit | 0.7250 |

## Top Performing XAI Combinations

### Best Time Complexity

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | adult_income | random_forest | causal_shap | 0.8681 |
| 2 | adult_income | random_forest | shap_interactive | 0.8175 |
| 3 | compas | random_forest | shap_interactive | 0.4574 |
| 4 | compas | random_forest | causal_shap | 0.4191 |
| 5 | adult_income | random_forest | shapley_flow | 0.3964 |
| 6 | compas | random_forest | shapley_flow | 0.2084 |
| 7 | imdb | lstm | attention_visualization | 0.2054 |
| 8 | mnist | vit | occlusion | 0.1082 |
| 9 | imdb | bert | attention_visualization | 0.0861 |
| 10 | imdb | lstm | lime | 0.0670 |

### Best Faithfulness

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | mnist | cnn | prototype | 0.9800 |
| 2 | mnist | cnn | counterfactual | 0.9800 |
| 3 | imdb | bert | lime | 0.8400 |
| 4 | imdb | lstm | lime | 0.8000 |
| 5 | adult_income | gradient_boosting | prototype | 0.7500 |
| 6 | adult_income | mlp | counterfactual | 0.7450 |
| 7 | adult_income | mlp | prototype | 0.7200 |
| 8 | compas | gradient_boosting | prototype | 0.7150 |
| 9 | adult_income | decision_tree | counterfactual | 0.7100 |
| 10 | adult_income | random_forest | counterfactual | 0.7100 |

### Best Monotonicity

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | adult_income | gradient_boosting | prototype | 0.8349 |
| 2 | adult_income | decision_tree | prototype | 0.8132 |
| 3 | adult_income | mlp | prototype | 0.8121 |
| 4 | adult_income | random_forest | prototype | 0.7844 |
| 5 | compas | decision_tree | prototype | 0.7293 |
| 6 | compas | mlp | prototype | 0.7072 |
| 7 | compas | gradient_boosting | prototype | 0.6930 |
| 8 | compas | random_forest | prototype | 0.6888 |
| 9 | compas | mlp | counterfactual | 0.3153 |
| 10 | compas | random_forest | counterfactual | 0.3143 |

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

