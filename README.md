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

## Set up

### Prerequisites
To run the code, you will need:
- Genome sequences downloaded from NCBI Database in FASTA format as ZIP files (https://www.ncbi.nlm.nih.gov/datasets/genome/)
  The following link contains the one hundred genome files used in this project: https://github.com/amberlie03/Input-Files 
- Python 3.x (any version that supports Jupyter Notebook)
- Jupyter Notebook (or JupyterLab)

Required libraries:
- File handling using 'zipfile', 'os', and 'shutil'
- Data preprocessing using 'pandas' and 'numpy'
- Regular expression 're'
- Read GenBank using 'bio from seqI0'
- Data visulaisation using 'csv', 'matplotlib', and 'seaborn'
- Model trainign and evaluation using 'scikit-learn'
- Statistical analysis using 'scipy.stats'

### Clone the Repository
To get started, the repository must be cloned to the local machine:

git clone https://github.com/amberlie03/Genome-SSR-Analysis-FYP

### Summary 
Firstly clone the repository, then install the required libraries using `pip`. Then set up a virtual environment to run code. 
 
