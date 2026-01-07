# High-Energy Physics Data Analysis using Python
## Overview

This project explores a small but realistic data analysis workflow inspired by high-energy physics experiments. The goal is to work with event-based particle collision data and practice the kind of data cleaning, selection, and statistical analysis that is common in experimental physics. The focus is on clarity, correctness, and reproducibility rather than complex models.

## Dataset

The dataset used here is a synthetic particle event dataset designed to resemble detector output from particle physics experiments. Each event contains measurements such as energy, momentum components, particle charge, and particle type. To reflect real experimental conditions, the data includes missing values, unphysical measurements, and measurement noise similar to what is typically encountered in detector data.

## Analysis Approach

The analysis follows a structured, research-style workflow:

- Load and inspect the raw event data

- Identify and remove unphysical values

- Handle missing or incomplete measurements

- Compute derived quantities such as momentum magnitude

- Apply simple, physics-motivated event selection criteria

- Simulate detector resolution effects on energy measurements

- Compare energy and momentum distributions across particle types

- Visualize results using clear and interpretable plots

Each step is explained in the notebook to make the reasoning behind the analysis easy to follow.

## Tools Used

- Python

- NumPy

- Pandas

- Matplotlib

- Jupyter Notebook

- Git

## Reproducibility

The full analysis is contained in a single Jupyter notebook and can be run from start to finish. Random seeds are fixed where applicable, and intermediate processed data are saved to ensure that the results can be reproduced consistently on different systems.

## Results and Observations

After cleaning and selecting events, the energy and momentum distributions show clear and expected differences between particle types. Simulated detector resolution effects introduce a broadening of the energy measurements while preserving the overall distribution trends. These behaviors are consistent with what is typically observed in experimental particle physics analyses.

## Project Structure

hep-data-analysis/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── analysis.ipynb
├── src/
├── README.md
└── requirements.txt
