# AutoML Leaderboard

| Best model   | name                                                         | model_type     | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------|:---------------|:--------------|---------------:|-------------:|
|              | [1_Baseline](1_Baseline/README.md)                           | Baseline       | logloss       |       0.646799 |         0.63 |
|              | [2_DecisionTree](2_DecisionTree/README.md)                   | Decision Tree  | logloss       |       0.792039 |         5.56 |
|              | [3_Linear](3_Linear/README.md)                               | Linear         | logloss       |       0.472213 |         4.24 |
|              | [4_Default_Xgboost](4_Default_Xgboost/README.md)             | Xgboost        | logloss       |       0.524482 |         5.85 |
|              | [5_Default_NeuralNetwork](5_Default_NeuralNetwork/README.md) | Neural Network | logloss       |       0.978159 |         2.35 |
|              | [6_Default_RandomForest](6_Default_RandomForest/README.md)   | Random Forest  | logloss       |       0.466647 |         2.56 |
| **the best** | [Ensemble](Ensemble/README.md)                               | Ensemble       | logloss       |       0.460017 |         0.4  |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Features Importance
![features importance across models](features_heatmap.png)



### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

