# Modelling-Disease-Transmission
Equitable allocation of resources such as vaccines are a central challenge in epidemic response, particularly when disease burden is unequally distributed across population subgroups. While most existing research on epidemic resource allocation focuses on maximizing efficiency, typically by minimizing infections or deaths, relatively little attention has been given to the equity implications of these strategies. 

Real-world populations often exhibit stark disparities in transmission risk and disease vulnerability, raising questions about how to allocate limited resources fairly. To address this gap, our research aims to systematically characterize the equity-efficiency tradeoff and identify population disparity contexts in which equity goals become more or less costly.

We developed a deterministic compartmental epidemic model based on the SIRVQD (Susceptible, Infected, Vaccinated, Quarantined, Deceased) framework. The population is divided into two subgroups with heterogenous parameters, varying the transmission rate and mortality rate, to represent real-world disparities across socioeconomic or demographic populations. We evaluate four equity-aware optimization strategies from literature: (1) objective-function penalization; (2) equity-constrained optimization; (3) min-max optimization; (4) Nash bargaining optimization. 

Preliminary simulations suggest that the loss in efficiency incurred when moving from an efficiency-optimal solution to a fairness-constrained solution– what we refer to as the “cost of fairness”– varies significantly based on the type of population heterogeneity and the allocation strategy used. 

This work contributes to a growing body of research at the intersection of operations research, epidemiology, and social equity, with the broader goal of informing more fair and efficient public health interventions in future epidemics. 
