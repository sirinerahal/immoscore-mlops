# immoscore-mlops

Reproducible ML pipeline for ImmoScore, a house price prediction project.

## Installation

```bash
git clone https://github.com/sirinerahal/immoscore-mlops.git
cd immoscore-mlops
python -m venv .venv
.venv\Scripts\activate        # Windows
pip install -r requirements.txt
```

## Data

The dataset is not versioned in Git. Download `train.csv` from Kaggle, rename it `data.csv`, and place it in `data/raw/`.

## Structure

- `notebooks/`: exploration only
- `data/`: datasets, ignored by Git
- `requirements.txt`: Python dependencies