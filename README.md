# Ticket Classification Using LSTM, GRU and SRN — 2026 Reproduction

This repository contains the **2026 reproduction** of my previous ticket classification project using Long Short-Term Memory (LSTM), Gated Recurrent Unit (GRU), and Simple Recurrent Network (SRN) models.

The original experiments were conducted in 2025 as part of my research and publication. This repository was created to rerun the original methodology in the 2026 software environment and examine the reproducibility of the results.

## Models

The following models are reproduced:

* LSTM
* LSTM with tuned hyperparameters
* GRU
* GRU with tuned hyperparameters
* SRN

Hyperparameter tuning for LSTM and GRU is performed using `GridSearchCV` and `SciKeras`.

## Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC

Training and test results are reported for model performance comparison.

## Software Environment

The 2026 reproduction uses:

* TensorFlow 2.20.0
* Keras 3.13.2
* SciKeras 0.13.0
* scikit-learn 1.5.2
* Python
* NumPy
* Pandas

The software environment differs from the environment used for the original experiments.

## Results

The reproduced results may differ slightly from the results reported in the original research.

For example, the tuned LSTM achieved a test accuracy of **93.55%** in the original experiment, while the 2026 reproduction achieved **92.55%**.

| Model        | Original Test Accuracy | 2026 Reproduction |
| ------------ | ---------------------: | ----------------: |
| LSTM (Tuned) |                 93.55% |            92.59% |
| LSTM         |                      — |            92.40% |
| GRU          |                      — |            92.37% |
| SRN          |                      — |            92.09% |
| GRU (Tuned)  |                      — |            92.00% |


The remaining results will be added after completing the reproduction experiments.

## Reproducibility Note

Deep learning results are not always identical between different executions or software environments. Differences may occur because of random weight initialisation, data shuffling, library versions, hardware, and changes in TensorFlow/Keras implementations.

The purpose of this repository is not to replace the originally published results, but to document the reproduction of the same methodology in a newer environment.

The results reported in the original repository remain the results obtained at the time of the original research and publication.

## Original Research

The original repository contains the source code and experimental results associated with the research conducted in 2025.

This repository should be considered the **2026 reproduction version** of that work.

## Author

Orapin Pakkarapanit
