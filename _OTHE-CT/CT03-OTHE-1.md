---
layout: group
author: smb2023
day: "Thursday"
room: "Suzanne M. Scharer Room (##3146)"
code: "CT03"
subgroup: "OTHE"
subgroup-long: "OTHE-1"
title: "OTHE Subgroup Contributed Talks"
author1: "Chengyue Wu"
inst1: "University of Texas at Austin"
title1: "Optimization of a longitudinal imaging protocol to monitor the response of breast cancer to neoadjuvant therapy via Bayesian-based data assimilation"
abstract1: "Introduction: Neoadjuvant therapy (NAT) is considered the standard-of-care for locally advanced breast cancer. Recent studies indicated that magnetic resonance imaging (MRI) data acquired after the first 1-3 cycles of NAT can provide early prediction of breast cancer patient response. However, it remains to be determined when the best times are to collect the longitudinal images to maximize both predictive accuracy and patient convenience. In this study, we seek to establish an in silico framework to address this unmet need by integrating mechanism-based mathematical modeling with Bayesian-based data assimilation. 
Methods: A TNBC cohort (n = 139) from the ARTEMIS trial was used for this study. For each patient, longitudinal MRIs were collected before (MRI1), during (MRI2), and after (MRI3) the Adriamycin/Cyclophosphamide (A/C) NAT regimen. We have developed a mechanism-based mathematical model to make patient-specific predictions of TNBC response to the A/C therapy. In particular, the model is a reaction-diffusion equation describing the spatiotemporal change in tumor cellularity due to cell migration, proliferation, and treatment-induced death. We implemented the model with a Bayesian-based scheme: Using MRI1 for initialization and MRI2 for calculating the posterior distributions of model parameters, then making predictions at the end of A/C. The standard derivation (SD) of the predicted tumor volume was defined as the uncertainty. The difference between the mean of the predicted tumor volume and the MRI3 measurement was defined as the error. We then optimized to find the optimal day for collecting MRI2 that reduced the uncertainty and error of the model prediction at the completion of A/C. In particular, we generated synthetic data at candidate time points (termed MRI2*; i.e., time points at which we may want to collect additional MRI data) by fitting the model to all collected MRIs, recalibrated the model with the synthetic data MRI2* to make prediction at the completion of A/C, and then evaluated the corresponding prediction uncertainty and error. The date for MRI2* that minimized the prediction uncertainty and error is determined to be the optimal time point for the second imaging session.
Results: Preliminary implementation and tests were performed on one patient with tumor volumes derived from the imaging data. The Bayesian-based scheme calibrated the model using the clinically measured MRI1 and MRI2 (i.e., MRI2 at day 30). Comparing the model prediction of the residual tumor volume to the measurement of MRI3, the prediction uncertainty and error were 24.72% and 32.64%, respectively. The identified optimal time point for the mid-treatment imaging session, MRI2* at day 38, provided a minimal prediction uncertainty and error of 13.02% and 7.55%, respectively. Thus, the optimized date for the second MRI resulted in a 47.33% decrease in uncertainty and a 76.87% decrease in error for predicting the residual tumor volume at the end of A/C. 
Conclusion: These preliminary results demonstrate that our approach has the potential to identify the optimal time point for the second MRI scan of a longitudinal MRI protocol to improve the precision and accuracy of early prediction of TNBC patient response to NAT. Ongoing efforts include extending the implementation to 3D and applying it to more patients. 
Acknowledgments: NCI U01CA142565, U01CA174706, U24CA226110. CPRIT RR160005. Clinical trial NCT02276443. MDACC Moon Shot Program. MDACC-TACC-Oden Institute Consortium Pilot Project."
additional_authors1: "C.E. Stowers, UT Austin; Z. Xu, UT MD Anderson Cancer Center; C. Yam, UT MD Anderson Cancer Center; J.B. Son, UT MD Anderson Cancer Center; J. Ma, UT MD Anderson Cancer Center; G.M. Rauch, UT MD Anderson Cancer Center; T.E. Yankeelov, UT Austin, UT MD Anderson Cancer Center; E.A.B.F. Lima, UT Austin."
author2: "Cole Butler"
inst2: "North Carolina State University"
title2: "Partially functional resistance in gene drive control"
abstract2: "Gene drives (GDs) allow scientists to spread a genetic cargo into a target population, even if the cargo is harmful to the carrier organism. GD technology has immense promise in everything from conservation efforts to the control of mosquito-borne diseases. To spread, GDs exploit DNA repair mechanisms to duplicate themselves at the expense of a target gene. However, repair does not always occur as intended, and can produce alleles that are resistant to the GD. Resistance is one of the greatest threats to GD use in the wild and is difficult to study at appropriate scales within laboratory experiments. Current approaches to studying resistance have predominantly relied on a binary paradigm: resistant alleles are either functional or non-functional. Neither resistant allele can be targeted by the GD construct but only the former restores proper genetic functioning to the organism. In this study, we consider the contribution of resistant alleles that are partially functional, and therefore fall outside this paradigm. Partially functional resistance occurs when a resistant allele restores some—but not all—genetic functioning to the organism. Organisms carrying such alleles do not spread the GD as efficiently but may still incur heavy fitness costs. Using a coupled genetic population dynamics model, we study GD performance in a target population with partially functional resistance. In addition to extending the current theoretical framework used to study resistance, we also study the roles played by certain DNA repair mechanisms, making our work generalizable to many target organisms. We pay particular attention to GD performance in certain mosquito species of interest, such as the malaria mosquito Anopheles gambiae, and the dengue mosquito Aedes aegypti. This work provides a key next step in understanding how the mechanisms behind resistance can help or hinder GD success. Furthermore, our work can inform the development of GDs going forward so as to mitigate the risk of control failure due to resistance arising in target populations."
additional_authors2: "Sumit Dhole, North Carolina State University"
author3: "Daniel Cooney"
inst3: "University of Pennsylvania"
title3: "A PDE Model for Protocell Evolution and the Origin of Chromosomes via Multilevel Selection"
abstract3: "The origin of chromosomes was a major transition in the evolution of complex cellular life. In this talk, we model the origin of chromosomes by considering a simple protocell composed of two types of genes: a “fast gene' with an advantage for gene-level self-replication and a “slow gene' that replicates more slowly at the gene level, but which confers an advantage for protocell-level reproduction. Using a PDE to describe the effects of within-cell and between-cell competition, we find that the gene-level advantage of fast replicators casts a long shadow on the multilevel dynamics of protocell evolution: no level of between-protocell competition can produce coexistence of the fast and slow replicators when the two genes are equally needed for protocell-level reproduction. We find that introducing a “dimer replicator', a linked pair of the slow and fast genes, can allow for long-time coexistence under multilevel competition between fast, slow, and dimer replicators. Our results suggest that the formation of a simple chromosome-like dimer replicator can help to overcome the shadow of lower-level selection and work in concert with multilevel selection to promote coexistence of genes that compete under gene-level replication but are synergistic at a higher level of selection."
additional_authors3: "Fernando W. Rossine (Harvard University); Dylan H. Morris (University of California, Los Angeles); Simon A. Levin (Princeton University)"
author4: "Hayden Fennell"
inst4: "Indiana University Bloomington"
title4: "Computational Apprenticeship: A Constructivist Approach for Teaching Modeling and Simulation"
abstract4: "Over the past two decades, there has been growing recognition of the need for discipline-situated computational modeling and simulation pedagogy in post-secondary STEM curricula. However, current research in this area remains largely definitional and aspirational in nature, as there are limited empirical studies on how to best support the development of computational expertise in undergraduate students. Outside of computer science programs, a student's exposure to computing education often remains siloed within introductory programming courses that lack meaningful integration with disciplinary content. Furthermore, current practice in early undergraduate computational education in engineering programs tends to focus heavily on the procedural and technical aspects of programming knowledge rather than on the application of computation to problem-solving and design. Because the field of discipline-based computation is under-theorized, traditional instructional approaches have typically defaulted to teaching the cognitive aspects of computation. To build transferable skills and expertise, however, instructors can draw upon constructivist traditions by situating computation within disciplinary contexts. This talk presents computational apprenticeship (an application of the cognitive apprenticeship framework) as a constructivist research and practice framework for developing transferable computational expertise in the undergraduate STEM curriculum. Aspects of the computational apprenticeship model in practice are illustrated using examples from computational biology."
additional_authors4: "Joseph Lyon, Purdue University, Honors College (Engineering); Bobby Madamanchi, University of Michigan, School of Information; Alejandra Magana, Purdue University, Computer and Information Technology
"
---