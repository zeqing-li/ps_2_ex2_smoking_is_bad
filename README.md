# PS 2, ex 2 Smoking is bad

# Setup

To install the required packages, run the following command in the terminal:

```bash
conda env create -f environment.yml
conda activate smoke
```

## Pre-commit

This repository uses pre-commit to run some checks before each commit. To install pre-commit, run:

```bash
pre-commit install
```

To run the checks manually, run:

```bash
pre-commit run --all-files
```
