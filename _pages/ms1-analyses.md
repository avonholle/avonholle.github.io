---
layout: single
title : analyses for manuscript 1
permalink: /diss/ms1-analyses/
---

## 1. Statistical analysis plan

[Statistical analysis plan (SAP)](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sap1.pdf){:target="_blank"} -- [code for SAP](../includes/scripts/paper1/sap1.Rmd){:target="_blank"}

<p></p>

## 2. Data handling scripts

  * [Read in 2014 data -- 5-year old cohort](../../unc-dissertation-markdown-p2/includes/scripts/paper1/Descriptive.Rmd){:target="_blank"}

  * [Read in 2017 data -- 1-year old cohort](../../unc-dissertation-markdown-p2/includes/scripts/paper1/read-phenotypes.Rmd){:target="_blank"}

  * [preliminary descriptive statistics](../../unc-dissertation-markdown-p2/includes/scripts/paper1/descriptive_statistics.Rmd){:target="_blank"}

  * [data imputation](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table3-data-handle-weight-impute.Rmd){:target="_blank"}

<p></p>

## 3. Table of descriptive statistics

  * [Table 1](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table1.pdf){:target="_blank"}

<p></p>

## 4. Evaluate model fit for the SITAR models

  * [Results for model fit for weight, height and wfl outcomes](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table3-w-fcns.pdf){:target="_blank"}

## 5. Association between the maternal predictors and infant growth through random effects from SITAR

Using the imputed data I created the following analyses:

1. [Results for weight](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table2-mice.html){:target="_blank"} -- [code](../includes/scripts/paper1/table2-mice.Rmd)

2. [Results for height](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table2-mice-ht.html){:target="_blank"} -- [code](../includes/scripts/paper1/table2-mice-ht.Rmd)

3. [Results for weight-for-length (wf)](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table2-mice-wfl.html){:target="_blank"} -- [code](../includes/scripts/paper1/table2-mice-wfl.Rmd)

---

## 6. Association between the maternal predictors and latent growth classes with latent class growth mixture models (LGMM)

**NOTE**: I create the Mplus models with [MplusAutomation in R](../includes/scripts/paper1/lgmm/export-mplus.Rmd) with scripts to create batches of Mplus files that I run on batches of files in virtuallab with an [.R script](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/run-models.R).

[Association between growth and maternal predictors -- stratified by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/strat-sex/summarize-mplus-results-sex-strat.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/strat-sex/summarize-mplus-results-sex-strat.Rmd)

  - [Template used to create Mplus files](../includes/scripts/paper1/lgmm/virtuallab/template_mplus1-strat-sex-assn.txt)

[Association between growth and maternal predictors -- pooled across sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/adj-sex/summarize-mplus-results.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/adj-sex/summarize-mplus-results.Rmd)

  - [Template used to create Mplus files](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/template_mplus1-bysex.txt)