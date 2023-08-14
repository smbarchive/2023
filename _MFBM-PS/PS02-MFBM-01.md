---
layout: group
poster: "MFBM-01"
day: "Thursday"
permalink: /MFBM/PS02-MFBM-1.html
code: "PS02"
subgroup: "MFBM"
author: "Anna-Dorothea Heller"
inst: "Max Planck Institute of Colloids and Interfaces, Potsdam, Germany"
title: "A stochastic Cellular Automaton Model to simulate Bone Remodeling"
abstract: "Bone remodeling is a very complex and fine-tuned process, which is necessary to ensure a healthy bone structure. If this process gets out of balance – e.g., because of hormonal disbalance or the impact of bone metastases – pathologies like osteoporosis can appear. In this contribution we introduce a novel computational approach to investigate this balance by connecting the bone remodeling process with its microenvironment. Our goal is to better understand the well-balanced and complex dynamic of the subprocesses involved in healthy bone remodeling.

We implement a 3D stochastic cellular automaton (SCA), where voxels interact only with their nearest neighbors in a scaffold representing bone tissue. At each time point, each voxel can take one of four different states that stand for the different phases of bone remodeling: formation, quiescent bone, resorption, and environment. To create a compact representation of the frequency-dependent interaction of those voxel states we make use of methods borrowed from evolutionary game theory for the update rule of the cellular automaton [1]. This representation encodes knowledge about the mutual impact the different actors of bone remodeling (osteocytes, osteoclasts and osteoblasts) have on each other. Each parameter in the model has therefore a direct connection to the biological processes.
First, we set up simulations of the model with either only resorption or only formation. This choice reduced the model complexity and allowed us to determine parameter spaces for a self-regulating behavior for each of them. The self-regulating behavior is defined by resorption or formation starting and ending without further parameter tuning. Parameters outside the range of self-regulation will lead to either osteolytic lesions (resorption) or heterotopic ossification (formation). Further analyses supported the approach of a spatial model with a small neighborhood to simulate the local phenomena observed in bone remodeling. 
Next, we coupled the two processes of resorption and formation. In the limit of separation of time scales, our model showed that self-regulating resorption followed by self-regulating formation reproduces the physiological bone remodeling behavior. Further analysis will create a more fluid coupling of the two processes while involving more parameters.

The model has the potential to use the role of the microenvironment to evaluate the impact of additional factors, such as drugs or bone metastases. We are planning on using experimental in vivo data from a breast cancer bone metastasis mouse model [2], which includes spatial and temporal dynamic of early osteolytic lesions, to fit additional parameters. Hopefully, these findings will add to the discussion, how pathological behavior might be controlled, if not even reversed. 

[1] M. D. Ryser and K.A. Murgas, Bone remodeling as a spatial evolutionary game, Journal of Theoretical Biology, 2017

[2] S. A. E. Young, A.-D. Heller et al., From breast cancer cell homing to the onset of early bone metastasis: dynamic bone (re)modeling as a driver of osteolytic disease, bioRxiv preprint
"
additional_authors: "Angelo Valleriani (Max Planck Institute of Colloids and Interfaces, Potsdam, Germany);
Amaia Cipitria (Biodonostia Health Research Institute, San Sebastian, Spain, IKERBASQUE, Basque Foundation for Science, Bilbao, Spain and Max Planck Institute of Colloids and Interfaces, Potsdam, Germany);
Sarah. A. E. Young (Max Planck Institute of Colloids and Interfaces, Potsdam, Germany)"
---
