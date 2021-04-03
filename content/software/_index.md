+++
widget = "about"
active = true
date = 2021-04-01T00:00:00

# Order that this section will appear in.
weight = 3
+++

<br/><br/>
<br/><br/>

[1] <span style="color:red"> powerLATE: Generalized Power Analysis for LATE </span>, (With Kirk Bansak). [[CRAN](https://cran.r-project.org/web/packages/powerLATE/index.html), [GitHub](https://github.com/kbansak/powerLATE)]
An R package that implements of the generalized power analysis for the local average treatment effect (LATE), proposed by [Bansak (2020)](https://doi:10.1214/19-STS732). Power analysis is in the context of estimating the LATE (also known as the complier average causal effect, or CACE), with calculations based on a test of the null hypothesis that the LATE equals 0 with a two-sided alternative. The method uses standardized effect sizes to place a conservative bound on the power under minimal assumptions. Package allows users to recover power, sample size requirements, or minimum detectable effect sizes. Package also allows users to work with absolute effects rather than effect sizes, to specify an additional assumption to narrow the bounds, and to incorporate covariate adjustment.

[2] <span style="color:red"> hbal: Hierarchically Regularized Entropy Balancing </span>, (With Yiqing Xu). [[GitHub](https://github.com/xuyiqing/hbal)]
An R package that implements hierarchically regularized entropy balancing proposed by [Xu and Yang (2021)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3807620). The method adjusts the covariate distributions of the control group to match those of the treatment group. hbal automatically expands the covariate space to include higher order terms and uses cross-validation to select variable penalties for the balancing conditions.