# MAF_Nathan

# Mycobacterium tuberculosis Transmission Survival Analysis

This repository contains the code and analysis related to the manuscript titled:  
**"Genes required by Mycobacterium tuberculosis to survive transmission"** by Mishra et al.

The code here is relevant to two main analyses:
1. **Transmission Survival Genome of Mtb**: This section includes the analysis of pooled CRISPRi library results, generating the number of significant differences (NOSDs) counts for each stage of transmission.
2. **Proteome Analysis**: This section analyzes the hydrophilicity index, glycine content, and the fraction of residues classified as intrinsically disordered regions across the Mtb proteome, exploring their relationship with essentiality counts.


## System Requirements

To run this code, the following software and libraries are required:

- **Operating System**: Linux (Ubuntu 20.04 or higher recommended)
- **Python Version**: 3.8 or higher
- **Required Libraries**:
  - pandas
  - tqdm
  - numpy
  - matplotlib
  - seaborn
  - umap-learn
  - hvplot
  - holoviews
  - bokeh
  - biopython (Bio.SeqUtils, Bio.SeqIO)

For installation, you can use `pip`:
```bash
pip install pandas tqdm numpy matplotlib seaborn umap-learn hvplot holoviews bokeh biopython


