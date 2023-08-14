---
layout: group
poster: "MFBM-15"
day: "Thursday"
permalink: /MFBM/PS02-MFBM-15.html
code: "PS02"
subgroup: "MFBM"
author: "Torkel Loman"
inst: "Massachusetts Institute of Technology"
title: "Catalyst: Fast Biochemical Modeling with Julia"
abstract: "We introduce Catalyst.jl, a flexible and feature-filled Julia library for modeling and high performance simulation of chemical reaction networks (CRNs). Catalyst acts as both a domain-specific language and an intermediate representation for symbolically encoding CRN models as Julia-native objects. This enables a pipeline of symbolically specifying, analyzing, and modifying reaction networks; converting Catalyst models to symbolic representations of concrete mathematical models; and generating compiled code for use in numerical solvers. Currently, Catalyst supports conversion to symbolic discrete stochastic chemical kinetics (jump process), chemical Langevin (stochastic differential equation), and mass-action reaction rate equation (ordinary differential equation) models. Leveraging ModelingToolkit.jl and Symbolics.jl, Catalyst models can be analyzed, simplified, and compiled into optimized representations for use in a broad variety of numerical solvers. The performance of the numerical solvers Catalyst targets is illustrated across a variety of reaction networks by benchmarking stochastic simulation algorithm and ODE solver performance. These benchmarks demonstrate significant performance improvements compared to several popular reaction network simulators. Finally, Catalyst combines with a range of packages within the Julia package ecosystem, enabling functions such as steady state finding, bifurcation analysis, parameter fitting, and much more."
additional_authors: "Yingbo Ma, Julia Computing; Vasily Ilin, University of Washington; Shashi Gowda, Massachusetts Institute of Technology; Niklas Korsbo, Pumas-AI; Nikhil Yewale, IIT Madras; Chris Rackauckas, Massachusetts Institute of Technology; Samuel Isaacson, Boston University"
---
