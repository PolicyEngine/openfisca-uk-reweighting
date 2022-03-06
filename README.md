# OpenFisca-UK re-weighting data

This repository contains data used to reproduce results in the re-weighting process for OpenFisca-UK.

### `no_val_split/training_log.csv.gz`

This compressed CSV file contains the training log for the final run of the re-weighting process: no validation split, training on all metrics. Each row contains one atomic metric (e.g. Income Tax revenue in 2020), and the corresponding error and loss.

### `train_val_split/training_log.csv.gz`

This compressed CSV file contains the training logs for all five folds of the cross-validation process, in the same format as the final run.
