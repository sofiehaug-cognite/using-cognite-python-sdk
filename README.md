# Using Cognite Python SDK

A step-by-step guide with practical examples and code for using the Cognite Python SDK.

https://cognite-docs.readthedocs-hosted.com/projects/cognite-sdk-python/en/latest/

## Getting Started

### Prerequisites

- Python 3.11+
- [Poetry](https://python-poetry.org/) (recommended) or pip

### 1. Clone the repository

```bash
git clone https://github.com/cognitedata/using-cognite-python-sdk.git
cd using-cognite-python-sdk
```

### 2. Install dependencies

We recommend using Poetry to manage your Python virtual environment:

```bash
poetry install
```

This installs the dependencies defined in `pyproject.toml` and creates a virtual environment in the project folder.

### 3. Run the notebooks

Open the repo in your IDE (e.g., VS Code) and start exploring the Jupyter notebooks.

> **Note:** You may need to select the Poetry virtual environment as your kernel.

## Alternative: pip installation

If you prefer not to use Poetry, you can install the SDK directly with pip:

```bash
pip install "cognite-sdk[pandas]"
```
