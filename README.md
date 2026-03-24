## Code for paper: Hybrid Monte Carlo Metadynamics

In paper, *[Hybrid Monte Carlo Metadynamics](https://doi.org/10.1063/5.0296724)*, we introduce a new algorithm that integrates the Hybrid Monte Carlo algorithm with Metadynamics, which we term "hybridMC-MetaD" (hMCMetaD in this git repository).

* `algorithm` folder: implementation of hybridMC-MetaD (hMCMetaD) algorithm and an illustrative example on a double-well model system
* `updater` folder: implementation of hybridMC-MetaD (hMCMetaD) as a HOOMD-blue custom updater and an example of using it on a hard bipyramid system

A preprint of this work is available on arXiv: https://arxiv.org/abs/2508.15942 

The data generated for this work and the scripts used can be found at https://doi.org/10.7302/rb0h-s710

If you have any questions, feel free to reach out to: zshiqi[at]umich.edu

If you find this repository helpful, please consider citing our paper: 

Zhao, C. S., Tsai, S. T., & Glotzer, S. C. (2026). Hybrid Monte Carlo metadynamics (hybridMC-MetaD). The Journal of Chemical Physics, 164(2).