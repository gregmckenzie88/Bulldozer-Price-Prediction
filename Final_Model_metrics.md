# Final Model

[sklearn.ensemble.RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)

## Model Features

| Feature Name                 | Data Type |
| ---------------------------- | --------- |
| SalesID                      | int64     |
| MachineID                    | int64     |
| ModelID                      | int64     |
| auctioneerID                 | float64   |
| YearMade                     | int64     |
| MachineHoursCurrentMeter     | float64   |
| fiModelDesc                  | int16     |
| fiBaseModel                  | int16     |
| fiSecondaryDesc              | int16     |
| ProductSize                  | int8      |
| fiProductClassDesc           | int8      |
| state                        | int8      |
| Enclosure                    | int8      |
| Engine_Horsepower            | int8      |
| Hydraulics_Flow              | int8      |
| saleYear                     | int64     |
| saleMonth                    | int64     |
| saleDate                     | int64     |
| saleDayOfWeek                | int64     |
| saleDayOfYear                | int64     |
| Engine_Horsepower_is_missing | bool      |
| Hydraulics_Flow_is_missing   | bool      |

## Hyperparameters

| Hyperparameter           | Value             |
| ------------------------ | ----------------- |
| bootstrap                | True              |
| ccp_alpha                | 0.0               |
| criterion                | squared_error     |
| max_depth                | 30                |
| max_features             | 0.900037995011649 |
| max_leaf_nodes           | None              |
| max_samples              | None              |
| min_impurity_decrease    | 0.0               |
| min_samples_leaf         | 1                 |
| min_samples_split        | 2                 |
| min_weight_fraction_leaf | 0.0               |
| n_estimators             | 250               |
| n_jobs                   | None              |
| oob_score                | False             |
| random_state             | None              |
| verbose                  | 0                 |
| warm_start               | False             |

## Performance Metrics

| Metric         | Value               |
| -------------- | ------------------- |
| Training MAE   | 1639.5948350684127  |
| Test MAE       | 4364.200469238181   |
| Training MSE   | 6730759.531112538   |
| Test MSE       | 48115859.182510115  |
| Training RMLSE | 0.08136847992294637 |
| Test RMLSE     | 0.20314577004595255 |
| Training R^2   | 0.9878619888711454  |
| Test R^2       | 0.9126307398052228  |
