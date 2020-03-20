![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
# biopython-coronavirus

A tutorial jupyter notebook illustrating how we can use [Biopython](https://github.com/biopython/biopython) to identity and perform some basic characterization of a coronavirus genome sequence.

## Viewing the notebook

Simply open the notebook link:
XXX

You may alternatively view the notebook via [nbviewer](https://nbviewer.jupyter.org/):
XXX

## Viewing via Google collab notebook

TO DO

## Installing the notebook locally

First clone this repository:
```
git clone https://github.com/chris-rands/biopython-coronavirus
```

You need Python (version 3.6 or higher) with the `jupyter` and `biopython` modules. If you do not already have these Python modules, I reccomend one of two options:

1) Installation via pip

```
pip3 install jupyter biopython
```

For installation without root access add the `--user` flag.

2) Installation via conda
  
```
conda env create -f biopython-coronavirus-environment.yml
conda activate biopython-coronavirus
```

## Running the notebook locally

You can open the notebook as follows:
```
jupyter-notebook biopython-coronavirus-notebook.ipynb
```
