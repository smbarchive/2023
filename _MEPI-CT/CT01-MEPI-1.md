---
layout: group
author: smb2023
day: "Monday"
room: "Barbie Tootle Room (#3156)"
code: "CT01"
subgroup: "MEPI"
subgroup-long: "MEPI-1"
title: "MEPI Subgroup Contributed Talks"
author1: "Christopher Mitchell"
inst1: "Tarleton State University"
title1: "Using Bayesian Methods to Infer Parameters for ODE Epidemic Systems"
abstract1: "Classical models of disease outbreaks rely on systems of nonlinear ordinary differential equations. ODE models have been widely successful and are credited with saving millions of lives worldwide. However, ODE models involve parameters that are often poorly understood and difficult to infer from limited and noisy data. This is especially problematic for rare, novel, or neglected diseases with unreliable reporting mechanisms. While some parameters can be deduced from biological or social facts, many must be inferred from data. Traditional least-squares point-estimates are fragile when applied to noisy data common in disease modeling. Bayesian inference replaces fragile point-estimates with posterior distributions that are more robust against data quality issues. Whereas point-estimate models produce a single outbreak forecast, Bayesian models generate an ensemble of forecasts through repeatedly sampling model parameters from their posterior distributions and numerically solving the resulting ODE. These multiple forecasts can be pooled and statistically analyzed at each time step (min, max, mean, etc) to give insight into potential outbreak scenarios (best-case, worst-case, most likely, resp). This project aims to create well-functioning ODE models using a new mathematical idea called amortized Bayesian inference implemented in the BayesFlow Python library. This exciting new tool was created in 2020 to help fight Covid-19 and other common diseases. This project will enhance the BayesFlow library to compensate for data quality issues and provide the improved models epidemiologists need to effectively fight NTDs."
additional_authors1: "Scott Cook, Tarleton State Unviersity"
author2: "Rodolfo Blanco-Rodriguez"
inst2: "University of Idaho"
title2: "Modeling the impact of contact network and viral evolution on lockdown and vaccination strategies"
abstract2: "The transmission of infectious diseases is heavily influenced by the network topology of the population through which the disease spreads. However, the effectiveness of control strategies in diverse and complex social structures is poorly understood. A key lesson learned with COVID-19 is that public health measures were very different from country to country. While some implemented strongly restrictive lockdowns while others focused on mass vaccination campaigns, leaving a concern about which strategies are most effective according to certain social structures. Additionally, during a pandemic, viral evolution forces us to reconsider our control strategies. To gain insight into this, we computationally analyzed the spread of two variants of a virus through three well-known network models, small-world networks (Watts-Strogatz), random networks (Erdös-Rényi), and scale-free networks (Barabási-Albert). We contrasted two lockdown policies in the different networks, one continuous and the other by intervals, and compared different vaccination strategies by varying the number of nodes vaccinated per day.
Our results showed that scale-free networks reached the highest outbreak peaks and the peak values of the infected population were independent of the infectivity of the virus variant. In addition, in this scale-free network, lockdown and vaccination strategies decreased the number of infected regardless of the strategy considered. Furthermore, for the small-world or random networks we found that confinement for 15-day intervals can reduce the peak number of infected nodes. Interestingly, we also found that a 20-day vaccination campaign yields lower infected cases than a 10-day campaign. These findings underscore the importance of considering social network topology to predict the course of epidemics and design more effective control measures."
additional_authors2: "Josephine N. A. Tetteh; Esteban A. Hernandez-Vargas"
author3: "Soyoung Kim"
inst3: "National Institute for Mathematical Sciences"
title3: "Optimal antiviral stockpile for influenza pandemic"
abstract3: "A stockpile of antiviral drugs is important for mitigating a novel influenza pandemic. Recently, intervention strategies against such a pandemic have improved significantly, affecting the required size and composition of the stockpile. Our goal is to estimate the optimal ratio of conventional to newer antiviral drugs. Epidemic parameters are estimated from daily-case data about H1N1pdm09 in the Republic of Korea, and used a deterministic ordinary differential equation model and stochastic simulation to predict the number of patients in a future pandemic. An antiviral stockpile containing neuraminidase inhibitors and a new drug, cap-dependent endonuclease inhibitor are considered, seeking the optimum ratio of the two drugs under different epidemiological and economic assumptions."
additional_authors3: "Yu Bin Seo; Jacob Lee; Yang Soo Kim; Eunok Jung"
author4: "Zitao He"
inst4: "University of Waterloo"
title4: "Predicting measles outbreaks from vaccine sentiments on social media"
abstract4: "Vaccinating decisions for childhood diseases such as measles have been studied with coupled models of disease dynamics and individual behaviors. Such models applied evolutionary game theory to model people's vaccination strategies and how they are affected by social norms. Recent studies incorporated bifurcation theory to identify early warning signals (EWS), such as increasing variance and lag-1 autocorrelation, of critical transitions. Deep learning models have also been used to classify different types of bifurcation from time-series data near a tipping point. On the other hand, the rise of social media has made it easier for pro- and anti-vaccine sentiments to spread. Researchers have used high-frequency social media data to study population dynamics of infectious diseases and have found critical slowing downs in geocoded Tweets about the MMR vaccine and measles-related Google searches before the 2014-15 Disneyland, California measles outbreak. This project aims to use deep learning models to predict potential disease outbreaks from social media data and provide novel methods for disease outbreak prediction near thresholds. We improved existing coupled behavior-disease models by considering different social groups and investigating the effect of homophily on disease dynamics near tipping points. We showed that a deep learning model, such as a CNN-LSTM framework, could capture EWS directly from real-world social media data and predict a potential disease outbreak in the future."
additional_authors4: "Chris T. Bauch, Department of Applied Mathematics, University of Waterloo"
---