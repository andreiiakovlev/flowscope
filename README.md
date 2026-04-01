# flowscope.ai ([link](https://github.com/andreiiakovlev/flowscope/tree/main))

## Overview
Flowscope is an analytical pipeline designed to predict **visual micro-trends** and estimate feature-level marginal performance lift in social media ecosystems. Our engine isolates the expected impact of specific visual features from baseline entity variance.

## Statistical Methodology
The predictive engine relies on extracting signal from highly noisy, cross-sectional social data:
- Micro-Community Clustering: Ingests unstructured tags and maps target accounts to latent social clusters, defining the local cross-sectional universe.
- Fixed-Effects Residual Analysis: Controls for baseline account exposure (e.g., average viewership). This isolates the residual engagement metrics.
Feature Lift Prediction: Maps visual features (e.g., has glasses, something soft in the frame) to the residual variance. The model predicts the expected view multiplier (uplift) for out-of-sample posts, outputting point estimates with rigorous 95% prediction intervals.

**Co-founders:** Andrei Iakovlev, Alexander Lobashev, Dmitry Magas'.

**Contact us:** contact@flowscope.ai
