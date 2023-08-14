---
layout: group
author: smb2023
day: "Tuesday"
subgroup: "ECOP"
subgroup-long: "ECOP-1"
title: "Current trends in phylogenetics"
organizers: "Kristina Wicke, Laura Kubatko"
description: "Inference of phylogenies – graphs that display ancestry-descent relationships among a collection of species – is a fundamental problem in evolutionary biology, and one for which the community of mathematical biologists has made crucial contributions. The field of phylogenetics is also heavily interdisciplinary, requiring interactions among mathematicians, statisticians, computer scientists, and biologists. The overarching goals of the field are to reconstruct and analyze the tree (or rather network) of life from data observed in the present and to use these data to make predictions about future evolutionary trajectories (as for instance, in the analysis of viruses). Both are challenging tasks and have led to many exciting new mathematical and computational questions and results. This mini-symposium will bring together researchers of various backgrounds (ranging from Discrete Biomathematics to Scientific Computing) and differing career stages to discuss current trends and recent developments in phylogenetics and beyond."
room: "Senate Chamber (#2145)"
code: "MS04"
code2: "MS03"
author1: "Nathan Kolbow"
inst1: "University of Wisconsin-Madison (Department of Statistics)"
title1: "Sorting gene trees by their path within a species network"
additional_authors1: "Claudia Solis-Lemus"
abstract1: "Reticulate evolution has been identified in the phylogenies of many species, and several methods have leveraged gene tree topologies to infer these species networks. Such methods are powerful for inferring reticulate phylogenies at the species level but do not provide any insights for individual genes. Here, we present a statistical method for accurately comparing subsets of gene trees based on the unknown displayed species tree they belong to within a species network. The result is an algorithm that accurately groups gene trees based on the path they follow in the species network. The displayed species tree corresponding to each group can then be inferred, deducing where individual genes did or did not follow horizontal gene transfer events in their evolutionary history."
author2: "Brandon Legried"
inst2: "Georgia Institute of Technology (Mathematics)"
title2: "Inferring phylogenetic birth-death models from extant lineages through time"
additional_authors2: "Jonathan Terhorst"
abstract2: "Birth-death processes have been used to study population growth, with broad-ranging biological applications such as identifying speciation and extinction rates, calibrating divergence times, and studying the dynamics of pathogens in infection trees. Recent theoretical work on phylogenetic birth-death models offer differing viewpoints on whether they can be estimated from lineages through time. Recently, Louca and Pennell (2020) demonstrated that time-varying birth and death rates are not identifiable from lineage-through-time data. This was a grave result, in view of thousands of published biological and computational studies that use this data. In this talk, I explain how identifiability can be restored, while re-focusing the discussion to what actually makes inference computationally challenging. This is based on joint work with Jonathan Terhorst (University of Michigan, Ann Arbor)."
author3: "Colby Long"
inst3: "The College of Wooster (Mathematical and Computational Sciences)"
title3: "Phylogenomic Models from Tree Symmetries"
additional_authors3: "Elizabeth S. Allman, University of Alaska Fairbanks; John A. Rhodes, University of Alaska Fairbanks"
abstract3: "Models of genomic sequence evolution often include a coalescent process since different sites may evolve on different gene trees due to
incomplete lineage sorting. Chifman and Kubatko initiated the study of such models, leading to the development of the SVDquartets method of
species tree inference. A key observation was that symmetries in an ultrametric species tree led to symmetries in the joint distribution of
bases at the taxa. In this talk, we will explore the implications of such symmetries more fully, defining new models incorporating only these symmetries, regardless of the mechanisms that might have produced them. We will also discuss phylogenetic invariants for these models and how the invariants can be used to establish identifiability of the species tree topologies."
author4: "Julia Chifman"
inst4: "American University (Mathematics and Statistics)"
title4: "Cancer evolution: mathematical models and inference methods."
additional_authors4: "Adam Knapp, Research Scientist at the Laboratory for Systems Medicine in the College of Medicine at the University of Florida;
Laura Kubatko, Professor of Statistics and Evolution, Ecology and Organismal Biology, The Ohio State University."
abstract4: "The advent of single-cell sequencing provides the ability to model clonal evolution of tumors within individual patients. Inference of such within-patient tumor phylogenies has the potential to advance our understanding of the variation in the process of tumor progression. The process of tumor evolution has been reviewed extensively by many authors, with strong support for the view of a tumor as an ecosystem of evolving subpopulations that compete for space and resources in their microenvironment. Phylogenetic methods have been applied in numerous ways to model tumor evolution, for both bulk tumor samples and for single-cell data. For single-cell data, the data type considered in this presentation, these methods range from the use of inferred pairwise mutation orders to reconstruct the phylogeny to specification of a mutation model and possibly also an error model, from which either a likelihood or a Bayesian inferential framework can be adopted. This presentation investigates current models and methods and compares them to our method using both simulated and empirical data. We also compare the performance of methods using data simulated over a random phylogeny versus data simulated over a phylogeny constrained by the evolving tumor."
---
