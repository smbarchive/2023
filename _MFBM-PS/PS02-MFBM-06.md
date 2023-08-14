---
layout: group
poster: "MFBM-06"
day: "Thursday"
permalink: /MFBM/PS02-MFBM-6.html
code: "PS02"
subgroup: "MFBM"
author: "Furkan Kurtoglu"
inst: "Indiana University"
title: "Multiscale Agent-Based Modeling of Metabolic Crosstalk Between Colorectal Cancer Cells and Cancer-Associated Fibroblasts"
abstract: "Understanding altered metabolism in different conditions requires consideration of various connections across multiple scales. This project aims to understand the metabolic relationship between Colorectal Cancer Cells and Cancer-Associated Fibroblast (CAF). Firstly, an experimental workflow is designed to measure the effect of CAF presence on CRC metabolism. The Flux Balance Analysis (FBA) model is created using growth and metabolomic data. Next, 3-D multiscale agent-based model (ABM) is built to scale from a single cell level to dozens of organoids. We integrated the metabolic model as an FBA model to be employed as a chemical network in each agent. The multiscale model provides the spatial information, which is local substrate availabilities and cellular pressures, to be used as input to FBA. The metabolic model yields a biomass creation rate used as cellular volume growth in agents. Individual agents proliferate with adequate cellular volume and exchange rates for essential chemicals. The distribution of important metabolites in the 3-D domain is calculated by 3-D reaction-diffusion equations. However, the whole computational framework is expensive; therefore, we enhanced our framework with a surrogate model and multiple domains. The metabolic model portion of the simulation is speeded up with a deep neural network (DNN) which is trained by high throughput pre-run FBA model screens. Other acceleration is gained by coarsening the microenvironment domain, which does not contain cells. Multiscale simulations have matched with experimental growth rates. Overall, we combine multiple scales from the molecular level to the 3-D experimental well-containing hundreds of thousands of cells. High-throughput simulations with multiscale knockdowns will help us understand the altered metabolism and discover important targets to diminish this metabolic relationship."
additional_authors: "Niki Tavakoli, University of Southern California; Emma Fong, Ellison Institute; Kali Konstantinopoulos, Indiana University; Randy Heiland, Indiana University; Nicholas A Graham, University of Southern California; Shannon M Mumenthaler, Ellison Institute; Stacey D Finley, University of Southern California; Paul Macklin, Indiana University"
---
