# Home-Credit-Default-Risk

## Requirements

- Python 3.12
- numpy 2.5.4
- pandas 3.0.6
- scikit-learn 1.9.1
- lightgbm 4.7.0
- matplotlib 3.11.2
- seaborn 0.13.2
- jupyter / nbconvert (to run the notebook)

Installation:

    pip install numpy pandas scikit-learn lightgbm matplotlib seaborn jupyter

## Reproduction

1. Place the `input/` folder (train.csv, test.csv, sample_submission.csv) next to the notebook.
2. Run all cells of `tutorial.ipynb` (Run all).
3. The file `output/submission.csv` is generated automatically.

The random seed is fixed (`SEED = 42`), so results are reproducible.
No external data is used.
