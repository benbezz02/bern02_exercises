# BERN02 Excercises

Reproducible workflows for two data-analysis exercises: a linear regression analysis of bird count data, and a generalized linear regression (GLR) analysis of pollution data. This repository was created as coursework for the BERN02 module and is structured to be re-run, inspected, and reused by others.

## Contents

| File / folder | Description |
|---|---|
| `regression.ipynb` | Exercise: linear regression analysis (bird count data) |
| `glr.ipynb` | Exercise: generalized linear regression analysis (pollution data) |
| `hierarcal_models.py.ipynb` | Exercise: Hierarchical Models and Testing |
| `unsupervised_learning.ipynb` | Exercise: Unsupervised Learning |
| `visualisation.ipynb` | Exercise: Visualisation |
| `data/bird_count.csv` | Full bird count dataset |
| `data/bird_count_samples.csv` | Sampled subset of the bird count dataset |
| `data/pollution_cleaneddata.csv` | Cleaned pollution dataset used in `glr.ipynb` |
| `data/pollution_metadata.txt` | Metadata describing the pollution dataset's fields, units, and provenance |
| `data/towelData.csv` | Dataset of Towel Experiments |

## Requirements

- Python 3.11 (developed and tested with this version; other 3.10+ versions
  will likely work but are untested)
- All Python package dependencies are pinned in `requirements.txt`

## Setup

```bash
# create and activate a virtual environment
python -m venv venv
source venv/bin/activate 

# install pinned dependencies
pip install -r requirements.txt
```

Then open `regression.ipynb` or `glr.ipynb` and run all cells top to bottom.


