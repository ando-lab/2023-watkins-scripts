# 2023-watkins-scripts

This is a demo to show how the 4915 MetH Alphafold predictions were analyzed in our paper [Watkins *et al* 2023](https://www.biorxiv.org/content/10.1101/2023.02.11.528079v1)

The codes are written by Haoyue Wang.
## Contents
- Four Jupyter notebooks.
- The required files are also attached. Note that the 4915 pdb files are provided as a .zip file. You can download it to test. The code to directly download the structures from the deepmind database is also provided. 
## Instructions for use
In order to run the code successfully, creating a new conda environment with requied dependencies is suggested:
```python
conda create --name MetH_AF_analysis python=3.8
conda activate MetH_AF_analysis
conda install -c conda-forge pandas jupyterlab matplotlib
conda install -c conda-forge -c schrodinger pymol-bundle
```