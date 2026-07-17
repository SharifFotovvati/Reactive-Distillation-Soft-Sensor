# Reactive Distillation Soft Sensor Using Deep Learning

## Overview

This repository presents the implementation of deep learning-based soft sensors for reactive distillation processes. Two independent case studies are investigated:

- Simulation 1: Methyl Tert-Butyl Ether (MTBE) Reactive Distillation Process
- Simulation 2: Ethyl Propionate Reactive Distillation Process

The datasets were generated using Aspen Plus steady-state simulations and Aspen Dynamics dynamic simulations. Several deep learning architectures were developed and evaluated for accurate prediction of key process variables.

---

## Repository Structure

```
Reactive-Distillation-Soft-Sensor
│
├── Simulation-1
│   ├── AspenPlus
│   ├── AspenDynamics
│   ├── Dataset
│   └── Models
│
└── Simulation-2
    ├── AspenPlus
    ├── AspenDynamics
    ├── Dataset
    └── Models
```

---

## Simulation 1

**Process**

Reactive Distillation Process for Methyl Tert-Butyl Ether (MTBE) Synthesis

### Models

- Feedforward Neural Network (FNN)
- One-Dimensional Convolutional Neural Network (CNN-1D)
- Temporal Convolutional Network (TCN)
- Transformer
- Gated Stacked Autoencoder (GSAE)
- Variable Attention LSTM (VA-LSTM)
- Self-Attention LSTM (SA-LSTM)

---

## Simulation 2

**Process**

Reactive Distillation Process for Ethyl Propionate Synthesis

### Models

- Deep Temporal Convolutional Network
- Optimized Transformer
- LSTM with Attention
- Temporal Attention LSTM
- Value Attention LSTM

---

## Software

- Aspen Plus
- Aspen Dynamics
- TensorFlow
- Keras
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- SHAP

---

## Research Area

This work combines Process Design Engineering, Process Systems Engineering, Process Simulation, and Deep Learning to develop intelligent soft sensors for reactive distillation columns.

The project integrates Aspen Plus, Aspen Dynamics, and modern deep learning architectures for accurate prediction of key process variables in nonlinear chemical processes.

---

## Author

Mahdi Sharif Fotovvati

M.Sc. Student

Department of Chemical Engineering

Process Design Engineering

Sahand University of Technology

Research Interests:
- Process Systems Engineering
- Reactive Distillation
- Process Design
- Process Modeling and Simulation
- Soft Sensors
- Deep Learning
- Artificial Intelligence in Chemical Engineering
