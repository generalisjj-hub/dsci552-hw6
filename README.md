# DSCI 552 Homework 6

Open `notebook/Jiang_Jun_HW6.ipynb` for the completed answers, code, and outputs. A 12-page printable version is at `output/pdf/Jiang_Jun_HW6.pdf`. The original APS training and test files are in `data/`.

With Python 3.12, from the repository root:

```sh
uv sync --frozen
uv run jupyter nbconvert --to notebook --execute --inplace notebook/Jiang_Jun_HW6.ipynb --ExecutePreprocessor.timeout=3600
```

Alternatively, install `requirements.txt` into a Python 3.12 environment and run the notebook with that environment's Jupyter kernel. Full-data SMOTE and cross-validation may take substantial time. XGBoost on macOS may require the OpenMP runtime (`brew install libomp`).
