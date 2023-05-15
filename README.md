# Analyzing Complex Interfaces with Jupyter Notebook

This Jupyter notebook analyzes the interface between two proteins, Prot_A and Prot_B, using a multi-step analytical pipeline.
The purpose of this pipeline is to provide insights that can inform future interface redesign efforts.

### The notebook demonstrates individual steps of the pipeline for a specific use case:

- Prot_A: SARS-CoV-2 spike protein
- Prot_B: Antibody P5A-3C8
- Prot_C: ACE2
PDB entries: 6M0J and 7Z0X

### The notebook includes the following sections:

- Loading and Preprocessing Structures
- Interface Residue Identification
- Hotspot Residue Identification


## Getting Started
To use this notebook, you will need to install/download the following software:

- Jupyter Notebook
- PyMOL 
- InterfaceResidues.py

Once you have installed the necessary software, you can run the notebook and follow the steps outlined in each section. There four sections: 
- Identify and retrieve the PDB entries 6M0J and 7Z0X.
- Perform structural superimposition of the two complexes to determine the overlap of the binding interfaces using PyMOL.
![Sructural superimposition of the two complexes](https://github.com/emamars95/complexes_interface/blob/main/aligned_6M0J.png)
- Extract the interface residues in each complex using InterfaceResidues within PyMol
![Interface of the 6M0J complex](https://github.com/emamars95/complexes_interface/blob/main/6M0J_interface.png)
- Perform a comparative analysis of the interface residues of SARS-CoV-2 spike protein in the two complexes to identify important residues

The notebook also includes detailed explanations of each step and the underlying concepts and methods used.
