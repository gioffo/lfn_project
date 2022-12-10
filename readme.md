# Hi

## Project structure

* **`/data/`** -> Folder for the datasets, before(.csv, .tar.gz, etc..) and after (.graphml) preprocessing
* **`preprocessing.ipynb`** -> Preprocessing of the datasets
* **`run_experiment.ipynb`** -> Compute counts and significance of motifs in the datasets and save the results as binary files.
* **`compare_z_scores.ipynb`** -> One on one comparison of motifs
* **`example.ipynb`** -> Example experiment on Escherichia Coli dataset
* **`test_plots.ipynb`** -> Plotting tests
* **`test*.ipynb`** -> Other tests :)

## Installation and run

Hopefully this works:

```Bash
conda create --name fl-gt --file requirements.txt
conda activate fl-gt
jupyter notebook
```
