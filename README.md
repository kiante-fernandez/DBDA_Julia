# *Doing Bayesian data analysis* in Julia using Turing.jl

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7023740.svg)](https://doi.org/10.5281/zenodo.7023740)

This ebook is designed to help people do Bayesian data analysis. Similar to Solomon Kurz, my contribution is converting Kruschke's JAGS code for use in Hong Ge's [**Turing.jl**](https://github.com/TuringLang/Turing.jl) for fitting Bayesian models in **Julia** using a wide range of sampling-based inference methods. I also prefer plotting and data wrangling with the packages from the [**Gadfly.jl**](http://gadflyjl.org/stable/) & [**DataFrames.jl**](https://dataframes.juliadata.org/stable/). So we'll be using those methods, too. 

Note: This project was inspired by: [Doing Bayesian Data Analysis in brms and the tidyverse](https://bookdown.org/content/3686/) by [A Solomon Kurz] (https://solomonkurz.netlify.app/). I encourage folks to check out his wonderful work. 

This ebook is not meant to stand alone. It's a supplement to the second edition of Kruschke's [*Doing Bayesian data analysis: A tutorial with R, JAGS, and Stan*](https://sites.google.com/site/doingbayesiandataanalysis/). I follow the structure of his text, chapter by chapter, translating his analyses into **Turing.jl** code. However, the content herein departs at times from the source material. Bayesian data analysis is an active area in terms of both statistical methods and software implementation.

The current 0.0.1 version is the first draft. I aim to add the **Turing.jl** versions of all of Kruschke's JAGS and Stan models, excluding examples that are not possible with the **Turing.jl** paradigm. 
