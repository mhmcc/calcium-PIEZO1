# calcium-PIEZO1
Jupyter notebook and Python code for the analysis of calcium influx in MCF-7 breast cancer cells via the PIEZO1 ion channel with varying cell morphology, as published in:

> So, C.L., Robitaille, M., Sadras, F. et al. Cellular geometry and epithelial-mesenchymal plasticity intersect with PIEZO1 in breast cancer cells. Commun Biol 7, 467 (2024). https://doi.org/10.1038/s42003-024-06163-z

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
Please refer to our published article for information on how to download the data.

## References
Please see the companion paper linked above for details of the methods and packages used in this code.

## Citing this code
If you use or adapt our code or methods in your research, please cite the companion paper linked above or as shown here in BibTeX format:
```
@article{so2024cellular,
  title={Cellular geometry and epithelial-mesenchymal plasticity intersect with PIEZO1 in breast cancer cells},
  author={So, Choon Leng and Robitaille, M{\'e}lanie and Sadras, Francisco and McCullough, Michael H and Milevskiy, Michael JG and Goodhill, Geoffrey J and Roberts-Thomson, Sarah J and Monteith, Gregory R},
  journal={Communications Biology},
  volume={7},
  number={1},
  pages={467},
  year={2024},
  publisher={Nature Publishing Group UK London}
}
```

## Questions
Please email michael.mccullough@anu.edu.au if you have questions about the code.
