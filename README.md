# calcium-PIEZO1
Jupyter notebook and Python code for the analysis of calcium influx in MCF-7 breast cancer cells via the PIEZO1 ion channel with varying cell morphology, as published in:

> \[TBA on publication\]

## Overview
This repository contains:
* The Jupyter notebook `calcium_PIEZO1.ipynb` which runs the analysis and model fitting for the calcium signalling data, generating a subset of the results and  figures for our study (Fig 2g-k and Supp Fig 2).

## Installation and usage
To run the notebook:
1. Clone the repository.
1. Install the environment with `conda` using the included YAML file.
``` 
conda env create -f calcium_PIEZO1.yml
```
1. Download the data (see Data availability).
1. Set the `datapath` environment variables in the second code block of the notebook. The `datapath` must point to the file `200508_cytoo_mcf7_yoda_lean.csv`.
1. Run all cells in order.

## Data availability
The data for this project are available for download at: \[TBA on publication\]

## References
Please see the companion paper linked above for details of the methods and packages used in this code.

## Citing this code
If you use or adapt our code or methods in your research, please cite the companion paper linked above or as shown here in BibTeX format:
```
\[TBA on publication\]
```

## Questions
Please email michael.mccullough@anu.edu.au if you have questions about the code.
