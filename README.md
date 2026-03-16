# Foundation Model for Predictive Maintenance

**TFM MULCIA** — Foundation Model for Predictive Maintenance using Federated Learning

## Overview

This project explores the application of **Foundation Models** and **Federated Learning** to predictive maintenance tasks, using the **PHMD (PHM Dataset)** benchmark. The goal is to build a generalizable model capable of learning degradation patterns across heterogeneous industrial assets without centralizing raw sensor data.

## Project Structure

```
fm-predictive-maintenance/
├── exploration/         # Exploratory analysis of PHMD datasets
├── data_pipeline/       # Data loading, preprocessing and feature engineering
├── models/              # Foundation Model architecture
├── training/            # Training scripts (centralized & federated)
├── data/                # Downloaded datasets (not tracked by git)
└── results/             # Plots, logs and evaluation outputs
    └── plots/
```

## Datasets

Uses datasets from the [PHMD library](https://github.com/nicolasluarte/phmd), a unified interface for public predictive maintenance benchmarks (CMAPSS, FEMTO, XJTU-SY, etc.).

## Requirements

```bash
pip install -r requirements.txt
```

## Status

Work in progress — TFM MULCIA 2025/2026.
