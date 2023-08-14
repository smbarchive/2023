---
layout: group
poster: "ONCO-07"
day: "Monday"
permalink: /ONCO/PS01-ONCO-7.html
code: "PS01"
subgroup: "ONCO"
author: "John Metzcar"
inst: "Indiana University"
title: "​​​​Using multiscale simulations to assess solutions to the Boolean network target control problem"
abstract: "Boolean networks, or logical models, are proven methods for simulating a cell’s response to its environment [1], [2]. In these models, nodes represent components of the system, such as genes or proteins, and an edge from a “parent” node to a “child” node indicates that the parent has a causal influence on the child, such as a transcription factor activating a gene. Each node is assigned a time-varying binary variable that can be ON (representing presence or activity of the system component) or OFF (representing its absence or inactivity). Often, a node state (or set of node states) is taken to represent a cellular behavior of interest. In the context of Boolean networks, the process of identifying interventions that lead to a particular cellular behavior (encoded as node states that represent known phenotypic markers) is called the target control problem [3], [4]. We address this problem in selected cancer-related Boolean networks by developing and applying a new method for edgetic perturbations, which involves intervening in specific interactions (e.g., analogous to blocking specific binding sites) rather than suppressing entire biomolecules. We separately determine node interventions solving the target control problem using two previously published methods: one based on a mean field approximation and a second, percolation-based method [5], [6]. We then implement the identified node and edge interventions in a multiscale context using the combined agent-based and Boolean network simulator PhysiBoSS [7], [8]. Using this approach, we test the effectiveness of the interventions devised in an isolated, single-cell context in a more realistic in silico environment that can account for spatial features (such as chemical gradients), heterogeneity of signal response in cell populations, and cell-cell interactions. 

[1] A. A. Hemedan, A. Niarakis, R. Schneider, and M. Ostaszewski, “Boolean modelling as a logic-based dynamic approach in systems medicine,” Computational and Structural Biotechnology Journal, vol. 20, pp. 3161–3172, Jan. 2022, doi: 10.1016/j.csbj.2022.06.035.
[2] J. D. Schwab, S. D. Kühlwein, N. Ikonomi, M. Kühl, and H. A. Kestler, “Concepts in Boolean network modeling: What do they all mean?,” Computational and Structural Biotechnology Journal, vol. 18, pp. 571–582, 2020, doi: 10.1016/j.csbj.2020.03.001.
[3] J. C. Rozum, D. Deritei, K. H. Park, J. Gómez Tejeda Zañudo, and R. Albert, “pystablemotifs: Python library for attractor identification and control in Boolean networks,” Bioinformatics, vol. 38, no. 5, pp. 1465–1466, Mar. 2022, doi: 10.1093/bioinformatics/btab825.
[4] C. Su and J. Pang, “A Dynamics-based Approach for the Target Control of Boolean Networks,” in Proceedings of the 11th ACM International Conference on Bioinformatics, Computational Biology and Health Informatics, in BCB ’20. New York, NY, USA: Association for Computing Machinery, Nov. 2020, pp. 1–8. doi: 10.1145/3388440.3412464.
[5] T. Parmer, L. M. Rocha, and F. Radicchi, “Influence maximization in Boolean networks,” Nature Communications, vol. 13, no. 1, p. 3457, Jun. 2022, doi: 10.1038/s41467-022-31066-0.
[6] J. G. T. Zañudo and R. Albert, “Cell Fate Reprogramming by Control of Intracellular Network Dynamics,” PLOS Computational Biology, vol. 11, no. 4, p. e1004193, Apr. 2015, doi: 10.1371/journal.pcbi.1004193.
[7] G. Letort et al., “PhysiBoSS: a multi-scale agent-based modelling framework integrating physical dimension and cell signalling,” Bioinformatics, vol. 35, no. 7, pp. 1188–1196, Apr. 2019, doi: 10.1093/bioinformatics/bty766.
[8] M. Ponce-de-Leon et al., “PhysiBoSS 2.0: a sustainable integration of stochastic Boolean and agent-based modelling frameworks.” bioRxiv, p. 2022.01.06.468363, Mar. 27, 2023. doi: 10.1101/2022.01.06.468363.
"
additional_authors: "Jordan Rozum, SUNY-Binghamton University; Paul Macklin, Indiana University"
---
