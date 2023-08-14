---
layout: group
author: smb2023
day: "Thursday"
room: "Cartoon Room 1 (#3145)"
code: "CT03"
subgroup: "MFBM"
subgroup-long: "MFBM-1"
title: "MFBM Subgroup Contributed Talks"
author1: "Hyeontae Jo"
inst1: "Institute for Basic Science (IBS)"
title1: "Density Physics-Informed Neural Network infers an arbitrary density distribution for non-Markovian system"
abstract1: "In this talk, we have developed Density-PINN (Physics-Informed Neural Networks), a method capable of estimating the probability density function embedded within a differential equation. While conventional PINNs have focused on determining the solutions or parameters of differential equations that can explain observed data, we introduce a specialized approach for estimating the probability density function contained within the equation. Specifically, when dealing with a limited number of stochastic time series as observed data, and where only the average of the data satisfies the solution of the differential equation, we have constructed a mean-generating model using Variational Autoencoders. By applying our method to single-cell gene expression data from 16 promoters in response to antibiotic stress, we discovered that promoters with slower signaling initiation and transduction exhibit greater cell-to-cell heterogeneity in response intensity."
additional_authors1: "Hyukpyo Hong (KAIST, IBS); Hyung Ju Hwang (POSTECH); Won Chang (University of Cincinnati); Jae Kyoung Kim (KAIST, IBS)"
author2: "Luigi Frunzo"
inst2: "University of Naples Federico II"
title2: "Mathematical modelling of phototrophic-heterotrophic biofilm system"
abstract2: "The presentation will concerns a mathematical model for the analysis and prediction of microbial interactions within mixotrophic biofilms composed of microalgae and heterotrophic bacteria. The model combines equations for biomasses growth and decay, diffusion-reaction of substrates, and detachment process. In particular, the colonization of external species invading the biofilm is considered. The biofilm growth is governed by nonlinear hyperbolic PDEs while substrate and invading species dynamics are dominated by semilinear parabolic PDEs. It follows a complex system of PDEs on a free boundary
domain. The equations are numerically integrated by using the method of characteristics. The model has been applied to simulate the ecology of a mixotrophic biofilm formed by phototrophic and heterotrophic species. The comparison of numerical and experimental data will confirm the accuracy of the proposed model."
additional_authors2: "Vincenzo Luongo; Mariarosaria Mattei; Alberto Tenore"
author3: "Samantha Linn"
inst3: "University of Utah"
title3: "First passage times under frequent stochastic resetting"
abstract3: "Stochastic search processes with stochastic resetting have recently received substantial attention in
mathematical biology. Much of the existing work concerns only the study of mean first passage times (FPTs)
of such processes due to their analytical tractability. In our work, we forgo the standard analytical
approach of defining the FPT in terms of a last renewal equation of its density and instead reformulate it
as a sum over failed and successful attempts. This method allows us to determine the full distribution and
moments of the FPT for a broad class of stochastic search processes in the limit of frequent stochastic
resetting. Our results apply to any system whose short-time behavior of the search process without
resetting can be approximated. In addition to the typical case of exponentially distributed resetting times,
we prove our results for a wide array of resetting time distributions. Finally, we show that the errors of
our approximations vanish exponentially fast in typical scenarios of diffusive search."
additional_authors3: "Sean Lawley, University of Utah"
author4: "Silvia Berra"
inst4: "University of Genova, Italy"
title4: "Drug dosage in cancer: a mathematical approach for computing steady states of chemical reaction networks"
abstract4: "During the G1-S transition phase of life of colorectal cells many proteins interact in chemical reactions, some of which are crucial since mutations altering the function of the corresponding proteins may cause cancer. The set of these interactions can be described through a properly designed Chemical Reaction Network (CRN). In turn, the latter can be represented by a mathematical model consisting in a system of autonomous ordinary differential equations.
Computing the steady state of this system is a key step for understanding the global (and local) effects of each mutation and of some specific targeted drugs used to contrast the corresponding functional alterations. The most common approach for computing the steady state consists in simulating the system's dynamical evolution in time; however, this is a very time-consuming process. Here I propose a different method, consisting in recasting the steady state computation problem as a root-finding one. To solve the latter, an algorithm that combines the Newton method and the gradient descent approach is introduced, where the non-negativity constraints on the steady state concentrations are assured by defining and applying a suitable operator P at the end of every iterative step [1]. Such an algorithm, which is convergent under specific assumptions, turns out to be more precise and faster than the dynamic approach.
Starting from a CRN previously introduced for modeling the G1-S transition phase of colorectal cells [2], the method is validated in simulation mimiking both physiological and mutated status and also in the presence of targeted drugs applied individually or together in a combined therapy. 

[1] Berra, Silvia, et al. 'A fast and convergent combined Newton and gradient descent method for computing steady states of chemical reaction networks.' arXiv preprint arXiv:2212.14252 (2022).
[2] Sommariva, Sara, et al. 'Computational quantification of global effects induced by mutations and drugs in signaling networks of colorectal cancer cells.' Scientific reports 11.1 (2021): 19602."
additional_authors4: "Sara Sommariva, Department of Mathematics, University of Genova, via Dodecaneso 35, 16146 Genova, Italy
Federico Benvenuto, Department of Mathematics, University of Genova, via Dodecaneso 35, 16146 Genova, Italy
Giacomo Caviglia, Department of Mathematics, University of Genova, via Dodecaneso 35, 16146 Genova, Italy
Michele Piana, Department of Mathematics, University of Genova, via Dodecaneso 35, 16146 Genova, Italy"
---
