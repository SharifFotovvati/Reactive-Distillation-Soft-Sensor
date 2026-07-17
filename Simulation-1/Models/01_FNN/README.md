# Feedforward Neural Network (FNN)

## Overview

This folder contains the implementation of the Feedforward Neural Network (FNN) developed for predicting key process variables in the MTBE reactive distillation process.

## Model Information

- Architecture: Feedforward Neural Network
- Framework: TensorFlow / Keras
- Input Features: 36
- Output Variables: 2

### Outputs

- Methanol Mole Fraction
- 1-Butene Mole Fraction

## Training Configuration

| Parameter | Value |
|-----------|-------|
| Optimizer | Adam |
| Learning Rate | 0.0001 |
| Loss Function | Mean Squared Error (MSE) |
| Evaluation Metric | Mean Absolute Error (MAE) |

## Files

- FNN_MTBE_Soft_Sensor.py
- Architecture.png (Optional)

This model was developed and customized for soft sensor design in reactive distillation columns.
