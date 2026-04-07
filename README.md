# interpretable-modeling-dynamic-stabilization

Accompanying code to paper titled
Horváth et al. "Interpretable Modeling of Human Decision-Making from User Interactions in a Dynamic Stabilization Task"

# Prerequisite: tpmpy
To run the IPython notebook, first get this library from https://github.com/csapoadam/tpmpy-public
Copy its contents into the current folder.

# First initialization of project w/ uv
1. `pip install uv` (unless uv is already installed, in which case skip step 1)
2. `uv sync` (this will re-create all the dependencies based on the `pyproject.toml` and `uv.lock` files)
3. `uv run jupyter lab`

# Subsequent runs
Just navigate to this folder, and perform step 3 from above.

# Acknowledgements

This package was developed as part of project ID *2024-1.2.3-HU-RIZONT-2024-00030*

*Copyright (C) 2025 Corvinus University of Budapest*
