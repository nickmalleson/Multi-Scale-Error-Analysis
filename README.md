# Identifying the appropriate spatial resolution for the analysis of crime patterns

_Authors: Nick Malleson, Wouter Steenbeek, Martin A. Andresen_

This repositoyy contains the source code that accompanies the following paper:

Malleson, N., W. Steenbeek, M. A. Andresen (2019) 
Identifying the appropriate spatial resolution for the analysis of crime patterns. 
_PLOSOne_.

The empirical work outlined here can be conducted, in full, using the R source code:  [`multi_scale_error_analysis.Rmd`](./multi_scale_error_analysis.Rmd)

It is in 'R Markdown' format so can either be used to generate an html file with text and graphics included, or the R commands can be run independently. The script depends heavily on the `sppt` R package
The script attempts to download the required crime data (that are open source), so all experiments outlined here can be run in their entirety. 

The easiest way to run the script is to load it into RStudio and run it from there.
Alternatively, it can be run from a bash command line to generate an html file using
this command (all on a single line):

```sh
Rscript -e "require(knitr) ; require(markdown) ; knit(’multi scale error analysis.Rmd’,
    ’multi scale error analysis.md’); markdownToHTML(’multi scale error analysis.md’,
    ’multi scale error analysis.html’);"
```

