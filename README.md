# CafChem Teaching Notebooks

Colab notebooks for chemistry and AI teaching courses.

## Running the notebooks (Anaconda on Windows)

One-time setup, in the **Anaconda Prompt (anaconda3)** app (Start menu, type "Anaconda Prompt"):

```
conda install -c conda-forge rdkit meeko py3dmol gemmi scipy dimorphite-dl
```

This takes a few minutes (longer the first time - the default conda channel does not carry these packages, so they come from the community conda-forge collection). Then open Jupyter the usual way (Anaconda Navigator or `jupyter lab`), open a notebook, and run the cells from the top - the first cell will see the packages are installed and skip pip, so nothing stalls.

Or use **Colab** instead: click the "Open in Colab" badge at the top of a notebook. Nothing to install - Colab has everything except a couple of small packages, which its first cell installs quickly.

## CH3CO1/CH4PA1: Python catch-up

[notebooks/PyCatchUp_CafChem.ipynb](notebooks/PyCatchUp_CafChem.ipynb)

## CH3CO1/CH4PA1: Week 1 - a simple agent

[notebooks/HF_agent_step0_CafChem.ipynb](notebooks/HF_agent_step0_CafChem.ipynb)

## CH3CO1/CH4PA1: Week 2 - SMILES and RDKit

[notebooks/SMILES_primer_CafChem.ipynb](notebooks/SMILES_primer_CafChem.ipynb)

[notebooks/RDKit_intro_CafChem.ipynb](notebooks/RDKit_intro_CafChem.ipynb)

## CH3CO1/CH4PA1: Mini Project 1 - Dataset

[Mini Project 1 Dataset](https://github.com/MauricioCafiero/CafChem_Teaching_Notebooks/blob/main/project_molecules.txt)

## CH3CO1/CH4PA1: Week 5 - Featurizing and Machine Learning

[notebooks/Featurizing_SKLearn_CafChem](https://github.com/MauricioCafiero/CafChem_Teaching_Notebooks/blob/main/notebooks/Featurizing_SKLearn_CafChem.ipynb)

[dataset for week 5](https://github.com/MauricioCafiero/CafChem_Teaching_Notebooks/blob/main/delaney.csv)

## CH3PR1: Computational drug docking practical

[notebooks/Vina_dock_3D_CafChem.ipynb](notebooks/Vina_dock_3D_CafChem.ipynb)

[CH3PR1 docking receptors](notebooks/CH3PR1_receptors.md) - the six receptor files used by the notebook, as a separate page with a zip download and direct links. The notebook downloads the files automatically; the page is for browsing or manual download.
