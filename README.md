[![DOI](https://zenodo.org/badge/1024530046.svg)](https://doi.org/10.5281/zenodo.16338034)


# PaleoHD:High Resolution Paleoclimate Reconstructions

## Overview

PaleoHD is a collection of Jupyter Notebooks and workflows designed to generate climate field reconstructions and downscale them to obtain high-resolution map of key environmental variables that can be used in agriculture modeling. 

The downscaling is achieved using deep learning methods, particularly, diffusion models.

## Feature

* Reproducible Jupyter notebooks for each stage of the workflow

* Tools for visualizing and evaluation climate field reconstructions and downscaled outputs.

* Integration with deep learning models

* Outputs tailored for agriculture modeling

## Getting started

To clone and explore the notebooks:

```
git clone https://github.com/khider/paleoHD.git
cd PaleoHD
```

## Repository Organization

paleoHD/
│
├── notebooks/                              # Jupyter notebooks organized by stage
│   ├── DataAssimilation                    # Workflows for data assimilation using the cfr workshop
│       ├── 01_ProxyAssembly.ipynb
│       └── 02_Data_assimilation.ipynb
│       └── 03_a_data_validation_.ipynb
│       └── 03_b_data_comparison_.ipynb
│   ├── DataComparison                      #Comparison among paleo products and to instrumental records
└── README.md                               # Information pertinent to the project
└── LICENSE                                 # License information
└── citation.cff                            # citation information
└── environment.yml                         # computational environment     
