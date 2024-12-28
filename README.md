# Genome_SSR_analysis_FYP
This repository contains the code and resources used in the analysis of extracted SSRs in bacterial genomes

**"Investigating the Relationship Between Simple Sequence Repeats and GC Content in Bacterial Genomes"**

Author: Amberlie Corbett-Jones, Department of Biology, University of Bath 

## Overview
This project involves the analysis of bacterial genome sequences to study the distribution of Simple Sequence Repeats (SSRs) and their relationship with GC content. The repository includes scripts for:
- Downloading and extracting zip files from the NCBI database
- Extracting the SSRs
- Calculating overall GC content and SSR GC content
- Identifying and categorising SSRs
- Control variables

## Set up

### Prerequisites
To run the code, you will need:
- Genome sequences downloaded from NCBI Database in FASTA format as ZIP files (https://www.ncbi.nlm.nih.gov/datasets/genome/)
  The following link contains the one hundred genome files used in this project: https://github.com/amberlie03/Input-Files
- Python 3.x (any version that supports Jupyter Notebook)
- Jupyter Notebook (or JupyterLab)

Required libraries:
- File handling using `zipfile`, `os`, and `shutil`
- Data preprocessing using `pandas` and `numpy`
- Regular expression `re`
- Read GenBank using `bio from seqI0`
- Data visulaisation using `csv`, `matplotlib`, and `seaborn`
- Model training and evaluation using `scikit-learn`
- Statistical analysis using `scipy.stats`

### Clone the Repository
To get started, the repository must be cloned to the local machine:

```bash
git clone https://github.com/amberlie03/Genome-SSR-Analysis-FYP
```

### Summary 
First, clone the repository and install the required libraries using `pip install`. Then, set up a virtual environment and adjust code to fit with own directories. 
For example, replace `zip_path = '/Path/to/downloaded/zipfiles.zip'` with the location where the input genome files are saved. 

Zip file and SSR extraction code: https://github.com/amberlie03/Genome-SSR-Analysis-FYP/blob/main/Extracting_SSRs.ipynb

The given code was repeated for each genome and compiled into one large csv: https://github.com/amberlie03/Genome-SSR-Analysis-FYP/blob/main/FYP_data.csv

Extracted SSRs were extracted and compiled into text files for each genome: https://github.com/amberlie03/Genome-SSR-Analysis-FYP/blob/main/Extracted_SSRs.zip

Control variables in this project consisted of five random genomes, randomised one hundred times and SSRs extracted each iteration: https://github.com/amberlie03/Genome-SSR-Analysis-FYP/blob/main/Controls.ipynb
  Control data results csv: 

Data analysis involved identifying and categorising SSRs, visualising the data and performing statistical tests: https://github.com/amberlie03/Genome-SSR-Analysis-FYP/blob/main/Data%20Analysis.ipynb 
