# MaryamLoni-Thesis-codes
Evaluating Robustness of Antigenic Mass ELISAs: From Superiority Testing to Equivalence-Based Decisions

R code accompanying this MSc thesis (Statistics and Data Science, Leiden University).

Files Appendix_Case_Study_Codes.Rmd - factor coding, regression models, equivalence summary tables, lack-of-fit and curvature tests for the case study.
Appendix_Simulation_Codes.Rmd - simulations comparing superiority and equivalence testing, block-effect sensitivity check, and sample size/power analysis.


Requirements

R (4.5.1), with packages: dplyr, tidyr, ggplot2, flextable, moments, nortest.

Notes


Factor levels are coded as -1, 0, +1 (low, center, high) and treated as continuous predictors.
Equivalence margins are defined on the natural log scale.
The case study data file is not included.
