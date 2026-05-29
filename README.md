This repository is the ICML 2026 artifact for Ellipsoidal Time Series Forecasting.

Qilin Wang. Ellipsoidal Time Series Forecasting. ICML 2026.
arXiv:2505.17370.
   
Fern is a long-horizon time-series forecasting model that represents future predictions through ellipsoidal spectral maps. Instead of predicting only a future mean trajectory, Fern learns a local geometric map that stretches, rotates, and translates a Gaussian source into forecast patches. This gives both predictions and interpretable diagnostics such as local stretching, spectral radius, and volume change.

The ICML paper argues that forecasting models should be tested not only on average benchmark accuracy, but also on controlled failure modes: chaos, non-stationary shocks, regime changes, and data artifacts. This repository preserves the code, logs, metrics, and protocol notes behind the reported ICML experiments.

# What This Repository Is

This repository is a paper artifact for the ICML 2026 camera-ready version of:

Ellipsoidal Time Series Forecasting
Qilin Wang, ICML 2026

It contains or will contain:

implementation code used for the ICML paper;
synthetic dynamics and shock-generation code used in the controlled benchmark;
archived metrics and training logs for the reported experiments;
configuration records and protocol notes for the shock table, detailed tables, ablations, and compute-footprint table;
figure/table artifacts used to support the paper.

The purpose of this repository is to make the ICML results inspectable, auditable, and easier to build upon.

# What This Repository Is Not

This repository is not the actively maintained long-term Fern package.

It is also not a promise of one-command, bit-exact reproduction of every number in the paper from a refactored code path. Some reported experiments were run under protocol-specific implementation snapshots. Later refactors may change layer construction order, initialization order, or floating-point operation order, which can change exact training trajectories.

For the ICML paper, the archived metrics, logs, configuration records, and protocol notes are the authoritative record for the reported numbers.

A cleaner standalone Python package for the synthetic benchmark generators, together with a more complete Fern research implementation, is planned for release soon. The goal is to separate the reusable benchmark/model code from this archival ICML artifact.

Repository Status

This repository currently serves two roles:

ICML 2026 Artifact
A stable release associated with the camera-ready paper.
Bridge to Future Releases
A temporary public home for the reported implementation and benchmark code before the cleaner standalone modules are released.

The future release plan is:

a standalone Python module for the synthetic dynamical systems and controlled shock benchmark;
a cleaner Fern implementation intended for new research and easier extension;
eventually, a faster Python/Rust or hybrid implementation for scalable data generation and experiment pipelines.
