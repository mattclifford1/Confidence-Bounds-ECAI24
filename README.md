# Learning Confidence Bounds for Classification with Imbalanced Data - ECAI 2024
Package for our paper: https://arxiv.org/abs/2407.11878


## Setting up Environment
First clone this repo
```
git clone https://github.com/mattclifford1/Confidence-Bounds-ECAI24
cd Confidence-Bounds-ECAI24
```
Then make a python env e.g. with conda
```
conda create -n CliffordECAI24 python=3.10 -y
conda activate CliffordECAI24
```
Install as editable package
```
pip install -e .
```

## Reproducing the experiments from the paper
run the file 'experiments/run_all.py'

this will save each dataset's results to experiments/results and will combine all the results into one latex table experiments/combined_table.txt


N.B. you will need to download and process and the MIMIC-ICU dataset externally as I do not have the rights to include it within this repo. Please contact me if you have any questions.
## Applying to your own classifier
TODO: write docs for this...
