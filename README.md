## Overview
This repository contains three Jupyter notebooks related to the manuscript titled:
**"Genes required by Mycobacterium tuberculosis to survive transmission"** by Mishra et al.

The notebooks cover two analyses:
1. **Transmission Survival Genome of Mtb**: Pooled CRISPRi library results, generating number of significant differences (NOSD) counts.
2. **Proteome Analysis**: Hydrophilicity index, glycine content, and intrinsic disorder regions analysis across the Mtb proteome.

## How to Use
To run the notebooks:
1. Clone the repository:


   ```bash
   git clone https://github.com/richiam16/MAF_Nathan.git
   ```

2. **Create a new Conda environment** (recommended):
   ```bash
   conda create --name mtb_repo_env python=3.8
   conda activate mtb_repo_env
   ```

3. Install required libraries using `pip` or `conda`:
   ```bash
   pip install -r requirements.txt
   ```

   OR, if using conda for Biopython and other specific packages:
   ```bash
   conda install pandas tqdm numpy matplotlib seaborn umap-learn hvplot holoviews bokeh biopython
   ```

4. Open the notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```

5. Follow the documented steps in each notebook to reproduce the analyses.

## System Requirements
- **Python**: 3.8+
- **Jupyter Notebook**: or Google Colab
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
   - biopython
   - notebook or jupyterlab

## Notebooks Overview
- `EDA_MAGECK.ipynb`: Exploratory data analysis of input pooled CRISPRi datasets processed with MAGECK.
- `essentiality_counts_MAGECK.ipynb`: Generates the number of significant differences (NOSD) metric for each gene across all modeled stages of infection. 
- `Hydrophilicity_IDRs_Glyince_Analysis.ipynb`: Analysis of hydrophilicity index and glycine content + Intrinsically disordered regions analysis.

## License
MIT License.