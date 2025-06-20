---
permalink: /
title: "Presentation"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Associate Professor at the Information Processing and Telecommunications Center, ETSI de Telecomunicación, Universidad Politécnica de Madrid. Before then, I was a Senior Lecturer in the Department of Electrical Engineering and Electronics at the University of Liverpool, UK. Previously, I held postdoctoral positions at Universidad Politécnica de Madrid, Chalmers University of Technology, Sweden, Curtin University, Australia, and Aalto University, Finland. 

My main research activities and interests are in the area of Bayesian inference, with emphasis on multiple target tracking and probabilistic machine learning.


Main contributions
======
These are some of my main research contributions.

Generalised optimal sub-pattern assignment (GOSPA) metrics
---------------

The GOSPA metric proposed in [[G1]](https://ieeexplore.ieee.org/document/8009645) is a mathematically principled metric to measure the distance between two sets of targets. The metric is used for evaluation of multi-target filters and it penalises localisation errors for properly detected targets, and the number of missed and false targets.

The trajectory GOSPA (T-GOSPA) metric proposed in [[G2]](https://ieeexplore.ieee.org/abstract/document/9127194) is a mathematically principled metric to measure the distance between two sets of trajectories for evaluation of multi-target tracking algorithms. It penalises localisation errors for properly detected targets, the number of missed and false targets, and includes a track switching cost.

The GOSPA metric has also been extended to graphs to measure the distance between graphs [[G3]](https://ieeexplore.ieee.org/abstract/document/10644126). In this case, it penalises localisation errors for properly detected nodes, the number of missed and false nodes, and edge mismatch errors.


[G1] A. S. Rahmathullah, Á. F. García-Fernández and L. Svensson, "Generalized optimal sub-pattern assignment metric," 2017 20th International Conference on Information Fusion (Fusion), Xi'an, China, 2017, pp. 1-8, doi: 10.23919/ICIF.2017.8009645.

[G2] Á. F. García-Fernández, A. S. Rahmathullah and L. Svensson, "A Metric on the Space of Finite Sets of Trajectories for Evaluation of Multi-Target Tracking Algorithms," in IEEE Transactions on Signal Processing, vol. 68, pp. 3917-3928, 2020, doi: 10.1109/TSP.2020.3005309

[G3] J. Gu, Á. F. García-Fernández, R. E. Firth and L. Svensson, "Graph GOSPA Metric: A Metric to Measure the Discrepancy Between Graphs of Different Sizes," in IEEE Transactions on Signal Processing, vol. 72, pp. 4037-4049, 2024, doi: 10.1109/TSP.2024.3449091.

Poisson multi-Bernoulli mixture (PMBM) filters
---------------

The Poisson multi-Bernoulli mixture (PMBM) filters are closed-form Bayesian multi-target filtering algorithms and can be considered fully Bayesian state-of-the-art multiple hypothesis tracking (MHT) algorithms. The PMBM filters have an efficient hypothesis structure with probabilistic target existence, with significantly lowers the number of global hypotheses. 

There are several PMBM filters depending on the used models, for instance: point-target PMBM filter [[P1]](https://ieeexplore.ieee.org/abstract/document/7272821) [[P2]](https://ieeexplore.ieee.org/abstract/document/8289337), extended-target PMBM filter [[P3]](https://ieeexplore.ieee.org/abstract/document/8730493), PMBM filter for coexisting point and extended targets [[P4]](https://ieeexplore.ieee.org/abstract/document/9399297), general detection-based PMBM filter [[P5]](https://ieeexplore.ieee.org/abstract/document/10130623), continuous-discrete PMBM filters (continuous-time dynamics) [[P6]] (https://ieeexplore.ieee.org/abstract/document/8964451).



[P1] J. L. Williams, "Marginal multi-Bernoulli filters: RFS derivation of MHT, JIPDA, and association-based member," in IEEE Transactions on Aerospace and Electronic Systems, vol. 51, no. 3, pp. 1664-1687, July 2015, doi: 10.1109/TAES.2015.130550.

[P2] Á. F. García-Fernández, J. L. Williams, K. Granström and L. Svensson, "Poisson Multi-Bernoulli Mixture Filter: Direct Derivation and Implementation," in IEEE Transactions on Aerospace and Electronic Systems, vol. 54, no. 4, pp. 1883-1901, Aug. 2018, doi: 10.1109/TAES.2018.2805153. 

[P3] K. Granström, M. Fatemi and L. Svensson, "Poisson Multi-Bernoulli Mixture Conjugate Prior for Multiple Extended Target Filtering," in IEEE Transactions on Aerospace and Electronic Systems, vol. 56, no. 1, pp. 208-225, Feb. 2020, doi: 10.1109/TAES.2019.2920220

[P4] Á. F. García-Fernández, J. L. Williams, L. Svensson and Y. Xia, "A Poisson Multi-Bernoulli Mixture Filter for Coexisting Point and Extended Targets," in IEEE Transactions on Signal Processing, vol. 69, pp. 2600-2610, 2021, doi: 10.1109/TSP.2021.3072006.

[P5] Á. F. García-Fernández, Y. Xia and L. Svensson, "Poisson Multi-Bernoulli Mixture Filter With General Target-Generated Measurements and Arbitrary Clutter," in IEEE Transactions on Signal Processing, vol. 71, pp. 1895-1906, 2023, doi: 10.1109/TSP.2023.3278944.

[P6] Á. F. García-Fernández and S. Maskell, "Continuous-Discrete Multiple Target Filtering: PMBM, PHD and CPHD Filter Implementations," in IEEE Transactions on Signal Processing, vol. 68, pp. 1300-1314, 2020, doi: 10.1109/TSP.2020.2968247.


Multi-target tracking based on sets of trajectories
---------------

In Bayesian multi-target tracking, all information of interest about the trajectories the targets have followed is contained in the density of the set of trajectories given all available measurements. The mathematical foundations to perform multi-target tracking based on sets of trajectories were provided in [[S1]](https://ieeexplore.ieee.org/abstract/document/8731733), and the measure-theory connections in [[S2]](https://arxiv.org/abs/1912.01748).

This framework has enabled the development of a novel class of filters that estimate sets of trajectories from first principles: trajectory PMBM (TPMBM) filters [[S3]](https://ieeexplore.ieee.org/abstract/document/10799204), trajectory PMB (TPMB) filters [[S4]](https://ieeexplore.ieee.org/abstract/document/9169859), trajectory probability hypothesis density (TPHD) filters and trajectory cardinality probability hypothesis density (TCPHD) filters [[SS]](https://ieeexplore.ieee.org/abstract/document/8846723
). Among these, the TPMBM filters provide the closed-form solution to obtain the posterior on the set of trajectories. The rest are approximate filters.  



[S1] Á. F. García-Fernández, L. Svensson and M. R. Morelande, "Multiple Target Tracking Based on Sets of Trajectories," in IEEE Transactions on Aerospace and Electronic Systems, vol. 56, no. 3, pp. 1685-1707, June 2020, doi: 10.1109/TAES.2019.2921210.

[S2] Y. Xia, K. Granström, L. Svensson, A. F. García-Fernández, and J. L. Wlliams, “Multi-scan implementation of the trajectory Poisson multi-Bernoulli
mixture filter,” Journal of Advances in Information Fusion, vol. 14, no. 2, pp. 213–235, Dec. 2019.

[S3] K. Granström, L. Svensson, Y. Xia, J. Williams and Á. F. García-Fernández, "Poisson Multi-Bernoulli Mixtures for Sets of Trajectories," in IEEE Transactions on Aerospace and Electronic Systems, vol. 61, no. 2, pp. 5178-5194, April 2025, doi: 10.1109/TAES.2024.3517576.

[S4] Á. F. García-Fernández, L. Svensson, J. L. Williams, Y. Xia and K. Granström, "Trajectory Poisson Multi-Bernoulli Filters," in IEEE Transactions on Signal Processing, vol. 68, pp. 4933-4945, 2020, doi: 10.1109/TSP.2020.3017046. 

[S5] Á. F. García-Fernández and L. Svensson, "Trajectory PHD and CPHD Filters," in IEEE Transactions on Signal Processing, vol. 67, no. 22, pp. 5702-5714, 15 Nov.15, 2019, doi: 10.1109/TSP.2019.2943234.


Applications
======

I have worked in many different applications including: 
- Multi-target tracking (radar, sonar, drones, space-objects, sensor management, distributed acoustic sensing, computer vision).
- Simultaneous localisation and mapping (5-G, Wi-Fi and Bluetooth).
- Gaussian process inference (molecular property prediction, classification).
- Perception for advanced driver assistance systems.
- Health (fMRI and EEG signal processing).
- Battery state-of-charge estimation.
- Financial portfolio management.


Awards
======

- Second best paper award for the paper "Hybrid PHD-PMB Trajectory Smoothing Using Backward Simulation" (IEEE International Conference on Multisensor Fusion and Integration for Intelligent Systems, 2024).

- Second best paper award for the paper "An analysis on metric-driven multi-target sensor management: GOSPA versus OSPA" (24th International Conference on Information Fusion, 2021).

- Third Best paper award for the paper "Spooky effect in optimal OSPA estimation and how GOSPA solves it" (22nd International Conference on Information Fusion, 2019).

- Best paper award for the paper "Generalized optimal sub-pattern assignment metric" (20th International Conference on Information Fusion, 2017).

