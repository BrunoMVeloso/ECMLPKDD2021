# Hyper-Parameter Optimization for LatentSpaces in Dynamic Recommender System


This is the accompanying code for the paper

[Hyper-Parameter Optimization for LatentSpaces in Dynamic Recommender Systems](https://github.com/BrunoMVeloso/ECMLPKDD2021/ecmlpkdd_paper.pdf), by Bruno Veloso, Luciano Caroprese, Matthias König, Sónia Teixeira, Giuseppe Manco, Holger H. Hoos, and João Gama.

The paper is the result of a joint activity at the [HumaneAI-Net](https://www.humane-ai.eu/) project, as described in the [related page](https://www.humane-ai.eu/project/online-deep-automl/). A poster describing the main results achieved within this activity are described [here](https://github.com/BrunoMVeloso/ECMLPKDD2021/blob/main/Poster%20HumanE-AI.pdf).

The following video exemplifies the behavior of the Nelder-Mead algorithm proposed in the paper. 

![NelderMead](https://github.com/BrunoMVeloso/ECMLPKDD2021/blob/main/NelderMead.gif)

The notebook is essentially self-explanatory. You need Pytorch >= 1.5 to run it.

- There is a section containing the data generator proposed in the paper. 
- Experiments including the Nelder-Mead, SMAC baseline and Static baseline are reported and all the graphs contained in the paper are reproduced. 

