# Projet-M-thodes-Bay-siennes


This example is taken from Table 3 of Crowder (1978), and concerns the proportion of seeds that germinated on each of 21 plates arranged according to a 2 by 2 factorial layout by seed and type of root extract. The data are shown below, where "r" "i" and "ni" are the number of germinated and the total number of seeds on the i'th plate, i =1,...,N. These data are also analysed by, for
example, Breslow: and Clayton (1993).
The model is essentially a random effects logistic, allowing for over-dispersion. If pi is the probability of germination on the i th plate, we assume

ri ~ Binomial(pi, ni)

logit(pi) = α0 + α1x1i + α2x2i + α12x1ix2i + bi

bi ~ Normal(0, τ)

where x1i, x2i are the seed type and root extract of the i th plate, and an interaction term α12*x1i*x2i
is included. α0, α1, α2, α12, τ are given independent "noninformative" priors.
