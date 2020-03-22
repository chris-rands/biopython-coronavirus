![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
# biopython-coronavirus

A tutorial [Jupyter](https://jupyter.org/) Notebook illustrating how to use [Biopython](https://github.com/biopython/biopython) to identity and perform some basic characterization of a coronavirus genome sequence. The objective of this tutorial is to introduce some of the Biopython modules in an applied biological context.

## Viewing the Notebook

Simply open the [Notebook link here](https://github.com/chris-rands/biopython-coronavirus/blob/master/biopython-coronavirus-notebook.ipynb).

Alternatively view the Notebook by pasting the address into [nbviewer](https://nbviewer.jupyter.org/).

## Running the Notebook via Google collab

TO DO

## Installing the Notebook locally

First clone this repository:
```
git clone https://github.com/chris-rands/biopython-coronavirus;
cd biopython-coronavirus
```

Requires Python (version 3.6 or higher) with the `jupyter` and `biopython` modules. One of two options is recommended:

1) Installation via [pip](https://pip.pypa.io/en/stable/)

```
pip3 install jupyter biopython
```

For installation without root access add the `--user` flag.

2) Installation via [conda](https://docs.conda.io/en/latest/)
  
```
conda env create -f biopython-coronavirus-environment.yml
conda activate biopython-coronavirus
```

## Running the Notebook locally

Open the Notebook as follows:
```
jupyter-notebook biopython-coronavirus-notebook.ipynb
```

## Related Biopython resources

- [Official tutorial documentation](http://biopython.org/DIST/docs/tutorial/Tutorial.html)
- [Peter's workshop](https://github.com/peterjc/biopython_workshop)
- [Notebook tutorials](https://github.com/tiagoantao/biopython-notebook)
