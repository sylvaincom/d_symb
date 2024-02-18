# $d_{symb}$: An Interpretable Distance Measure for Multivariate Non-Stationary Physiological Signals

>Now that the proceedings are available, the code of $d_{symb}$ will soon be made available!

This repository contains the code to reproduce all experiments in our publication:
```
S. W. Combettes, C. Truong, and L. Oudre.
An Interpretable Distance Measure for Multivariate Non-Stationary Physiological Signals.
In "Proceedings of the International Conference on Data Mining Workshops (ICDMW)", Shanghai, China, 2023.
```
Links: [paper](https://ieeexplore.ieee.org/abstract/document/10411636) / [PDF](http://www.laurentoudre.fr/publis/ICDM2023.pdf)

All the code is written in Python (scripts and notebooks).

<details><summary><i>Toggle for the paper's abstract!</i></summary>We introduce d_{symb}, a novel distance measure for comparing multivariate non-stationary physiological signals. Unlike most distance measures on multivariate signals such as variants of Dynamic Time Warping (DTW), d_{symb} can take into account their non-stationarity thanks to a symbolization step. This step is based on a change-point detection procedure, that splits a non-stationary signal into several stationary segments, followed by quantization using K-means clustering. The proposed distance measure leverages the general edit distance that is applied to the symbolic sequences. The performance of d_{symb} compared to two commonly used DTW variants is illustrated by applying it to physiological signals recorded during walking protocols. In particular, d_{symb} is shown to be interpretable: its symbolization detects the segments that correspond to salient behaviors. An open source GitHub repository is made available to reproduce all the experiments in Python.</details></br>

Please let us know of any issue you might encounter when using this code, either by opening an issue on this repository or by sending an email to `sylvain.combettes [at] ens-paris-saclay.fr`. Or if you just need some clarification or help.
