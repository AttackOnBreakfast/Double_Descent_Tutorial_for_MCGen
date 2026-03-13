# Double Descent in High-Energy Physics

This repository contains a tutorial notebook exploring the **Double Descent** phenomenon within the context of High-Energy Physics (HEP), specifically focusing on Parton Distribution Function (PDF) fitting using `LHAPDF`.

## Overview
Increasing model complexity is traditionally expected to lead to overfitting. However, modern models often exhibit "Double Descent," where test error drops again in the highly overparameterized regime. This tutorial identifies, interprets, and ablates the sources of this behavior using spectral analysis.

## Key Features
- **Toy Example:** Polynomial regression demonstrating the interpolation peak.
- **Physics Application:** Realistic PDF fitting using the `NNPDF31` set via LHAPDF.
- **Ablation Study:** Testing the "Small Singular Value" hypothesis by implementing spectral cutoffs.

## Installation
To run this notebook locally, ensure you have `LHAPDF` installed (requires C++ headers) and install the Python dependencies:

```bash
pip install -r requirements.txt