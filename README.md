# Hybrid Digital Twin for CO₂ Hydrogenation to Light Olefins

## Overview

This project is being developed as part of **IITISoC 2026 (DYNAMO Track 1 – PS3)** at IIT Indore.

The objective is to develop a **Hybrid Digital Twin** for the CO₂ hydrogenation process by combining **physics-based reaction kinetics**, **machine learning**, and **Aspen Plus process simulation**. The digital twin aims to provide fast and physically consistent predictions of reactor performance under varying operating conditions.

---

## Objectives

- Develop a physics-based kinetic model for CO₂ hydrogenation.
- Generate a thermodynamically consistent synthetic kinetic dataset.
- Train a neural network surrogate model for rapid prediction.
- Predict product distribution using the Anderson–Schulz–Flory (ASF) model.
- Integrate the surrogate model with Aspen Plus to build a hybrid digital twin.

---

## Methodology

```
Operating Conditions
(T, P, H₂/CO₂)

        ↓

RWGS + Fischer–Tropsch Kinetics

        ↓

Plug Flow Reactor (ODE Solver)

        ↓

Synthetic Dataset

        ↓

Neural Network Surrogate

        ↓

ASF Product Distribution

        ↓

Aspen Plus Digital Twin
```

---

## Current Progress

- ✅ Literature Review
- ✅ Reaction Kinetics Development
- ✅ Plug Flow Reactor Model
- ✅ Synthetic Dataset Generation
- ✅ Thermodynamic Validation
- ✅ Anderson–Schulz–Flory (ASF) Product Distribution
- ✅ Neural Network Surrogate Model
- ⏳ Aspen Plus Integration
- ⏳ Complete Digital Twin Development

---

## Repository Contents

| File | Description |
|------|-------------|
| `Prj_2.ipynb` | Jupyter notebook containing kinetic model, dataset generation, ASF implementation, and neural network surrogate model |
| `co2_hydrogenation_dataset_3k.csv` | Synthetic dataset generated from the kinetic model |

---

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- SciPy
- Pandas
- Matplotlib
- Aspen Plus *(ongoing)*

---

## Team Members

- Nikhil Jakhar
- Uday Ranode
- Utkarsh Sharma
- Sohil Thakur
- Saiteja Vemula

---

## Status

🚧 Project under active development.
