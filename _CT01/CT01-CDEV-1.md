---
layout: group
author: smb2023
day: "Monday"
room: "Brutus Buckeye Room (#3044)"
code: "CT01"
subgroup: "CDEV"
subgroup-long: "CDEV-1"
title: "CDEV Subgroup Contributed Talks"
author1: "David Holloway"
inst1: "British Columbia Institute of Technology"
title1: "Size regulation of the lateral organ initiation zone and its role in determining cotyledon number in conifers"
abstract1: "Unlike most flowering plants, which have one or two cotyledons (embryonic leaves), many conifers form three or more cotyledons. These are arranged in a whorl, or ring, at a particular distance from the embryo tip. The number of cotyledons, nc, varies substantially within species, even in clonal cultures. nc variability reflects embryo size variability, with larger diameter embryos having higher nc. The radius of the whorl varies over three-fold for the naturally observed range of nc. In the model plant Arabidopsis, the initiation zone for leaf primordia occurs at a minimum between inhibitor zones of HD-ZIP III at the shoot tip and KANADI (KAN) encircling this farther from the tip. A similar mechanism is indicated in conifer embryos by the effects of overexpression of HD-ZIP III inhibitors on cotyledon formation. We developed a PDE model of HD-ZIP III / KAN spatial localization and used this to characterize the molecular regulation that could generate (a) the three-fold whorl radius variation (and associated nc variability) observed in conifer cotyledon development, and (b) the HD-ZIP III and KAN shifts induced experimentally in conifer embryos and in Arabidopsis. The model was used to find the sensitivity of mechanism components for positioning lateral organs (cotyledons or leaves) closer to or farther from the tip. Positional shifting is most readily driven by changes to the spatial extent of upstream regulator patterns and changes in HD-ZIP III / KAN mutual inhibition, and less efficiently driven by changes in upstream dosage or the activation kinetics of HD-ZIP III. Sharper expression boundaries can also be more resistant to shifting than shallower expression boundaries. The strong variability in whorl size reflected in conifer nc (commonly from 2 to 10) may indicate a freer variation in regulatory interactions, whereas flowering plants, with nc = 1 or 2, may require tighter control of such variation. The variability in conifer whorl size may have similarities to spatial scaling in fly embryos in which gene expression pattern variation compensates for embryo length variability. The model provides a framework for quantitative experiments on the positional control of lateral organ initiation. This could further understanding of the factors that control the leaf arrangements, or phyllotaxy, characteristic of species."
additional_authors1: "Rebecca Saunders, BCIT Biotechnology; Carol Wenzel, BCIT Biotechnology
"
author2: "Merlin Pelz"
inst2: "University of British Columbia"
title2: "The Emergence of Spatial Patterns with Diffusion-Coupled Compartments with Activator-Inhibitor Kinetics in 1-D and 2-D"
abstract2: "Since Alan Turing’s pioneering publication on morphogenetic pattern formation obtained with reaction-diffusion (RD) systems, it has been the prevailing belief that two-component reaction diffusion systems have to include a fast diffusing inhibiting component (inhibitor) and a much slower diffusing activating component (activator) in order to break symmetry from a uniform steady-state. This time-scale separation is often unbiological for cell signal transduction pathways.
We modify the traditional RD paradigm by considering nonlinear reaction kinetics only inside compartments with reactive boundary conditions to the extra-compartmental space which diffusively couples the compartments via two species. The construction of a nonlinear algebraic system for all existing steady-states enables us to derive a globally coupled matrix eigenvalue problem for the growth rates of eigenperturbations from the symmetric steady-state, on finite domains in 1-D and 2-D and a periodically extended version in 1-D.
We show that the membrane reaction rate ratio of inhibitor rate to activator rate is a key bifurcation parameter leading to robust symmetry-breaking of the compartments. Illustrated with Gierer-Meinhardt, FitzHugh-Nagumo and Rauch-Millonas intra-compartmental reaction kinetics, our compartmental-reaction diffusion system does not require diffusion of inhibitor and activator on vastly different time scales. Bifurcation theoretic results for symmetric and asymmetric steady-state patterns obtained from our asymptotic theory are confirmed with full numerical PDE simulations.
Our results reveal a possible simple mechanism of the ubiquitous biological cell specialization observed in nature."
additional_authors2: "joint work with Prof. Michael J. Ward (UBC)"
author3: "Renee Dale"
inst3: "Donald Danforth Plant Science Center"
title3: "Competition for resources during semi-sequential growth of developmental units drive allometric patterns in the grass Setaria"
abstract3: "Resource allocation drives the above-ground distribution of mass in grass plants across discrete developmental units called phytomers. Although the number of phytomers varies in genetically-identical grasses, plants with relatively more phytomers may not exhibit an increase in total biomass or height. To understand what may be driving this, we tracked the growth of 30 S. italica plants from genotypes B100 and A10.1. We experimentally observed that plants from the genotype B100 had between 20 and 22 phytomers, while plants from the genotype A10.1 had between 7 and 9 phytomers. B100 plants with more phytomers (e.g., 22) did not grow taller or have more total leaf length, despite having more leaves than plants with fewer phytomers (e.g., 20). A10.1 plants with more phytomers (e.g., 9) did grow taller and had more total leaf length than those with fewer phytomers (e.g., 7). We developed a dynamical model to determine if these patterns are emergent from the underlying growth structure. The model is parameterized using the number of phytomers and related developmental time parameters: leaf emergence, stem and leaf elongation time, and time of panicle emergence. The model uses the semi-sequential nature of phytomer growth as its structure. The model predicts that the number of phytomers, the length of time each phytomer grows, and the shift to reproductive growth determines the allometric patterns. Together, model and data suggest that allometric patterns are driven by competition for resources between phytomers and the shift to reproductive growth in Setaria. These results are further developed using 5 additional Setaria genotypes, and through exploration of predicting developmental time parameters from growth curves obtained in high-throughput."
additional_authors3: "Darshi Banan; Ivan Baxter; Shankar Mukherji"
author4: "Samantha Ivings"
inst4: "University of Sheffield"
title4: "Connecting abstract maths to cell biology: A novel vertex model for predicting pluripotent stem cell lineage decisions, capturing cell symmetries through internal node dynamics"
abstract4: "Human pluripotent stem cells (hPSCs) are vastly promising for regenerative medicine, as they can self-renew indefinitely in vitro and become any cell type in the human body. Therefore, patients with damaged or lost tissue could be effectively treated by growing hPSCs into the required cell type for treatment.
Unfortunately, how hPSCs make lineage decisions remains poorly understood. The process by which hPSCs acquire lineage is called differentiation, and a cell’s progress along this journey can be measured by its expression levels of genetic markers. At present, allowing cells to freely differentiate yields seemingly heterogeneous lineage patterning across unconstrained cultures.
A ground-breaking study by Warmflash et al. (2014) showed that differentiating hPSCs spatially confined on discs yields reproducible lineage patterning across the cell culture, in the form of concentric rings. Later, Muncie et al. (2019) demonstrated reproducible patterning by differentiating hPSCs on a wider range of controlled geometries. How single hPSCs orchestrate these phenomena remains an interesting question.
In this work, a novel cell-level modelling approach is proposed for explaining lineage patterning on controlled culture geometries. An undirected vertex model is introduced, where nodes represent single hPSCs. Cells are ‘neighbours’, and therefore share an edge, if their membranes are in contact. Nodes have internal dynamics in the form of an ordinary differential equation system, representing gene networks. These dynamics capture novel symmetry relations between nodes. Mimicking cell morphology in vitro, each node is represented by a Voronoi object which together tile the simulated geometry. Simulations of cell equilibria recapitulate experimental results, supporting that culture geometries may be designed to control lineage at low expense.
The model is further developed by initialising a single cell with stochastic division until the culture is fully populated. Tracking the trajectory of each cell’s dynamics is hoped to provide insight into how different lineage paths are explored before each cell fully commits in the robust process of embryogenesis."
additional_authors4: "Daniel Coca"
---