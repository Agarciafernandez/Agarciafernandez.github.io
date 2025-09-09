---
permalink: /
title: "Presentation"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an **Associate Professor** at the [Information Processing and Telecommunications Center](https://iptc.upm.es/), ETSI de Telecomunicación, [**Universidad Politécnica de Madrid**](https://www.upm.es/internacional). Before then, I was a Senior Lecturer at the **University of Liverpool**, UK. Previously, I held postdoctoral positions at Universidad Politécnica de Madrid, **Chalmers University of Technology**, Sweden, **Curtin University**, Australia, and **Aalto University**, Finland. As a PhD student, I also did two research stays at the **University of Melbourne**, Australia. 

My main research activities and interests are in the area of Bayesian inference, with emphasis on multiple target tracking and probabilistic machine learning.


Main contributions
======
These are some of my main research contributions.

Generalised optimal sub-pattern assignment (GOSPA) metrics
---------------

**The GOSPA metric [[G1]](https://ieeexplore.ieee.org/document/8009645) is a mathematically principled metric to measure the distance between two sets of targets for evaluation of multi-target filtering algorithms**. The metric penalises localisation errors for properly detected targets, and the number of missed and false targets, see [video](https://www.youtube.com/watch?v=M79GTTytvCM).

**The trajectory GOSPA (T-GOSPA) metric [[G2]](https://ieeexplore.ieee.org/abstract/document/9127194) is a mathematically principled metric to measure the distance between two sets of trajectories for evaluation of multi-target tracking algorithms**. It penalises localisation errors for properly detected targets, the number of missed and false targets, and the number of track switches.

The GOSPA metric has also been extended to graphs to measure the distance between graphs [[G3]](https://ieeexplore.ieee.org/abstract/document/10644126). The graph GOSPA metric penalises localisation errors for properly detected nodes, the number of missed and false nodes, and edge mismatch errors.


[G1] A. S. Rahmathullah, Á. F. García-Fernández and L. Svensson, "Generalized optimal sub-pattern assignment metric," 2017 20th International Conference on Information Fusion (Fusion), Xi'an, China, 2017, pp. 1-8, doi: 10.23919/ICIF.2017.8009645.

[G2] Á. F. García-Fernández, A. S. Rahmathullah and L. Svensson, "A Metric on the Space of Finite Sets of Trajectories for Evaluation of Multi-Target Tracking Algorithms," in IEEE Transactions on Signal Processing, vol. 68, pp. 3917-3928, 2020, doi: 10.1109/TSP.2020.3005309

[G3] J. Gu, Á. F. García-Fernández, R. E. Firth and L. Svensson, "Graph GOSPA Metric: A Metric to Measure the Discrepancy Between Graphs of Different Sizes," in IEEE Transactions on Signal Processing, vol. 72, pp. 4037-4049, 2024, doi: 10.1109/TSP.2024.3449091.

Poisson multi-Bernoulli mixture (PMBM) filters
---------------

The **Poisson multi-Bernoulli mixture (PMBM) filters are closed-form, fully Bayesian multi-target filtering algorithms**. PMBM filters can be considered fully Bayesian, state-of-the-art multiple hypothesis tracking (MHT) algorithms. The PMBM filters have an efficient hypothesis structure with probabilistic target existence, which significantly lowers the number of global hypotheses. 

There are several PMBM filters depending on the used models, for instance: point-target PMBM filter [[P1]](https://ieeexplore.ieee.org/abstract/document/7272821) [[P2]](https://ieeexplore.ieee.org/abstract/document/8289337), extended-target PMBM filter [[P3]](https://ieeexplore.ieee.org/abstract/document/8730493), PMBM filter for coexisting point and extended targets [[P4]](https://ieeexplore.ieee.org/abstract/document/9399297), general detection-based PMBM filter [[P5]](https://ieeexplore.ieee.org/abstract/document/10130623), continuous-discrete PMBM filters (continuous-time dynamics) [[P6]](https://ieeexplore.ieee.org/abstract/document/8964451) [[P7]](https://ieeexplore.ieee.org/abstract/document/10857380).

The PMBM filters can be approximated via Poisson multi-Bernoulli (PMB) filters for faster computing, see for instance [[P1]](https://ieeexplore.ieee.org/abstract/document/7272821) and [[P8]](https://ieeexplore.ieee.org/abstract/document/9535241).

A Youtube course that explains Bayesian multi-object tracking including PMBM filtering is [here](https://www.youtube.com/@multipleobjecttracking1226).

[P1] J. L. Williams, "Marginal multi-Bernoulli filters: RFS derivation of MHT, JIPDA, and association-based member," in IEEE Transactions on Aerospace and Electronic Systems, vol. 51, no. 3, pp. 1664-1687, July 2015, doi: 10.1109/TAES.2015.130550.

[P2] Á. F. García-Fernández, J. L. Williams, K. Granström and L. Svensson, "Poisson Multi-Bernoulli Mixture Filter: Direct Derivation and Implementation," in IEEE Transactions on Aerospace and Electronic Systems, vol. 54, no. 4, pp. 1883-1901, Aug. 2018, doi: 10.1109/TAES.2018.2805153. 

[P3] K. Granström, M. Fatemi and L. Svensson, "Poisson Multi-Bernoulli Mixture Conjugate Prior for Multiple Extended Target Filtering," in IEEE Transactions on Aerospace and Electronic Systems, vol. 56, no. 1, pp. 208-225, Feb. 2020, doi: 10.1109/TAES.2019.2920220

[P4] Á. F. García-Fernández, J. L. Williams, L. Svensson and Y. Xia, "A Poisson Multi-Bernoulli Mixture Filter for Coexisting Point and Extended Targets," in IEEE Transactions on Signal Processing, vol. 69, pp. 2600-2610, 2021, doi: 10.1109/TSP.2021.3072006.

[P5] Á. F. García-Fernández, Y. Xia and L. Svensson, "Poisson Multi-Bernoulli Mixture Filter With General Target-Generated Measurements and Arbitrary Clutter," in IEEE Transactions on Signal Processing, vol. 71, pp. 1895-1906, 2023, doi: 10.1109/TSP.2023.3278944.

[P6] Á. F. García-Fernández and S. Maskell, "Continuous-Discrete Multiple Target Filtering: PMBM, PHD and CPHD Filter Implementations," in IEEE Transactions on Signal Processing, vol. 68, pp. 1300-1314, 2020, doi: 10.1109/TSP.2020.2968247.

[P7] Á. F. García-Fernández and S. Särkkä, "Gaussian Multi-Target Filtering With Target Dynamics Driven by a Stochastic Differential Equation," in IEEE Transactions on Signal Processing, vol. 73, pp. 664-675, 2025, doi: 10.1109/TSP.2025.3535556.

[P8] Y. Xia, K. Granström, L. Svensson, M. Fatemi, Á. F. García-Fernández and J. L. Williams, "Poisson Multi-Bernoulli Approximations for Multiple Extended Object Filtering," in IEEE Transactions on Aerospace and Electronic Systems, vol. 58, no. 2, pp. 890-906, April 2022, doi: 10.1109/TAES.2021.3111720.


Multi-target tracking based on sets of trajectories
---------------

**In Bayesian multi-target tracking, all probabilistic information about the trajectories the targets have followed is contained in the density of the set of trajectories given all available measurements**. The mathematical foundations to perform multi-target tracking based on sets of trajectories were provided in [[S1]](https://ieeexplore.ieee.org/abstract/document/8731733), and the measure theory connections in [[S2]](https://arxiv.org/abs/1912.01748).

This framework has enabled the development of a novel class of multi-target tracking algorithms that estimate sets of trajectories from first principles: trajectory PMBM (TPMBM) filters [[S3]](https://ieeexplore.ieee.org/abstract/document/10799204), trajectory PMB (TPMB) filters [[S4]](https://ieeexplore.ieee.org/abstract/document/9169859), trajectory probability hypothesis density (TPHD) filters and trajectory cardinality probability hypothesis density (TCPHD) filters [[S5]](https://ieeexplore.ieee.org/abstract/document/8846723
). Among these, the TPMBM filters provide the closed-form solution to obtain the posterior on the set of trajectories. The rest are approximate filters with different computational-accuracy trade-offs.  

Sets of trajectories also enable optimal processing of out-of-sequence measurements [[S6]](https://ieeexplore.ieee.org/document/9502575). If we consider target spawning, we can use sets of tree trajectories to keep complete genealogy information of each trajectory [[S7]](https://ieeexplore.ieee.org/document/9754270).


[S1] Á. F. García-Fernández, L. Svensson and M. R. Morelande, "Multiple Target Tracking Based on Sets of Trajectories," in IEEE Transactions on Aerospace and Electronic Systems, vol. 56, no. 3, pp. 1685-1707, June 2020, doi: 10.1109/TAES.2019.2921210.

[S2] Y. Xia, K. Granström, L. Svensson, A. F. García-Fernández, and J. L. Wlliams, “Multi-scan implementation of the trajectory Poisson multi-Bernoulli
mixture filter,” Journal of Advances in Information Fusion, vol. 14, no. 2, pp. 213–235, Dec. 2019.

[S3] K. Granström, L. Svensson, Y. Xia, J. Williams and Á. F. García-Fernández, "Poisson Multi-Bernoulli Mixtures for Sets of Trajectories," in IEEE Transactions on Aerospace and Electronic Systems, vol. 61, no. 2, pp. 5178-5194, April 2025, doi: 10.1109/TAES.2024.3517576.

[S4] Á. F. García-Fernández, L. Svensson, J. L. Williams, Y. Xia and K. Granström, "Trajectory Poisson Multi-Bernoulli Filters," in IEEE Transactions on Signal Processing, vol. 68, pp. 4933-4945, 2020, doi: 10.1109/TSP.2020.3017046. 

[S5] Á. F. García-Fernández and L. Svensson, "Trajectory PHD and CPHD Filters," in IEEE Transactions on Signal Processing, vol. 67, no. 22, pp. 5702-5714, 15 Nov.15, 2019, doi: 10.1109/TSP.2019.2943234.

[S6] Á. F. García-Fernández and W. Yi, "Continuous-Discrete Multiple Target Tracking With Out-of-Sequence Measurements," in IEEE Transactions on Signal Processing, vol. 69, pp. 4699-4709, 2021, doi: 10.1109/TSP.2021.3100999. 

[S7] Á. F. García-Fernández and L. Svensson, "Tracking Multiple Spawning Targets Using Poisson Multi-Bernoulli Mixtures on Sets of Tree Trajectories," in IEEE Transactions on Signal Processing, vol. 70, pp. 1987-1999, 2022, doi: 10.1109/TSP.2022.3165947.



Iterated posterior linearisation for Bayesian inference
---------------

In Bayesian inference, given a Gaussian prior, a Gaussian approximation to the posterior can be obtained by approximating the likelihood as a linear-Gaussian model. How the parameters of this linear-Gaussian model are chosen determines the quality of the posterior approximation. **Iterated posterior linearisation seeks the optimal linearisation** in a mean square error sense for the given measurement value **by performing iterated statistical linear regression w.r.t. the posterior**. This approach leads to the iterated posterior linearisation filter (IPLF) [[I1]](https://ieeexplore.ieee.org/document/7153566), which generalises (non-iterated) non-linear Kalman filters. Iterated posterior linearisation inference can also be applied to other applications such as smoothing [[I2]](https://ieeexplore.ieee.org/document/7515187) [[I3]](https://ieeexplore.ieee.org/abstract/document/8260875), cooperative localisation [[I4]](https://ieeexplore.ieee.org/abstract/document/7999230) and classification using Gaussian processes [[I5]](https://ieeexplore.ieee.org/document/8673324).

Iterated posterior linearisation is described in two popular books for state estimation [[I6]](https://users.aalto.fi/~ssarkka/pub/bfs_book_2023_online.pdf) and machine learning [[I7]](https://probml.github.io/pml-book/book2.html). 


[I1] Á. F. García-Fernández, L. Svensson, M. R. Morelande and S. Särkkä, "Posterior Linearization Filter: Principles and Implementation Using Sigma Points," in IEEE Transactions on Signal Processing, vol. 63, no. 20, pp. 5561-5573, Oct.15, 2015, doi: 10.1109/TSP.2015.2454485.

[I2] Á. F. García-Fernández, L. Svensson and S. Särkkä, "Iterated Posterior Linearization Smoother," in IEEE Transactions on Automatic Control, vol. 62, no. 4, pp. 2056-2063, April 2017, doi: 10.1109/TAC.2016.2592681.

[I3] F. Tronarp, Á. F. García-Fernández and S. Särkkä, "Iterative Filtering and Smoothing in Nonlinear and Non-Gaussian Systems Using Conditional Moments," in IEEE Signal Processing Letters, vol. 25, no. 3, pp. 408-412, March 2018, doi: 10.1109/LSP.2018.2794767.

[I4] Á. F. García-Fernández, L. Svensson and S. Särkkä, "Cooperative Localization Using Posterior Linearization Belief Propagation," in IEEE Transactions on Vehicular Technology, vol. 67, no. 1, pp. 832-836, Jan. 2018, doi: 10.1109/TVT.2017.2734683. 

[I5] Á. F. García-Fernández, F. Tronarp and S. Särkkä, "Gaussian Process Classification Using Posterior Linearization," in IEEE Signal Processing Letters, vol. 26, no. 5, pp. 735-739, May 2019, doi: 10.1109/LSP.2019.2906929.

[I6] S. Särkkä and L. Svensson, Bayesian Filtering and Smoothing, 2nd ed. Cambridge University Press, 2023.

[I7] K. P. Murphy, Probabilistic Machine Learning: Advanced Topics. MIT Press, 2023.


Temporal parallelisation of Bayesian smoothers and control
---------------

Bayesian smoothing has a linear complexity in the number of time steps. **The framework in [[T1]](https://ieeexplore.ieee.org/abstract/document/9013038) solves Bayesian smoothing problems with logarithmic time complexity**. This is achieved by determining the elements and associative operators to pose the filtering and smoothing problems as an all-prefix-sums operation, which can be solved in parallel using parallel scans. 

This framework gives rise to parallel-in-time Kalman smoothers [[T1]](https://ieeexplore.ieee.org/abstract/document/9013038), and parallel-in-time smoothers for hidden Márkov models [[T2]](https://ieeexplore.ieee.org/abstract/document/9512397). The approach can be extended to obtain parallel-in-time Viterbi algorithms [[T2]](https://ieeexplore.ieee.org/abstract/document/9512397) [[T3]](https://ieeexplore.ieee.org/abstract/document/10289998) and to solve optimal control problems [[T4]](https://ieeexplore.ieee.org/abstract/document/9697418). The code of these algorithms can be written in machine learning frameworks to make the most of the parallel computation capabilities of graphics processing units (GPUs). 

This contribution is also discussed in the book [[I7]](https://probml.github.io/pml-book/book2.html).

[T1] S. Särkkä and Á. F. García-Fernández, "Temporal Parallelization of Bayesian Smoothers," in IEEE Transactions on Automatic Control, vol. 66, no. 1, pp. 299-306, Jan. 2021, doi: 10.1109/TAC.2020.2976316.

[T2] S. S. Hassan, S. Särkkä and Á. F. García-Fernández, "Temporal Parallelization of Inference in Hidden Markov Models," in IEEE Transactions on Signal Processing, vol. 69, pp. 4875-4887, 2021, doi: 10.1109/TSP.2021.3103338.

[T3] S. Särkkä and Á. F. García-Fernández, "On The Temporal Parallelisation of The Viterbi Algorithm," 2023 31st European Signal Processing Conference (EUSIPCO), Helsinki, Finland, 2023, pp. 2018-2022, doi: 10.23919/EUSIPCO58844.2023.10289998.

[T4] S. Särkkä and Á. F. García-Fernández, "Temporal Parallelization of Dynamic Programming and Linear Quadratic Control," in IEEE Transactions on Automatic Control, vol. 68, no. 2, pp. 851-866, Feb. 2023, doi: 10.1109/TAC.2022.3147017. 

Applications
======

I have worked in many different applications including: 
- Multi-target tracking (radar, sonar, space-objects, drones, traffic monitoring, sensor management, distributed acoustic sensing, computer vision).
- Simultaneous localisation and mapping (5-G, Wi-Fi and Bluetooth).
- Gaussian process inference (molecular property prediction, classification).
- Perception for advanced driver assistance systems.
- Health (fMRI and EEG signal processing).
- Battery state-of-charge estimation.
- Financial portfolio management.


Awards
======

- Best paper award for the paper [A. S. Rahmathullah, Á. F. García-Fernández and L. Svensson, "Generalized optimal sub-pattern assignment metric," 2017 20th International Conference on Information Fusion (Fusion), Xi'an, China, 2017, pp. 1-8, doi: 10.23919/ICIF.2017.8009645.](https://ieeexplore.ieee.org/document/8009645)

- Third best paper award for the paper [Á. F. García-Femández and L. Svensson, "Spooky effect in optimal OSPA estimation and how GOSPA solves it," 2019 22th International Conference on Information Fusion (FUSION), Ottawa, ON, Canada, 2019, pp. 1-8, doi: 10.23919/FUSION43075.2019.9011259.](https://ieeexplore.ieee.org/document/9011259).

- Second best paper award for the paper [Á. F. García-Fernández, M. Hernandez and S. Maskell, "An analysis on metric-driven multi-target sensor management: GOSPA versus OSPA," 2021 IEEE 24th International Conference on Information Fusion (FUSION), Sun City, South Africa, 2021, pp. 1-8, doi: 10.23919/FUSION49465.2021.9626837](https://ieeexplore.ieee.org/document/9626837).

- Second best paper award for the paper [Y. Xia, A. F. Garcia-Fernandez and L. Svensson, "Hybrid PHD-PMB Trajectory Smoothing Using Backward Simulation," 2024 IEEE International Conference on Multisensor Fusion and Integration for Intelligent Systems (MFI), Pilsen, Czech Republic, 2024, pp. 1-8, doi: 10.1109/MFI62651.2024.10705782](https://ieeexplore.ieee.org/document/10705782).






