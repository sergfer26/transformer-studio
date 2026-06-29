# Transformer Studio

A project for exploring and working with transformer models.

## Project Structure

- `notebooks/` - Jupyter notebooks for experimentation and analysis

## Getting Started

Create the environment with `uv`:

```bash
uv venv --python 3.12
source .venv/bin/activate
uv sync
uv run jupyter lab
```

## Formatting

This project uses `black` for both Python scripts and Jupyter notebooks.

Install or update the environment after pulling dependency changes:

```bash
uv sync
```

Format the entire repository:

```bash
uv run black .
```

Format only notebooks:

```bash
uv run black notebooks
```

Format only Python scripts:

```bash
uv run black path/to/script.py
```

`black` is installed with the `jupyter` extra, so `.ipynb` files are formatted natively in addition to `.py` files.

The current environment is inferred from the checked-in notebook code and includes:

- `black[jupyter]`
- `torch`
- `torchvision`
- `numpy`
- `matplotlib`
- `jupyterlab`
- `ipykernel`

The `Fine_Tune_BERT_for_Text_Classification_with_TensorFlow.ipynb` notebook is currently empty in this repository, so TensorFlow or Hugging Face packages were not added yet.
