# Assessing Response Quality in Multi-Item Scales Using resquin

This is an application case that investigates response quality in two multi-item scales - one on environmental attitudes
and one on political trust - using resquin.

## About resquin

**`resquin` is currently in development and should only be used with
caution.**

`resquin` (**res**ponse **qu**ality **in**dicators) provides functions
to assess response quality and identify poor quality responses or response biases.
`resp_styles()` and `resp_distributions()` provide response quality indicators geared towards multi-item
scales or matrix questions. Both multi-item scales and matrix questions
present survey respondents with multiple questions which have the same response format,
meaning the same number and labeling of response options.

At the moment, `resquin` provides two functions:

-   `resp_styles()` - Calculates response style indicators (e.g. extreme
    response style or middle response style).
-   `resp_distributions()` - Calculates response distribution indicators
    (e.g. intra-individual mean and standard deviation over a set of
    survey questions).

Two more functions are planned:

-   `resp_patterns` - Calculates response pattern indicators (e.g.
    straightlining)
-   `resp_times` - Calculates response time indicators (e.g. median item
    response time)
    
For information on the functions of and how to use `resquin` see [resquin](https://matroth.github.io/resquin/) and [Getting started with resquin](https://matroth.github.io/resquin/articles/getting_started_with_resquin.html).

## Installation

`resquin` is available via github. To install `resquin` from github, you
can use one of the following commands:

```{r eval=FALSE}
# Installing resquin with devtools
devtools::install_github("https://github.com/MatRoth/resquin")

# Installing resquin with pak
pak::pak("https://github.com/MatRoth/resquin")
```
