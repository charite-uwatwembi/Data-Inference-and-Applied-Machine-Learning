# DIAML Assignment 3 — cuwatwem

This folder contains my Assignment 3 notebook, report, source data, and saved figures.

## Run it

Open Terminal in this folder and run:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m ipykernel install --user --name diaml-as3 --display-name "Python (DIAML AS3)"
```

Then open `cuwatwem_DIAML_Assignment3.ipynb` in VS Code and select **Python (DIAML AS3)** as the notebook kernel. Use **Restart & Run All** to reproduce every result.

## Folder structure

- `cuwatwem_DIAML_Assignment3.ipynb` — runnable analysis
- `data/` — all five source datasets used by the notebook
- `figures/` — graphs saved by the notebook
- `requirements.txt` — Python packages used
