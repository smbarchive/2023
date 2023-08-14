---
layout: group
author: smb2023
day: "Thursday"
room: "Interfaith Prayer & Reflection Room (#3020C)"
code: "CT03"
subgroup: "ECOP"
subgroup-long: "ECOP-1"
title: "ECOP Subgroup Contributed Talks"
author1: "Anastasios Stefanou"
inst1: "Institute for Algebra, Geometry, Topology and their Applications, University of Bremen"
title1: "Topological Data Analysis and Phylogenetics"
abstract1: "In the real world, mutations of genetic sequences are often accompanied by their recombinations. Such joint phenomena are modeled by phylogenetic networks. These networks are typically generated or reconstructed from coalescent processes that may arise from optimal merging or fitting together a given set of phylogenetic trees. L. Nakkleh formulated the phylogenetic network reconstruction problem (PNRP) as follows: Given a family of phylogenetic trees over a common set of taxa, is there a unique minimal phylogenetic network whose set of spanning trees contains the family? There are different answers to PNRP, since there are different ways to define what a “minimal network” is (based on different optimization criteria).
Inspired by ideas from topological data analysis (TDA) (i.e. filtered simplicial complexes), we devise a simplicial lattice-model for modeling phylogenetic networks, called the cluttergram, that generalizes the dendrogram (filtered partition) model of phylogenetic trees. We show that the collection of all cluttergrams over the same set of taxa (leaves) forms a lattice. This lattice-model allows us to solve the PNRP in a mathematically rigorous way and in a way that is free of choosing optimization criteria for the reconstruction process. The solution to the phylogenetic network reconstruction process is obtained by taking the join operation of the dendrograms on the lattice of cluttergrams (by viewing dendrograms as cluttergrams). Furthermore, we show that computing the join-cluttergram from a given set of dendrograms is polynomial in the size and the number of the input trees (dendrograms). 
Moreover, motivated by the tool of persistence diagram in topological data analysis, we introduce an invariant of cluttergrams, called the mergegram, by extending the corresponding construction that was defined by Elkin and Kurlin on dendrograms. Then, we show that the mergegram is a 1-Lipschitz stable invariant of cluttergrams. This new TDA-signature of phylogenetic networks enable us to utilize standard statistical pipelines (vectorization and machine learning) to study phylogenetic networks. To illustrate the utility of these new TDA-tools to Phylogenetics, in this work we provide Python implementations of the introduced concepts and also experiments with certain benchmark biological datasets.
This is joint work with Pawel Dlotko and Jan Senge."
additional_authors1: "Pawel Dlotko, Dioscuri Centre for Topological Data Analysis, Institute of Mathematics of the Polish Academy of Sciences;
Jan Senge, Institute for Algebra, Geometry, Topology and their Applications, University of Bremen"
author2: "Kristina Wicke"
inst2: "New Jersey Institute of Technology"
title2: "Exploring spaces of semi-directed phylogenetic networks"
abstract2: "Phylogenetic networks are a generalization of phylogenetic trees allowing for the representation of speciation and reticulate evolutionary events such as hybridization or horizontal gene transfer. Traditionally, two types of phylogenetic networks were considered in the literature: unrooted (undirected) ones that are often used to represent conflict in data and rooted (directed) ones that explicitly depict evolution as a directed process. 
Recently, however, semi-directed phylogenetic networks have emerged as a class of phylogenetic networks sitting between rooted and unrooted phylogenetic networks since they contain directed and undirected edges. For example, software such as PhyloNetworks, NANUQ, and PhyNEST reconstructs semi-directed level-1 networks from biological data. However, in contrast to rooted and unrooted phylogenetic networks, little is known about searching spaces of semi-directed phylogenetic networks to find an optimal network. 
In this talk, we introduce semi-directed phylogenetic networks and related concepts. We then discuss a rearrangement move, called cut edge transfer (CET), and show that the space of semi-directed level-1 networks with a fixed leaf set and number of reticulations is connected under CET. Hence, every semi-directed level-1 network in this space can be transformed into any other such network by a sequence of CETs. By introducing two additional moves that allow for the addition and deletion of reticulations, we extend our results to semi-directed (level-1) network on a fixed leaf set. As a byproduct, we also obtain connectedness results for rooted level-1 networks under a rooted version of CET. 
"
additional_authors2: "Simone Linz (University of Auckland)"
author3: "Sarah Bogen"
inst3: "Utah State University"
title3: "A trait-based modeling approach to estimate global movement potential for plant populations in a warming planet"
abstract3: "Understanding the spatial and temporal dynamics of plant populations has important implications for the fields of ecology and conservation. A rich body of mathematical approaches have been developed to mechanistically model population spread based on species demography and seed dispersal patterns. However, with over 390,000 plant species on Earth, it is not feasible to collect complete information on all species for the purpose of making generalized conclusions. This problem may be addressed through trait-based modeling, which seeks to represent realistic combinations of organismal traits rather than focusing on individual species. In this work, I use a Bayesian multivariate approach to synthesize sparse datasets and estimate key demographic and dispersal parameters for a population of virtual species. I then use integrodifference equations to estimate population spreading speeds for virtual species and investigate links between movement-related extinction risk and easy-to-measure plant functional traits. This work demonstrates an example of how empirical data, statistical modeling, and mathematical modeling may be synthesized to advance understanding and inform decision-making in complex fields such a spatial ecology."
additional_authors3: "J. Bullock; R. Salguero-Gómez; N.G. Beckman"
---
