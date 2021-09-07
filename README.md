# AROS 2021: Reproducibility with RMarkdown and the reproducR package


This repository contains workshop material for the tutorial "Reproducibility with RMarkdown and the reproducR package", which I offered at the Aarhus Reproducibility and Open Science (AROS) Seminar, Aarhus University (08 September 2021). 

:star: The R Markdown file **03_integrated_reproducr.Rmd** showcases the [`reproducr` library](https://jschultecloos.github.io/reproducr/), which provides a framework to implement reproducible research practices in scientific workflows with R Markdown.

:star: You can access the workshop material and compile the example Rmd-files from within your browser with no need to locally install the software package R, the RStudio IDE, a LaTeX distribution, Pandoc, or any of the R libraries that the template relies on.
  - :bulb: The runtime environment created for the Binder uses an MRAN snapshot of 2021-09-07 and relies on R version 4.1.1 (2021-08-10), running under: Ubuntu 18.04.5 LTS, RStudio 1.2.5001.
  - :bulb: It may take a short time to launch the environment. 
  
  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jschultecloos/AROS_2021/HEAD?urlpath=rstudio)



## Workshop abstract

This hands-on tutorial provides participants with an in-depth understanding of how to build on R Markdown to make their research workflows fully reproducible. Acknowledging the diversity of programming languages (e.g., R, Python, SQL) and types of research outputs (e.g., manuscripts, blog posts) that are common in computational social science, the tutorial showcases an integrated and automated R Markdown research project workflow. It familiarizes participants with the basic logic of R Markdown for research outputs, while extending this basic logic for scientific use cases by relying on the power of Pandoc and Lua.
