# High-Energy Physics Data Analysis using Python

## Overview
This project focuses on analyzing particle collision event data using Python. It is inspired by the type of data analysis workflows used in high-energy physics experiments. The main aim of the project is to practice working with event-based scientific data, handle detector-related imperfections, and perform basic statistical analysis in a clear and reproducible way.

## Dataset
The dataset used in this project is a synthetic particle event dataset designed to resemble detector output from particle physics experiments. Each event includes measurements such as energy, momentum components, charge, and particle type. To make the analysis realistic, the dataset includes missing values, unphysical measurements, and measurement uncertainty similar to what is seen in real experimental data.

## Approach
The analysis follows a step-by-step workflow similar to a small research study:
- Load and inspect raw event data  
- Remove unphysical values and handle missing measurements  
- Compute derived quantities such as momentum magnitude  
- Apply simple physics-inspired event selection criteria  
- Simulate detector resolution effects on energy measurements  
- Compare energy and momentum distributions across particle types  
- Visualize results using clear and interpretable plots  

## Tools Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Jupyter Notebook  
- Git  

## Reproducibility
The full analysis is contained in a single Jupyter notebook that can be run from start to finish. Random seeds are fixed where needed, and processed data files are saved to ensure the results can be reproduced consistently.

## Results and Observations
After cleaning and selecting events, the energy and momentum distributions show clear differences between particle types. The effect of detector resolution introduces expected broadening in energy measurements without changing the overall trends. These results are consistent with typical behavior seen in experimental particle physics data analysis.

## Project Structure
hep-data-analysis/
├── data/
│ ├── raw/
│ └── processed/
├── notebooks/
│ └── analysis.ipynb
├── src/
├── README.md
└── requirements.txt