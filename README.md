This repository contains the complete implementation of the Fern model from:

Qilin Wang. Ellipsoidal Time Series Forecasting. ICML 2026.
arXiv:2505.17370.

It includes the core model code, training pipeline, and evaluation scripts for the shock-table experiments in the paper. Extended shock-table analysis and additional statistics are provided in the accompanying Markdown files.

The anonymous GitHub link in the paper also includes a Jupyter notebook demonstrating the training workflow used to reproduce the shock-table results.

The full benchmark and data-generation database will be released as a separate Python module with a reproducible setup. That module will contain the dynamical-system definitions, noise/intervention protocols, configuration utilities, and experiment-generation tools used across the Fern experiments.

A mixed Rust/Python implementation is currently in progress, aimed at faster data generation, reproducible orchestration, and deployment-oriented workflows. This migration is ongoing and will be released separately once stable.
