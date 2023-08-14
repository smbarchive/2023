---
layout: group
poster: "ONCO-09"
day: "Thursday"
permalink: /ONCO/PS02-ONCO-9.html
code: "PS02"
subgroup: "ONCO"
author: "Matthew Froid"
inst: "H. Lee Moffitt Cancer Center and Research Institute"
title: "A Hybrid Modeling Approach Illuminates Physical and Genetic Factors Contributing to Resistance in the AML Bone Marrow Niche"
abstract: "BACKGROUND: Acute myeloid leukemia (AML) outcomes remain poor, likely due to treatment-resistant leukemic stem cells (LSCs). Evidence suggests resistance to tyrosine kinase inhibitors (TKIs) depends on the bone marrow’s vascular plasticity via the Janus Phenomena. The opposing “faces” of the Janus Phenomena are the initial beneficial cytoreduction of blast cells, followed by revascularization of the BM by endothelial cells, the expansion of LSCs, and then relapse. This is partially mediated through miR-126 over-expression upon which the endothelial cells are dependent to revascularize the BM and to shelter LSCs. To mitigate the Janus Phenomena, miRisten, a miR-126 expression inhibitor, was developed. To understand the interactions of TKI with miRisten, we used experimental data to inform an agent-based model (ABM) recapitulating the Janus Phenomena to explore how different vasculature architectures and drug scheduling can prevent relapse. In addition to the BM structure, we explored common interactors among genes linked to both drugs (AC220, a TKI, and miRisten).
METHODS: Using an on-lattice 2D ABM containing three agents (EC cells, LSCs, and blast cells), we modeled 16 different vascular architectures informed from mouse tibias post-TKI treatment. We tested three conditions: TKI, TKI + miRisten, and TKI + miRisten pre-treatment. K-means clustering and PCA were performed to determine relationships among the varying vascular architectures. A protein-protein interaction (PPI) network based on publicly available data for the proteins affected by both drugs was constructed. We used several centrality measurements to determine the nodes in the directed graph that have the largest role in the connectivity of the network. Next we constructed a graph neural network to classify proteins linked to either the targets of AC220 or miRisten with limited or tenuous experimental validation.
RESULTS: The optimal dose strategy to prevent relapse was two-weeks of pre-treatment with mRristen before TKI administration. Additionally, vascular architectures spanning the entire domain of the ABM consistently prevented relapse during treatment. Interestingly within the drugs’ PPI, miR-206 (a known tumor suppressor linked to angiogenesis and an indirect regulator of miR-126) was the node with the highest degree centrality.
CONCLUSION: To prevent AML relapse under TKI, miRisten should be given for two weeks before starting TKI. Additionally, both the physical structure of the vasculature and the protein-protein interactors contribute to resistance."
additional_authors: "David Basanta, H. Lee Moffitt Cancer Center and Research Institute; Aleksandra Karolak, H. Lee Moffitt Cancer Center and Research Institute; Russ Rockne, City of Hope; Bin Zhang, City of Hope; Guido Marcucci, City of Hope"
---
