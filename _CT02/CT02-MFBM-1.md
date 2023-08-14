---
layout: group
author: smb2023
day: "Tuesday"
room: "Student-Alumni Council Room (#2154)"
code: "CT02"
subgroup: "MFBM"
subgroup-long: "MFBM-1"
title: "MFBM Subgroup Contributed Talks"
author1: "Anna Konstorum"
inst1: "Institute for Defense Analyses"
title1: "A decomposition as a model: extracting mechanistic information from high-throughput time-course data using tensor dictionary learning"
abstract1: "Matrix decomposition methods such Principal Components Analysis (PCA) and Non-Negative Matrix Factorization (NMF), as well as non-linear analogues such as t-SNE and UMAP, have become increasingly popular in bioinformatics to perform data dimension reduction. For data that includes a time-course, a more natural representation is as a tensor (a multi-index array). We show that one can reframe the tensor decomposition of sample-by-feature-by-time-course data as a tensor dictionary learning problem, which effectively models each subject as a sum of rank-one matrices we term 'Feature Canonical Trajectories' (FCTs). The benefits of the FCT representation is that it provides not only an embedding and clustering of subjects, but also a model for the data by representing subject gene expression data as a linear combination of canonical trajectories of feature-sets. We show that by reframing the decomposition as a data model we can also identify new metrics to choose a decomposition algorithm and approximation for improved interpretability, and provide an example of this in action by identifying a novel age-specific FCT associated with platelet vaccination response data."
additional_authors1: ""
author2: "Dewayne A. Dixon"
inst2: "Howard University"
title2: "Core Epigenetic Module Biomarkers among Various PTSD Subtypes"
abstract2: "Posttraumatic stress disorder (PTSD) is a debilitating condition triggered by traumatic events. Notable symptom differences exist between combat-exposed veterans, active-duty personnel, and civilian PTSD cases. However, the underlying biological mechanisms remain elusive. This study aims to uncover the shared biological core modules associated with PTSD by leveraging extensive omics data among various PTSD subtypes. To achieve this, we employed the 'COre Module Biomarker Identification with Network ExploRation' (COMBINER) approach on DNA methylation data to identify key network modules of epigenetic modification across PTSD subtypes. These findings not only enhance our knowledge of PTSD's diverse symptomatology but also pave the way for the development of biomarkers and personalized treatments."
additional_authors2: "Yeona Kang, Department of Mathematics at Howard University, Washington D.C. 
Routing Yang, Medical Readiness Systems Biology, Walter Reed Army Institute of Research, Silver Spring, MD, USA"
author3: "Heber L Rocha"
inst3: "Indiana University"
title3: "Multiscale Modeling and Data Assimilation: A Path to Personalized Medicine"
abstract3: "In recent years, a growing interest in personalized medicine has emerged as a result of significant advancements in the fields of biology, data science, and computational modeling. One emerging concept that has obtained attention from the scientific community is the patient digital twin (DT), which aims to develop a comprehensive model to enable clinicians to systematically analyze the complexity of each patient, simulate treatment outcomes, and select the optimal treatment option. Constructing a patient digital twin (DT) involves creating a detailed computational model that can capture the unique characteristics of an individual patient. The model should include information about the patient's medical history, current health status, genetic makeup, and other relevant factors that can affect treatment outcomes. However, obtaining all this information can be challenging, as clinical data on individual patients is often limited. To overcome this limitation, researchers can use mechanistic models to replicate observed phenomena across various scenarios.

In this study, we developed a mechanistic model of cancer-immune interactions in pulmonary micrometastasis. We found that the model could express a wide range of patient trajectories, from complete tumor elimination to uncontrollable growth. Using high-throughput computing platforms, we analyzed 100k virtual patient trajectories by exploring the parameter space of this model. Initially, we analyzed patient data at a single time point using clustering methods, but the results did not clearly identify patient trajectories. Further investigation revealed that the same patient could have completely different trajectories, making it challenging to categorize patients. The mechanistic model helped us understand this issue, showing that early or non-interactions between macrophages and invading tumor cells were responsible. This also explained the limitations of traditional patient stratification based on data alone. Additionally, it highlighted the need for digital twins that are patient-specific, dynamical, and continuously updated with new patient data instead of one-time calibration."
additional_authors3: "Boris Aguilar, Institute for Systems Biology; Michael Getz, Indiana University; Tina Hernandez-Boussard, Stanford University; Ilya Shmulevich, Institute for Systems Biology; Paul Macklin, Indiana University"
author4: "Hyun Kim"
inst4: "Institute for basic science"
title4: "Enhancing dimensionality reduction in single-cell RNA sequencing: a novel tool for improved preprocessing and noise filtering"
abstract4: "Single-cell RNA sequencing (scRNA-seq) has enabled various analyses, including cellular phenotyping and gene regulatory network reconstruction. However, the sparsity, high dimensionality, bias, skewness in data distribution, and technical noise in scRNA-seq data present challenges for downstream analyses. In order to tackle these issues, conventional packages depend on log-normalization for preprocessing and require users to select the reduced dimension when employing various dimensionality reduction methods. Nonetheless, these approaches can result in signal distortion and subjectivity when determining reduced data dimensions.
To overcome the limitation of conventional methods, we developed a new tool that corrects signal distortion during preprocessing and effectively filters out noise in data, enhancing the reliability of the outcome of dimensionality reduction. Our tool demonstrated superior performance compared to 9 widely used packages, including Seurat, Scanpy, and Monocle3 when tested on 53 real and simulated datasets."
additional_authors4: "JongEun Park, MinSeok Seo, JaeKyoung Kim"
---
