Producing reproducible code: A DAA DS framework
================

## Introduction

Data science is a burgeoning and yet still nascent field. Its popularity
has created an influx of DS’ from an incredible array of disparate
backgrounds; economics to biochemistry, and all fields in between! In
fact, its quite likely that DS as a profession contains more generalist
skilled individuals than any other scientific career, not least because
of the variety of skills required to be proficient, but also due to the
fields novelty - I think it reasonable to posit that most, current,
established DS were either joining from a second career and/or received
no formal pedagogy/taught themselves autodidacticly.

A generalist background clearly has merits, especially in the arena of
Data Scientific work where a wide ranging skillset is absolutely
necessary. However, the lack of pedagogical standardisation has caused
problems with readability, reproducibility, and replicability.
Interestingly, lacking pedagogical standardisation has not obviously
inhibited the “output” of DS work from improving. Indeed, the widely
recognised tools of data scientists (statistics, AI, coding, problem
solving) have enjoyed rising competency and improvements, likely through
a convergence in the lessons taught by both online and degree courses,
and “copy-paste” pedagogy from other disciplines.

However, how can we actually know that improvements have been accrued? A
definition of improvements would be required, and is beyond this the
scope of this brief piece, but I think it’s safe to assume that most
definitions would include one or more of the following: more output
(perhaps in a shorter timeframe), better performing models, more
appropriate figures and statistical analyses. But none of these
determine whether the work that went into producing the output (data
collection, datasets, the code), were appropriate for the question
posed. This is the crux of the matter: the “correctness” of the output
cannot be objectively assessed without transparency of the code.

# Definitions: Reproducible and Replicable

Definitions of key terminology in this space is a real minefield, not
least because the field you work in may determine the definition. For an
full review on this topic, do read this peer-reviewed paper by [Hans
Plesser
(2018)](https://www.frontiersin.org/articles/10.3389/fninf.2017.00076/full).

Talk about catch up of pedagogy and teaching reproducible working

Talk about NHS and novelty of moving toward taking on DS Talk about NHS
and recent papers on data Talk about DAA and its 3 year plan - DS part
in particular - say that in order to do this are code needs to be up to
scratch

Talk about ways we can work in a reproducible way as a team Use stuff on
my website to help with this

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](_main_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.