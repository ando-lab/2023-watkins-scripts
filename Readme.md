# 2023-watkins-scripts

Demonstration of how the 4915 Alphafold predictions of the cobalamin-dependent methionine synthase (MetH) were analyzed in our paper [Watkins *et al* 2023](https://www.biorxiv.org/content/10.1101/2023.02.11.528079v1).

Author: Haoyue Wang 🌙

## Repository Contents
- Four Jupyter notebooks (#1 - #4).
- Two required .csv files. 
- The 4915 pdb files can be downloaded as a .zip file for testing from the release asset. The code to directly download the structures from the deepmind database is also provided (#2). 
## Instructions for use
In order to run the code successfully, creating a new conda environment with requied dependencies is suggested:
```python
conda create --name MetH_AF_analysis python=3.8
conda activate MetH_AF_analysis
conda install -c conda-forge pandas jupyterlab matplotlib
conda install -c conda-forge -c schrodinger pymol-bundle
```
## References
MB Watkins, H Wang, AA Burnim, N Ando. (2023) Conformational switching and flexibility in methionine synthase studied by small-angle X-ray scattering and cryo-electron microscopy. <i>bioRXiv</i>. https://www.biorxiv.org/content/10.1101/2023.02.11.528079v1
