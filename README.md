
## LSTF-STGCN method.
This project's data is Shenzhen Luohu traffic flow.csv

It is raw data of Shenzhen traffic flow.

If you don't have it, please contact me.
## Code structure
    ├── README.md
    ├── __pycache__
    ├── _trial_temp
    │   ├── _trial_marker
    │   └── test.log
    ├── code
    │   ├── data_processing.py
    │   ├── model_training.py
    │   ├── utils.py
    │   ├── __pycache__
    │   ├── config_loader.py
    │   ├── data_visualization.py
    │   └── evaluation_metrics.py
    ├── data
    │   ├── raw_data
    │   │   ├── graph_signal_matrix.npz
    │   │   └── adjacency_matrix.csv
    │   ├── processed_data
    │   │   ├── train_data.npz
    │   │   ├── val_data.npz
    │   │   └── test_data.npz
    │   └── predictions
    │       ├── train_predictions.npy
    │       ├── val_predictions.npy
    │       └── test_predictions.npy
    ├── models
    │   ├──   LSTF-STGCN.py
    │   ├── hstgcn.py
    │   ├── ltt.py
    │   ├── __pycache__
    │   ├── arima.py
    │   ├── gbm.py
    │   └── output
    │       ├── model_checkpoints
    │       └── trained_models
    ├── results
    │   ├── figures
    │   │   ├── training_loss.png
    │   │   ├── validation_accuracy.png
    │   │   └── test_predictions_vs_actual.png
    │   └── logs
    │       ├── training_log.txt
    │       ├── validation_log.txt
    │       └── test_log.txt
    └── requirements.txt
<!--
**AutumnwaterFlipped/AutumnwaterFlipped** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.


