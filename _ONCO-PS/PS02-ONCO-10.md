---
layout: group
poster: "ONCO-10"
day: "Thursday"
permalink: /ONCO/PS02-ONCO-10.html
code: "PS02"
subgroup: "ONCO"
author: "Megan LaMonica"
inst: "The University of Texas at Austin"
title: "Investigating limits of predictability of a 3D reaction-diffusion glioblastoma model"
abstract: "Introduction: Predictive mathematical models of glioma growth and therapy response can be informed with quantitative magnetic resonance imaging (MRI) data [1]. However, it is unclear what quantity and quality of longitudinal MRI data are required for accurate model calibration and prediction. To address this uncertainty, we utilize a novel in silico framework that explores the predictability limits of a spatiotemporal reaction-diffusion glioma model by quantifying how different combinations of signal-to-noise ratio (SNR), spatial resolution (SR), and temporal resolution (TR) in initial murine MRI data affect accuracy of parameter calibration and tumor growth prediction.
Methods: We have developed a two-species reaction-diffusion glioma model that describes the spatiotemporal evolution of tumor cellularity and vascularity [2]. The initial cellularity and vascularity conditions that inform the model are estimated from quantitative MRI data. Different combinations of SNR, SR, and TR are applied to the initial conditions. TR is varied by changing the quantity and spacing of the MRI data used to inform parameter calibration. We apply the model to a spatially heterogeneous rat tumor in a simulated brain tissue domain [3]. We then solve the model via the finite difference method and calibrate model parameters using the Levenberg-Marquardt algorithm (N = 50 in silico replicates). We report the mean and standard deviation of each model parameter error as well as error in longitudinal tumor volume prediction for each tested combination of SNR, SR, and TR.
Results and future directions: Low SR (voxel volume 0.500 mm3), experimentally relevant SR (voxel volume 0.063 mm3), and high SR (voxel volume 0.008 mm3) conditions are evaluated across a range of TR and SNR for all model parameters. The worst TR case uses two calibration timepoints, 96 hours apart; the experimentally relevant case uses three timepoints, 48 hours apart; and finally, the best case uses five timepoints, 24 hours apart. SNR is tested from 5 to 160. At an experimentally relevant SNR of 40, calibrated parameter percent error (PE) in tumor diffusion and proliferation falls by approximately 75% as SR improves. PE falls by approximately 37% as TR improves in this same SNR case. With SR held constant at the 0.063 mm3 voxel volume SR condition, PE decreases by approximately 40% between an SNR of 20 and 40, with little improvement seen past an SNR of 80. Global concordance correlation coefficients and Dice similarity coefficients were relatively consistent across all tested combinations. The next step will be to evaluate the model with different ground truth tumors in order to recommend target combinations of SR, TR, and SNR for a wider range of tumor types and experimental conditions.
Funding: CPRIT RR160005, RP220225; NIH R01CA235800, U24CA226110, U01CA174706. 
References: [1] Hormuth et al., Advanced Drug Delivery Reviews, 187(114367), 2022. [2] Hormuth et al., Cancers, 13(8), 2021. [3] Hormuth et al., Ann. Biomed. Eng., 47(7), 2019."
additional_authors: "Thomas E. Yankeelov (1-5); David A. Hormuth, II (2-5)
1. UT Austin Department of Biomedical Engineering; 2. Oden Institute for Computational Engineering and Sciences; 3. Diagnostic Medicine, 4. Oncology, and 5. Livestrong Cancer Institutes

"
---
