# Temporal Attention LSTM (TA-LSTM)

## Overview

This folder contains the implementation of the Temporal Attention Long Short-Term Memory (TA-LSTM) model developed for predicting key process variables in the Ethyl Propionate reactive distillation process.

## Model Information

- Architecture: Temporal Attention Long Short-Term Memory (TA-LSTM)
- Framework: TensorFlow / Keras
- Input Features: 36
- Output Variables: 2

### Outputs

- Ethyl Propionate Mole Fraction
- Ethanol Mole Fraction

## Files

- TALSTM_EthylPropionate_Soft_Sensor.ipynb
- Architecture.png (Optional)

The TA-LSTM model incorporates a temporal attention mechanism that dynamically focuses on the most relevant time steps during prediction, improving the modeling of nonlinear dynamic behavior in reactive distillation systems.
