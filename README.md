[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/chekos/k-sys-covid-19-remix/master?urlpath=lab%2Ftree%2Fnotebooks%2FRealtime_R0.ipynb)

remake-covid-19-analysis
==============================

This is a recreation of @k-sys/covid-19 repository where he uses Bettencourt and Ribeiro's bayesian algorithm to estimate the most likely value of Rt and a credible interval.

Project Organization
--------------------
```
.
├── AUTHORS.md
├── LICENSE
├── README.md
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
├── docs               <- Documentation, e.g., doxygen or scientific papers (not tracked by git)
├── notebooks          <- Jupyter/Rmarkdown notebooks
├── reports            <- For a manuscript source, e.g., LaTeX, Markdown, etc., or any project reports
│   └── figures        <- Figures for the manuscript or reports
└── src                <- Source code for this project
    ├── __init__       <- Makes src a Python module
    ├── apps           <- scripts for apps (flask, streamlit)
    ├── data           <- scripts and programs to process data
    ├── external       <- Any external source code, e.g., pull other git projects, or external libraries
    ├── models         <- Source code for your own model
    ├── tools          <- Any helper scripts go here
    └── visualization  <- Scripts for visualisation of your results, e.g., matplotlib, ggplot2 related.

```