# Latent Variable Proximal Point Experiments

## Try the contact example online

**Run the complete LVPP contact example directly in your browser—no installation required.**

[![Launch the contact example on Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/m-reichelt/latent_variable/HEAD?urlpath=lab/tree/notebooks/contact2d.ipynb)

Click the badge to open [`contact2d.ipynb`](notebooks/contact2d.ipynb) in a ready-to-use JupyterLab environment. The first launch can take several minutes while Binder builds the environment.

This repository is a small experimental workspace for exploring and illustrating the latent variable proximal point (LVPP) method for variational problems with inequality constraints. It is intended for hands-on numerical experiments and learning rather than as a production-ready or comprehensive implementation.

The method is introduced in:

> Jørgen S. Dokken, Patrick E. Farrell, Brendan Keith, Ioannis P. A. Papadopoulos, and Thomas M. Surowiec, [*The latent variable proximal point algorithm for variational problems with inequality constraints*](https://doi.org/10.1016/j.cma.2025.118181), *Computer Methods in Applied Mechanics and Engineering* **445** (2025), 118181. ([arXiv:2503.05672](https://arxiv.org/abs/2503.05672))

## Contact example

[`notebooks/contact2d.ipynb`](notebooks/contact2d.ipynb) studies two-dimensional unilateral contact in plane-strain linear elasticity. It connects the constrained energy minimization problem with its Lagrangian saddle-point formulation and implements the corresponding LVPP iteration with NGSolve.

## License

This repository is licensed under the [GNU Lesser General Public License v2.1](LICENSE).
