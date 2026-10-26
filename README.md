# CafChem Teaching Notebooks

Colab notebooks for chemistry and AI teaching courses.

## Running the notebooks

The easy option is **Colab**: click the "Open in Colab" badge at the top of a notebook - no installation needed.

Running locally: just run the notebook cells from the top - the first cell installs what's needed (once per environment; it can take a few minutes on Windows). If that install stalls on Windows/Anaconda, run this once in the **Anaconda Prompt (anaconda3)** and then open the notebook in the normal (base) environment:

```
conda install -c conda-forge rdkit meeko py3dmol gemmi scipy dimorphite-dl
```

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
