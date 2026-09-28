# geomstats-breast-cancer-cell-shape-analysis

Shape analysis of biological cell shapes and phantom shapes using the Square Root Velocity (SRV) metric implemented in [Geomstats](https://geomstats.github.io/).

**Author:** Daniella I. Walter (UC Santa Barbara)

**Status:** v0.1 — in active development. This repository accompanies a manuscript in preparation for publication:

> D. I. Walter, A. Sharma, N. Miolane, R. S. Stowers. *Mapping breast cancer cell morphology via geometric statistics and machine learning.* In preparation, 2026.

## Overview

This pipeline quantifies cell shape dynamics from time-series microscopy of breast cancer cells by:

1. Extracting cell outlines as discrete closed curves
2. Representing each curve in the SRV framework and computing geodesic distances and Fréchet means on the shape space
3. Applying machine learning to the resulting geometric features to classify and cluster morphological states

Phantom (synthetic) shapes are included for validation of the metric.

## References

* Miolane et al. [Geomstats: A Python Package for Riemannian Geometry in Machine Learning](http://jmlr.org/papers/v21/19-027.html). JMLR 2020.
* Bouza et al. [Introduction to Riemannian Geometry and Geometric Statistics: from Basic Theory to Implementation with Geomstats](https://www.nowpublishers.com/article/Details/MAL-098). FnT ML 2023.
* Miolane et al. [Parametric information geometry with the package Geomstats](https://arxiv.org/abs/2211.11643). ACM TOMS 2023.
* Miolane et al. [Learning from landmarks, curves, surfaces, and shapes in Geomstats](https://arxiv.org/abs/2406.10437). ACM TOMS 2025.
* Miolane et al. [Geomstats software version](https://doi.org/10.5281/zenodo.4624475). Zenodo 2021.
