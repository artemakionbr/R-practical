# R-practical

In this practical we will estimate the effect of low density lipoprotein cholesterol (LDL-C)
on coronary heart disease (CHD) using a range of pleiotropy robust methods. This practical
uses summary-level data from a GWAS on LDL-C in UK Biobank (Richardson et al, 2020)
and from a GWAS of CHD conducted in a mixed ancestry (77% European) GWAS (Nikpay et
al, 2015). We will also include a multivariable MR estimation including summary-level data
on high density lipoprotein cholesterol (HDL-C) and triglycerides generated from a GWAS
of the same data as LDL-C.

This practical covers a number of different approaches to pleiotropy robust MR and
sensitivity analyses that could be included as part of a MR analysis. The particular
methods used here are neither an exhaustive list of what could be used nor a definitive list
of what should be used. This practical instead provides an example of the range of issues
that should be considered when assessing whether a particular MR estimate is likely to be
biased by the presence of pleiotropy. References for each of the methods are given at the
end

References: 
Richardson, Tom G., et al. “Evaluating the relationship between circulating lipoprotein
lipids and apolipoproteins with risk of coronary heart disease: A multivariable Mendelian
randomisation analysis.” PLoS medicine 17.3 (2020): e1003062.

The CARDIoGRAMplusC4D Consortium. A comprehensive 1000 Genomes–based genome-
wide association meta-analysis of coronary artery disease. Nat Genet 47, 1121–1130
(2015). https://doi.org/10.1038/ng.3396

Pleiotropy robust methods:

Bowden, Jack, et al. “Consistent estimation in Mendelian randomization with some invalid
instruments using a weighted median estimator.” Genetic epidemiology 40.4 (2016): 304-
314.
Hartwig, Fernando Pires, George Davey Smith, and Jack Bowden. “Robust inference in
summary data Mendelian randomization via the zero modal pleiotropy assumption.”
International journal of epidemiology 46.6 (2017): 1985-1998.

Bowden, Jack, George Davey Smith, and Stephen Burgess. “Mendelian randomization with
invalid instruments: effect estimation and bias detection through Egger regression.”
International journal of epidemiology 44.2 (2015): 512-525.

Steiger filtering:

Hemani, Gibran, Kate Tilling, and George Davey Smith. “Orienting the causal relationship
between imprecisely measured traits using GWAS summary data.” PLoS genetics 13.11
(2017): e1007081

Multivariable MR:

Burgess, Stephen, and Simon G. Thompson. “Multivariable Mendelian randomization: the
use of pleiotropic genetic variants to estimate causal effects.” American journal of
epidemiology 181.4 (2015): 251-260.

Sanderson, Eleanor, et al. “An examination of multivariable Mendelian randomization in
the single-sample and two-sample summary data settings.” International journal of
epidemiology 48.3 (2019): 713-727.

Sanderson, Eleanor, Wes Spiller, and Jack Bowden. “Testing and correcting for weak and
pleiotropic instruments in two‐sample multivariable Mendelian randomization.” Statistics
in medicine 40.25 (2021): 5434-5452
