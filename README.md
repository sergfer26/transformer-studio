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

The current environment is inferred from the checked-in notebook code and includes:

- `torch`
- `torchvision`
- `numpy`
- `matplotlib`
- `jupyterlab`
- `ipykernel`

The `Fine_Tune_BERT_for_Text_Classification_with_TensorFlow.ipynb` notebook is currently empty in this repository, so TensorFlow or Hugging Face packages were not added yet.
