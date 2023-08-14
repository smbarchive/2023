---
layout: group
author: smb2023
day: "Wednesday"
subgroup: "MFBM"
subgroup-long: "MFBM-1"
title: "Data-driven methods for biological modeling"
organizers: "John Nardini, Erica Rutter, 
Kevin Flores"
description: "This minisymposium highlights the development of novel data-driven methods, including statistics, machine learning, parameter estimation, and uncertainty quantification, and combinations thereof, towards modeling biological systems. These newly developed methods will tackle challenges that are commonly encountered when modeling real-world experimental, field, pre-clinical, or clinical data. Examples of such challenges include high dimensionality, computational complexity, sparse sampling, model bias, and intra- or inter-individual heterogeneity. The methods introduced in this minisymposium are applicable to a broad range of biological areas, including neurobiology, epidemiology, oncology, electrophysiology, and genetics."
room: "Cartoon Room 1 (#3145)"
code: "MS05"
author1: "Natalia Kravtsova"
inst1: "The Ohio State University (Department of Mathematics)"
title1: "Scalable Gromov-Wasserstein based comparison of biological time series"
additional_authors1: "Reginald L. McGee II, Department of Mathematics and Computer Science, College of the Holy Cross;
Adriana T. Dawes, Department of Mathematics, The Ohio State University"
abstract1: "A time series is an extremely abundant data type arising in many areas of scientific research, including the biological sciences. Any method that compares time series data relies on a pairwise distance between trajectories, and the choice of distance measure determines the accuracy and speed of the time series comparison. This work introduces an optimal transport type distance for comparing time series trajectories that are allowed to lie in spaces of different dimensions and/or with differing numbers of points possibly unequally spaced along each trajectory. The construction is based on a modified Gromov-Wasserstein distance optimization program, reducing the problem to a Wasserstein distance on the real line. The resulting program has a closed-form solution and can be computed quickly due to the scalability of the one-dimensional Wasserstein distance. We discuss theoretical properties of this distance measure, and empirically demonstrate the performance of the proposed distance on several datasets with a range of characteristics commonly found in biologically relevant data. We also use our proposed distance to demonstrate that averaging oscillatory time series trajectories using the recently proposed Fused Gromov-Wasserstein barycenter retains more characteristics in the averaged trajectory when compared to traditional averaging, which demonstrates the applicability of Fused Gromov-Wasserstein barycenters for biological time series. 
Fast and user friendly software for computing the proposed distance and related applications is provided. The proposed distance allows fast and meaningful comparison of biological time series and can be efficiently used in a wide range of applications."
author2: "Yordan P. Raykov"
inst2: "University of Nottingham (Statistics and Probability)"
title2: "Digital disease progression biomarkers for Parkinson's disease: algorithms for passive monitoring"
additional_authors2: "Luc Evers, Bastiaan R. Bloem, Tom M. Heskes, Marjan J. Meinders, Kasper Claes, Max A. Little"
abstract2: "In order to facilitate truly passive monitoring of long-term diseases such as Parkinson’s disease (PD), there is a need for models which can reliably quantify symptom-related characteristics of the disease in the highly variable context of daily life, rather than reflect the spurious correlation between sensor-based measurements and desired clinical outcomes. Toward that end, we develop scalable Bayesian nonparametric latent variable models with the capacity to capture a sparser representation of IMU data in free-living and detect statistical fluctuations reflective of different PD symptomatics. We propose the use of Bayesian radial basis function layers as an augmentation mechanism in off-the-shelf symptom detection methods and demonstrate their applicability as a mediator learning framework in the detection of PD resting tremors. We outline formally some of the fundamental challenges in doing causal inference in digital monitoring clinical trials for PD and propose theoretically justified strategies for dealing with different types of observed and unobserved confounding in free-living digital biomarkers. Furthermore, we propose novel latent variable models for quantifying time-of-day symptom fluctuations in free-living and a framework for temporal causal estimation of variable time horizon causes and outcomes."
---
