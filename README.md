# Protein Localisation Prediction

This repository contains the code and accompanying report to build a model to predict where a protein resides in a cell. 

The dataset used to build this model is composed of FASTA files containing the amino acid sequence of a protein. Additionally, the dataset contains the location of each protein. The dataset is composed of: 
- 3,004 cytosolic sequences
- 1,299 mitochondrial sequences
- 3,314 nucleic sequences
- 1,605 secreted or extracellular sequences 
- 2,002 prokaryotic sequences

The prokaryotic sequences were added as they can contaminate sequencing samples but this model focused on predicting the cytosolic, mitochondrial, nucleic and secreted or extracellular sequences with a high accuracy. 

The dataset used has not been included in this repository, therefore if you would like to run this code please reach out. 

The repository contains two files:
- Report.pdf: This is the report which details the findings of this project and also contains a code overview in the appendix. It is recommended to skim through the report before looking at the code as this will help to understand the code. 
- Protein_Localisation_Prediction.ipynb: This notebook contains all of the code used to build the model. 

If you have any questions, please feel free to reach out. 

