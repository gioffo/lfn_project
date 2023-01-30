# Learning from Networks Project

## Project structure

* **`/data/`** -> Folder for the datasets, before(.csv, .tar.gz, etc..) and after (.graphml) preprocessing
* **`/exp_shuffles/`** -> Folder for PDA experiment result binaries
* **`/experiment/`** -> Folder for main experiment result binaries
* **`/figures/`** -> Folder for saved figures of plots
* **`/test_notebooks/`** -> Folder for the notebooks used for testing
* **`preprocessing.ipynb`** -> Preprocessing of the datasets
* **`run_experiment.ipynb`** -> Compute counts and significance of motifs in the datasets and save the results as binary files.
* **`compare_z_scores.ipynb`** -> One on one comparison of motifs
* **`read_and_plot.ipynb`** -> Batch processing and plotting
* **`example.ipynb`** -> Example experiment on Escherichia Coli dataset
* *`performance_degradation_analysis.ipynb`* -> Experiment on performance degration of `motif_significance()` when using speed-up parameters

## Installation and run

Hopefully this works:

```Bash
conda create --name fl-gt --file requirements.txt
conda activate fl-gt
jupyter notebook
```
