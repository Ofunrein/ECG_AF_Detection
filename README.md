# ECG AF Detection

This repository contains a deep-learning ECG classification workflow focused on atrial fibrillation detection from single-lead ECG recordings. The primary artifact is a notebook that covers data loading, preprocessing, modeling, evaluation, and comparison of sequence-modeling approaches.

## Project Scope

- Domain: ECG rhythm classification
- Primary target class: atrial fibrillation (AF)
- Label set: 4-way rhythm/noise classification
- Model family: convolutional and recurrent neural networks
- Output type: reproducible notebook with metrics and visual diagnostics

## Files

- `ECG_AF_Detection.ipynb`: full implementation and analysis notebook

## Workflow Overview

The notebook is structured to move from raw data to validated model results:
- dataset overview and class inspection
- waveform preprocessing and fixed-length input shaping
- train/validation/test split strategy
- CNN baseline model build and training
- CNN+RNN/LSTM model build and training
- confusion matrix and score-based evaluation
- model comparison and interpretation

## Runtime Guidance

Use Google Colab with a GPU runtime for fastest execution and easiest dependency setup.

1. Open Google Colab.
2. Upload `ECG_AF_Detection.ipynb`.
3. Select a GPU runtime.
4. Run all cells in order.
