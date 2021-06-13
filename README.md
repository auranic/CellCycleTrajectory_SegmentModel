# Modeling progression of single cell populations through the cell cycle as a sequence of switches

Set of Python notebooks reproducing the procedures in the article 'Modeling progression of single cell populations through the cell cycle as a sequence of switches'

Dependencies:

1. [Stabilized ICA](https://github.com/ncaptier/Stabilized_ICA)
2. [scycle](https://github.com/csgroen/scycle)
3. [ElPiGraph](https://github.com/j-bac/elpigraph-python)
4. [skdim](https://github.com/j-bac/scikit-dimension)

## Normalization of single cell RNASeq dataset and extracting the trajectory

[Here is the notebook performing the normalization](https://github.com/auranic/CellCycleTrajectory_SegmentModel/blob/main/notebooks/CCT_Normalization_Computation.ipynb)

![image](https://github.com/auranic/CellCycleTrajectory_SegmentModel/blob/main/images/CCT_based_normalization_small.png)


## Simulator of automaton with allometric growth and cell division event

[Here is the notebook containing simulator of toy model as well as the model of real transcriptomic cell cycle trajectory](https://github.com/auranic/CellCycleTrajectory_SegmentModel/blob/main/notebooks/CellCycle_Modeling_SimpleSwitches.ipynb)


## Fitting the parameters of kinetic model

[Here is the notebook which fits the kinetic model to real cell cycle trajectory](https://github.com/auranic/CellCycleTrajectory_SegmentModel/blob/main/notebooks/CellCycleManuscript_ModelingCCT.ipynb)

