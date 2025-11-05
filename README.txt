
# EEG Mini Viewer

A minimal example project for loading and visualising EEG data locally using MNE-Python and common scientific Python tools.

Project notebook
----------------
The main project file is the Jupyter notebook at `Notebooks/eeg-mini-viewer.ipynb` — open this notebook to explore the demo, visualisations, and example code.

Highlights
----------
- Demonstrates how to load, preprocess, and visualise sample EEG recordings with MNE-Python.
- Small, reproducible example intended for learning and experimentation.

Prerequisites
-------------
- Python 3.10+ (the repo was tested with Python 3.11).
- A conda or virtualenv-based environment is recommended.
- See `requirements.txt` for Python package dependencies.

Quick setup (conda)
--------------------
1. Create and activate a conda environment:

   ```bash
   conda create -n eeg-mini python=3.11 -y
   conda activate eeg-mini
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   ```

Quick setup (venv + pip)
------------------------
1. Create a venv and install dependencies with pip:

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   ```

Run the notebook
----------------
Start Jupyter and open the project notebook:

```bash
jupyter lab    # or: jupyter notebook
# then open Notebooks/eeg-mini-viewer.ipynb in your browser
```

Notes
-----
- The notebook contains runnable cells that walk through loading example EEG data and plotting it with MNE.
- If you run into package issues, ensure the Python version matches the one used for creating `requirements.txt` and reinstall dependencies in a fresh environment.

Contributing
------------
Small fixes, improved examples, and additional notebooks are welcome — open an issue or a PR.

License & contact
-----------------
This repository uses no specific license file; For questions, contact the repository owner.

Files of interest
-----------------
- `requirements.txt` — Python dependencies
- `Notebooks/eeg-mini-viewer.ipynb` — main project notebook

Enjoy exploring EEG visualisations!
