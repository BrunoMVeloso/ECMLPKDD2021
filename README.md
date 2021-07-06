# Hyper-Parameter Optimization for LatentSpaces in Dynamic Recommender System


This is the accompanying code for the paper

[Hyper-Parameter Optimization for Latent Spaces in Dynamic Recommender Systems](https://github.com/BrunoMVeloso/ECMLPKDD2021/ecmlpkdd_paper.pdf), by Bruno Veloso, Luciano Caroprese, Matthias König, Sónia Teixeira, Giuseppe Manco, Holger H. Hoos, and João Gama. The paper has been accepted for presentation as a full paper at the research track of the 2021 edition of [The European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases](https://2021.ecmlpkdd.org/?page_id=1811).

The paper is the result of a joint activity at the [HumaneAI-Net](https://www.humane-ai.eu/) project, as described in the [related page](https://www.humane-ai.eu/project/online-deep-automl/). A poster describing the main results achieved within this activity are described [here](https://github.com/BrunoMVeloso/ECMLPKDD2021/blob/main/Poster%20HumanE-AI.pdf).

The following video exemplifies the behavior of the Nelder-Mead algorithm proposed in the paper. 

![NelderMead](https://github.com/BrunoMVeloso/ECMLPKDD2021/blob/main/NelderMead.gif)

The notebook is essentially self-explanatory. You need Pytorch >= 1.5 to run it.

- There is a section containing the data generator proposed in the paper. 
- Experiments including the Nelder-Mead, SMAC baseline and Static baseline are reported and all the graphs contained in the paper are reproduced. 


Bibtex

```
@inproceedings{VelEtAl21,
 title="Hyper-Parameter Optimization for Latent Spaces in Dynamic Recommender Systems",
 author="Veloso, Bruno and Caroprese, Luciano and K{\"o}nig, Matthias and Teixeira, S{\'o}nia and Manco, Giuseppe and Hoos, Holger H and Gama, Jo{\~a}o",
 booktitle="Proceedings of the European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases",
 year="to appear"
 tags="AutoML, Hyper-Parameter Optimization, Latent Spaces, Nelder-Mead, SMAC, Recommender Systems"
}
```
