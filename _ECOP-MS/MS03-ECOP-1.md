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
code: "MS03"
code2: "MS04"
author1: "Hector Banos"
inst1: "Dalhousie University (Department of Mathematics and statistics)"
title1: "When Are Profile Mixture Models affected by Over-parameterization?"
additional_authors1: "Andrew Rogers - Dalhousie University;
Ed Susko - Dalhousie University"
abstract1: "Phylogenetic models of protein sequence evolution not accounting for site heterogeneity are prone to long-branch attraction (LBA) artifacts, especially when reconstructing relationships on a billion-year time scale. Profile mixture models have been developed to approximate protein sequence evolution on a billion-year timescale by considering a finite mixture of stationary amino acid frequency vectors. Recently there have been questions about such models being affected by over-parameterization. Notably, people have argued that over-parameterization can negatively affect tree topology estimation if many frequency vectors are considered. We demonstrate that this is not the case based on classical statistical results, extensive simulations, and empirical examples. Moreover, our results can be applied to other types of mixture models used in phylogenetics."
author2: "Peter Beerli"
inst2: "Florida State University (Scientific Computing)"
title2: "Population genetics processes impact Species Trees estimation"
additional_authors2: "Marzieh Khodaei (Florida State University)"
abstract2: "We investigate the effects of DNA mutation models, population growth, and gene flow
on the power to correctly infer a species tree from genomic data. These inferences are
complicated by the commonly used representation of the sequence data as single
nucleotide polymorphisms instead of the full DNA sequences. This data representation
choice reduces the potential variability in the data and biases parameters such as
the effective population size of a species downwards. Methods that may work for
species with small population sizes, such as primates, will most likely fail
with species that have large population sizes, such as mosquitoes."
author3: "Lena Collienne"
inst3: "Fred Hutch Cancer Center (Computational Biology)"
title3: "Spaces of Discrete Time Trees"
additional_authors3: ""
abstract3: "Many algorithms for phylogenetic tree inference navigate treespace to find trees that are optimal according to some criterion. Though some software packages aim to reconstruct a distribution of trees rather than a single best tree, there is a lack of tools to analyse such distributions or samples thereof. In order to develop statistical methods for analysing distibutions over treespace, different ways of defining proximity of trees in treespace have been proposed, each of which provides a different definition of a metric space containing all possible trees. These definitions of treespace depend on the type of trees considered, for example time trees where branch lengths represent times, which we will focus on in this talk. Gaining insights into the timing of evolutionary events is important in many applications including cancer and virus evolution, which is why some software, including the popular BEAST packages, infer phylogenetic trees with timing information.
In this talk we will discuss why the choice of treespace (or distance measure) should depend on the application. In particular, we consider a definition of treespace for discrete versions of time trees, which have integer-valued branch lengths. Our definition of a metric space for trees is based on tree rearrangement operations that take times of internal nodes, i.e. evolutionary events in the tree, into account. Distances in these spaces can be computed efficiently, which leads us to discussing further properties of this distance measure and how it can be used in practice."
author4: "Tandy Warnow"
inst4: "University of Illinois Urbana-Champaign (Computer Science)"
title4: "New methods for very-large scale maximum likelihood tree estimation"
additional_authors4: "Paul Zaharias, Muséum National d’Histoire Naturelle, Paris France
Minhyuk Park, University of Illinois Urbana-Champaign"
abstract4: "Maximum likelihood estimation of phylogenetic trees is one of the basic analytical steps of many biological research projects involving evolutionary questions. With increasing amounts of sequence data, the interest in estimating large phylogenies, with up to hundreds of thousands, or even millions of sequences, is increasing. Yet these estimations are challenging, since maximum likelihood is NP-hard and standard heuristics (employed in leading software, such as RAxML-ng and IQ-TREE) are not designed for these ultra-large datasets. Recent work in my lab has produced alternative strategies based on divide-and-conquer for ultra-large maximum likelihood tree estimation that show potential to enable better results on very large datasets. Among these approaches are the 'Disjoint Tree Merger' methods (originally introduced by Erin Molloy) that operate in three stages: the input sequences are divided into disjoint sets, a tree is estimated on each set, and then the trees are merged into a tree on the full set using auxiliary information computed from the input. These Disjoint Tree Merger methods have strong theoretical guarantees (e.g., statistical consistency is maintained) and surprisingly good empirical performance on large datasets. In this talk I will present our progress using this approach on large biological datasets, and discuss future directions."
---
