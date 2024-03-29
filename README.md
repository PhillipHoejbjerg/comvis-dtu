# 👁️ Computer Vision 👁️
The package contains functionalities for the course 02504 - Computer Vision (Spring 2023) @ DTU


## Development setup

### Environment

Create a conda environment, e.g. like below with Python 3.10:
```
conda create -n comvis-dtu python=3.10
conda activate comvis-dtu
```

Install local package in editable mode:
```
pip install -e .
```

### Pre-commit hooks

Additionally, install the `pre-commit` module for ensuring a general code structure in the remote repository.
```
pip install pre-commit
```

Install `pre-commit` on the repository with the settings specified in `.pre-commit-config.yaml`.
```
pre-commit install
```
