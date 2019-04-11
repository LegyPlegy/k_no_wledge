# Bayesian Inference in Physics
### By V Dose
[Link To Article](http://www2.ipp.mpg.de/~rrf/bda/Publications/Papers/dose03b.pdf)


## Terminology

<u> Bayesian Inference:</u> describing the probability of an event, based on prior knowledge of conditions that might be related to the event.

<u> Bayes' Theorem:</u> P(A|B) = P(B|A) * P(A) / P(B)
i.e. "the probability of A given B occurs is equal to the probability of B given A times the probability of A over B."

<u> Occam's Razor:</u> The problem-solving principle that essentially states that "simpler solutions are more likely to be correct than complex ones."

## Abstract

Bayesian principles are used in several systems that are given as example.
Some systems include spectrum restoration, parameter estimation, model comparison, and in dealing with systems of inconsistent data.
Systems of inconsistent data are particularly interesting as inconsistencies can arise from incorrect estimation of errors or from distortions of the measurement signal.


## Introduction

Bayesian methods are not as useful in fields where active experiments can be repeated in principle in order to satisfy precision requirements. This argument breaks down when you are looking at experiments that have large, expensive equipment that operate on tight budgets. Similarly, observational fields such as astronomy and astrophysics cannot be augmented at will, thus the data that can be collected must be squeezed for information at the maximum efficiency possible.

### Bayesian Principles

Beginning with a probability function P(d,O | I), where d,O are two variables that are conditional on all background information I. This two-variable function can be decomposed into separate one-variable functions in the following steps:

	- P(d,O | I) =  P(O | I) * P(d | O,I) = P(d | I) * P(O | d,I)

Associating variable "d" with data, and "O" with the model parameter, and "I" with all other information relating parameters to data.

Rearranging terms in the two lines yields <u>Bayes' Theorem:</u>

	- P(O | d, I) = P(d | O, I) * P(O | I) / P(d | I)

<u>Marginalization</u> is a critical tool that provides a way to eliminate uninteresting variables from a problem that can't easily be removed as they are needed to formulate the likelihood. The form is as follows:

	- P(d | I) = integral( P(O | I) * )


###