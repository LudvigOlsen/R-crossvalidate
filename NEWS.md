# cvms 0.0.0.9000

* Adds reconstruct_formulas() for reconstructing formulas based on model definition columns in the results tibble.

* Adds combine_predictors() for generating model formulas from a set of fixed effects.

* Adds select_metrics() for quickly selecting the metrics and model definition columns.

* Breaking change: Metrics have been rearranged and a few metrics have been added.  

* Breaking change: Renamed argument folds_col to fold_cols to better fit the new repeated cross-validation option.  

* New: repeated cross-validation.  

* Created package :)  