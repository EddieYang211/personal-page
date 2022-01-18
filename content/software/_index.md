+++
widget = "about"
active = true
date = 2021-04-01T00:00:00

# Order that this section will appear in.
weight = 3
+++

<br/><br/>

1\. <span style="color:red"> powerLATE</span>: Generalized Power Analysis for LATE, (With Kirk Bansak). [CRAN](https://cran.r-project.org/web/packages/powerLATE/index.html), [GitHub](https://github.com/kbansak/powerLATE)

An R package that implements of the generalized power analysis for the local average treatment effect (LATE), proposed by Bansak <a href="https://arxiv.org/abs/1610.08580" style="color: black">(2020)</a>. The method uses standardized effect sizes to place a conservative bound on the power under minimal assumptions. Package allows users to recover power, sample size requirements, or minimum detectable effect sizes. Package also allows users to work with absolute effects rather than effect sizes, to specify an additional assumption to narrow the bounds, and to incorporate covariate adjustment.

<br/>

2\. <span style="color:red"> hbal</span>: Hierarchically Regularized Entropy Balancing, (With Yiqing Xu). [GitHub](https://github.com/xuyiqing/hbal)

An R package that implements hierarchically regularized entropy balancing proposed by Xu and Yang <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3807620" style="color: black">(2021)</a>. The method adjusts the covariate distributions of the control group to match those of the treatment group. hbal automatically expands the covariate space to include higher order terms and uses cross-validation to select variable penalties for the balancing conditions.

<br/>

3\. <span style="color:red"> ebal-python</span>: Entropy Balancing for Binary and Continuous Treatment. [GitHub](https://github.com/EddieYang211/ebal-python)

Python implementation of entropy balancing for binary (<a href="https://web.stanford.edu/~jhain/Paper/PA2012.pdf" style="color: black">Hainmueller, 2012</a>) and continuous treatment (<a href="https://arxiv.org/abs/2001.06281" style="color: black">Tübbicke, 2020</a>; <a href="https://arxiv.org/pdf/2003.02938.pdf" style="color: black">Vegetabile et al., 2021</a>). The method reweights the sample to remove correlations between the treatment and the covaraites.

<br/><br/>
