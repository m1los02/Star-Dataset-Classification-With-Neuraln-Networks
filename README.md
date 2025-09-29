# Star-Dataset-Classification-With-Neural-Networks

This project uses a dataset of astronomical measurements (`Star.csv`) to build a binary classifier that predicts whether a given observation belongs to a specific type of star.  

We apply data preprocessing, feature scaling, and a neural network classifier (built with TensorFlow/Keras), and evaluate performance using accuracy, ROC-AUC, and confusion matrices.

## Dataset
- **Dataset**: `Star.csv`
- **Samples**: 5852
- **Features**:
  - 8 numerical attributes describing astronomical signals:
    - IP (Integrated Profile): mean, standard deviation, kurtosis, skewness
    - DM-SNR (Dispersion Measure - Signal-to-Noise Ratio): mean, standard deviation, kurtosis, skewness
- **Target**: `Class` (binary: `0` or `1`)


## Project features
- Data cleaning (removing irrelevant columns)
- Feature selection
- Feature scaling 
- Train/validation/test split
- Class balancing with class_weight
- Batch Normalization & L2 regularization
- Hyperparameter tuning with Keras Tuner + GridSearchCV
- Evaluation metrics:
  - Accuracy
  - ROC-AUC
  - Confusion Matrix (visualized with Seaborn/Matplotlib)


Model achieved ~97% accuracy
