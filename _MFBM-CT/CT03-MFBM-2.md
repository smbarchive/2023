---
layout: group
author: smb2023
day: "Thursday"
room: "Cartoon Room 2 (#3147)"
code: "CT03"
subgroup: "MFBM"
subgroup-long: "MFBM-2"
title: "MFBM Subgroup Contributed Talks"
author1: "Jordan Collignon"
inst1: "University of California, Merced"
title1: "[PSI]-CIC: A Deep-Learning Pipeline for the Annotation of Sectored Saccharomyces cerevisiae Colonies"
abstract1: "The [PSI^+] prion phenotype in yeast manifests as a white, pink, or red color pigment related to the fraction of soluble Sup35. Experimental manipulations destabilize prion phenotypes, and allow colonies to exhibit [psi^-] (red) sectored phenotypes within otherwise completely white colonies. The mechanisms governing both size and quantity of sectors remain unknown. Images of experimental yeast colonies exhibiting sectored phenotypes offer an abundance of data to help uncover mechanisms of sectoring. However, the structure of sectored colonies is ignored in traditional biological pipelines. This is both because colony counting is labor intensive and procedures for characterizing sectored colonies do not exist. In this study, we present [PSI]-CIC, the first computational pipeline designed to identify and characterize features of sectored yeast colonies. We develop a neural network architecture that we train on synthetic images of sectored yeast colonies and apply to real images of [PSI^+], [psi^-], and sectored colonies. Our pipeline correctly predicts the colony state and frequency of sectors in approximately 89.2% of colonies detected in hand annotated experimental images. With this information, the scope of our pipeline can be later extended toward categorizing colonies grown under different experimental conditions, allowing for more meaningful and detailed comparisons between experiments performed on yeast. Our approach aims to streamline the analysis of sectored yeast colonies providing a rich set of quantitative metrics to compare with mathematical models of sector formation and provide insights into mechanisms driving the curing of prion phenotypes."
additional_authors1: "Wesley Naeimi, University of Massachusetts, Amherst; Tricia Serio, University of Massachusetts, Amherst; Suzanne Sindi, University of California, Merced"
author2: "Md Masud Rana"
inst2: "University of Kentucky"
title2: "Differential geometry and graph theory-based machine-learning model for drug design"
abstract2: "The fundamental step in the drug design and discovery process is understanding and accurately predicting the binding affinity between a drug candidate (ligand) and its receptor protein. Machine learning-based methods have become increasingly popular in this regard due to their efficiency and accuracy, as well as the growing availability of data on the structure and binding affinity of protein-ligand complexes. In molecular and biomolecular studies, differential geometry and graph theory are widely used to analyze vast, diverse, and complex datasets. Using molecular surface representation, crucial chemical and biological data can be encoded in differentiable manifolds that can reduce dimensionality. Graph theory is extensively used in biomolecular research because molecules or molecular complexes can be naturally modeled as graphs. Here, we will present several models based on differential geometry and graph theory that can be combined with advanced machine learning techniques to predict protein-ligand binding affinity with high accuracy. Our proposed models have demonstrated superior performance compared to numerous state-of-the-art models on established benchmark datasets."
additional_authors2: "Duc Duy Nguyen, Department of Mathematics, University of Kentucky."
author3: "Theo Loureaux"
inst3: "University of California Merced"
title3: "Automating the Generation of Synthetic Training Data for Biological Image Segmentation"
abstract3: "Image segmentation, the identification of specific objects from a larger image, is an important topic in computer vision and is critical to the study of biological and medical images. Common deep-learning approaches for image segmentation require large sets of labeled training-data. For many biological applications, annotated training data is not available and, as such, developing synthetic data sets - where the true labels are known - has become a standard approach in these methods. However, most methods of synthetic data generation often require substantial human intervention to create. This work takes a first step towards a fully-automated method for the segmentation of complex biological images.

In this talk, we present an iterative greedy algorithm that automates the selection of boundary points on a particular object, regardless of the complexity of its shape, by calculating the approximate solution to an optimization problem. We first demonstrate on a large set of curated shapes of various complexity that our algorithm generally does a better job than a naive approach, especially when the boundary of the shape is complex. We then apply our approach to the image segmentation in two biological contexts: identification of prion oligomers in AFM images, the identification of sectored yeast colonies. We show that our approach provides improvements to standard pipelines, and that greater improvements are possible by adding image artifacts - such as pixellization and sector coloring. Our work demonstrates that significant improvements can be made in biological image segmentation through the computational efficient generation of realistic synthetic samples. 

Keywords : Image segmentation, deep learning, synthetic images, automation, prions, yeast"
additional_authors3: "Dr. Laurent Pujo-Menjouet ; Dr. Suzanne Sindi"
---
