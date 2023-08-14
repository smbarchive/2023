---
layout: group
author: smb2023
day: "Wednesday"
subgroup: "MEPI"
subgroup-long: "MEPI-1"
title: "Zoonotic Infectious Diseases Models"
organizers: "Rocio Caja Rivera, Iona McCabe, Dana Pittman, Linda J. Allen"
description: "A majority of emerging infectious diseases are zoonotic, spread from non-human animals to humans. Multiple hosts, vectors, and seasonality are common features in zoonoses. Therefore, identification of the roles of hosts and vectors and their behavior as well as the timing of control methods are important to public and global health. In this mini-symposium, the effects of seasonality on the emergence of two zoonoses are explored in models for Lyme disease in a tick-mouse cycle and avian influenza spread by migrating waterfowl. The life stages and behavior of ticks on the outcome of control and the identification of intermediate hosts, crucial in the spread of disease to humans, are also explored."
room: "Student-Alumni Council Room (#2154)"
code: "MS05"
author1: "Holly Gaff"
inst1: "Old Dominion University (Department of Biological Sciences)"
title1: "Understanding Ticks and Tick-borne Diseases through Agent-based Modeling"
additional_authors1: "Robyn Nadolny, Defense Centers for Public Health-Aberdeen
Alexis White, Suffolk County New York
Sara Benham, Old Dominion University"
abstract1: "Tick-borne diseases are on the rise worldwide, and there is a lot of interest to reduce the burden of these diseases. Ticks and tick-borne pathogens are not well studied partly owing to their challenging biology. The dynamics of tick-borne pathogens includes multi-year systems of weather, habitat, and environmental factors plus the availability of hosts required for each life stage. Mathematical models provide an ideal tool to explore this type of complex system by implementing the dynamics that are known and exploring the potential additional components that are less understood. A series of agent-based models will be presented that investigate tick-borne disease dynamics, control, and geographic spread. Each model was based on field and lab data, and the output from each help to identify future experiments."
author2: "Kat Husar & Dana C. Pittman"
inst2: "Duke University; Texas A&M University (School of Public Health Epidemiology and Biostatistics)"
title2: "Lyme Disease Models of Tick-Mouse Dynamics with Seasonal Variation in Births, Deaths, and Tick Feeding"
additional_authors2: "Kateryna Husar, Department of Statistical Science, Duke University; Johnny Rajala, Department of Computer Science, University of Maryland; Fahad Mostafa, Department of Mathematics and Statistics, Texas Tech University; Linda J. S. Allen, Department of Mathematics and Statistics, Texas Tech University."
abstract2: "Lyme disease is the most prevalent vector-borne disease in the United States impacting the
Northeast and Midwest at the highest rates. Recently, it has become established in southeastern and south-central regions of Canada. Lyme disease is passed by the black-legged tick, Ixodes scapularis, infected with
the Borrelia burgdorferi bacterium. One of the hosts most commonly fed on by I. scapularis is Peromyscus
leucopus, colloquially known as the white-footed mouse. Understanding this parasite-host interaction is
critical as P. leucopus is one of the most competent reservoirs for Lyme disease. The cycle of infection is
driven by larvae feeding on infected mice that molt into infected nymphs and then transmit the disease to
another susceptible host such as a mouse or human. Lyme disease in humans is generally caused by the bite
of an infected nymph. The main aim of this investigation is to study how demographic and seasonal variation
and diapause in tick births, deaths, and feedings impact the infection dynamics of the tick–mouse cycle.
To account for delays in molting and reproduction in the tick life cycle, we begin by formulating a system
of ordinary differential equations (ODEs) describing the transmission cycle between ticks and mice before
exploring the use of delay differential equations (DDEs) with fixed delays. Several different tick feeding rates
are discussed. We then formulate a new system of ODEs with a more realistic Erlang-distributed delay.
We also account for seasonal changes through periodic parameters that depend on the season (spring,
summer, fall, or winter). The ODE model is generalized to a new stochastic model with demographic and
seasonal variability, a continuous-time Markov chain (CTMC). We calculate and discuss the relevance of the
basic reproduction number, R0, for the ODE and DDE models in a constant environment and numerically
compute it for the ODE model in a seasonal environment. We also determine the numerical sensitivity of
R0, to the prevalence of infected nymphs and mice and to the density of infected nymphs to changes in
the parameters in the seasonal ODE model . Lastly, we use the CTMC model to investigate the probability
of Lyme disease emergence in a small infection-free population of ticks and mice when a few infected mice
or nymphs are introduced. The probability of disease emergence is highly dependent on the season the
infection is introduced and which species (ticks or mice) are introduced. The numerical results show that
introduction of infected mice during the summer has the highest probability of sustained infection and
disease emergence."
author3: "Katherine Royce"
inst3: "Harvard University (Law School)"
title3: "Mathematically predicting intermediate host species for emerging zoonoses"
additional_authors3: ""
abstract3: "Intermediate host species provide a crucial link in the emergence of zoonotic infectious diseases, serving as a population where an emerging pathogen can mutate to become human-transmissible. Identifying such species is thus a key component of predicting and mitigating future epidemics. Despite this importance, intermediate host species have not been investigated in much detail, and have generally only been identified by testing for the presence of pathogens in multiple candidate species. This talk will present a mathematical model able to identify likely intermediate host species for emerging zoonoses based on ecological data for the candidates and epidemiological data for the pathogen. The model accurately identifies potential intermediate hosts of the three emerging coronaviruses of the twenty-first century, predicting palm civets as intermediate hosts for SARS-CoV-1 and dromedary camels as intermediate hosts for MERS. Further, it suggests mink, raccoon dogs, and ferrets as probable intermediate host species for SARS-CoV-2. With the capacity to evaluate intermediate host likelihood among different species, researchers can focus testing for possible infection sources and interventions more effectively."
author4: "Iona McCabe; Kaia Smith"
inst4: "University of California, Santa Barbara; Scripps College (Department of Mathematics; Department of Mathematics)"
title4: "Stochastic Models of Zoonotic Avian Influenza with Multiple Hosts, Environmental Transmission, and Migration in the Natural Reservoir"
additional_authors4: "Rowan L. Hassman, Department of Mathematics, Bates College; Linda J. S. Allen, Department of Mathematics and Statistics, Texas Tech University,"
abstract4: "Avian influenza virus (AIV) is an infectious disease that circulates among wild bird populations and regularly spills over into domestic animals, such as poultry and swine. This spread raises the risk of a mutation resulting in a human-to-human-transmissible strain, which would pose a serious threat to public health. Mathematical modeling can be a powerful tool to mitigate the risks associated with these strains. Prior models have included factors such as multiple host populations, spillover into humans, environmental transmission, seasonality, and migration. We develop an ordinary differential equation (ODE) model that combines all of these factors, and we translate this into a stochastic continuous-time Markov chain (CTMC) model. We examine and compare the numerical trajectories of the disease using the ODE and CTMC models. Linear approximation of the ODE model near the disease-free solution leads to the basic reproduction number R0, a threshold for both the ODE and CTMC models. Linearization of the CTMC near the disease-free solution leads to a branching process approximation and the corresponding backward Kolmogorov differential equation, which can be used to estimate the probability of disease extinction when R0. Seasonal variation in migration, transmission, birth rate and viral decay results in a seasonally-dependent probability of disease extinction (no disease outbreak). A parameter sensitivity analysis of the ODE model with respect to R0 indicates that our model is sensitive to the wild bird recovery rate and environmental transmission-related parameters, which may inform future research. Additionally, in the CTMC model, we examine the sensitivity of the frequency of a spillover event into the human population from domestic poultry. We find that wild birds can drive infection numbers in other populations even when transmission parameters for those populations are low, and that environmental transmission can be a significant driver of infections."
---
