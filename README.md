# Modeling progression of single cell populations through the cell cycle as a sequence of switches

Set of Python notebooks reproducing the procedures in the article 

Andrei Zinovyev, Michail Sadovsky, Laurence Calzone, Aziz Fouché, Clarice S. Groeneveld, Emmanuel Barillot, Alexander N. Gorban
[Modeling progression of single cell populations through the cell cycle as a sequence of switches](https://www.biorxiv.org/content/10.1101/2021.06.14.448414v1) 
bioRxiv 2021.06.14.448414; doi:10.1101/2021.06.14.448414

Dependencies:

1. [Stabilized ICA](https://github.com/ncaptier/Stabilized_ICA)
2. [scycle](https://github.com/csgroen/scycle)
3. [ElPiGraph](https://github.com/j-bac/elpigraph-python)
4. [skdim](https://github.com/j-bac/scikit-dimension)

## Normalization of single cell RNASeq dataset and extracting the trajectory

[Here is the notebook performing the normalization](https://github.com/auranic/CellCycleTrajectory_SegmentModel/blob/main/notebooks/CCT_Normalization_Computation.ipynb)

The loom files used in the notebook can be downloaded from [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5017357.svg)](https://doi.org/10.5281/zenodo.5017357)

The image below illustrates the basic steps of the CCT-based normalization

![image](https://github.com/auranic/CellCycleTrajectory_SegmentModel/blob/main/images/CCT_based_normalization_small.png)


## Simulator of automaton with allometric growth and cell division event

[Here is the notebook containing simulator of toy model as well as the model of real transcriptomic cell cycle trajectory](https://github.com/auranic/CellCycleTrajectory_SegmentModel/blob/main/notebooks/CellCycle_Modeling_SimpleSwitches.ipynb)


## Fitting the parameters of kinetic model

[Here is the notebook which fits the kinetic model to real cell cycle trajectory](https://github.com/auranic/CellCycleTrajectory_SegmentModel/blob/main/notebooks/CellCycleManuscript_ModelingCCT.ipynb)

