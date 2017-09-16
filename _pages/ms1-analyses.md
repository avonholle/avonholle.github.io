---
layout: single
title : analyses for manuscript 1
permalink: /diss/ms1-analyses/
---

Analyses for manuscript 1 examines the association between prenatal predictors and infant physical growth from months 0 to 5 as an outcome. Two different types of analyses will be used to examine this association. First, growth will be characterized by the SITAR method, which extracts out up to three different aspects of growth for an individual and uses that as an exposure in regression models with univariate measures of lipids. Second, a latent growth mixture model (LGMM) divides growth patterns into distinct 'latent growth classes' that serves as the outcome regressed onto the prenatal predictors.

An overall summary can be found [here](../../unc-dissertation-markdown-p2/includes/scripts/paper1/overall-summary.html).


## 1. Statistical analysis plan

[Statistical analysis plan (SAP)](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sap1.html) -- [code for SAP](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sap1.Rmd)

<p></p>

## 2. Data handling scripts

  * [Read in 2014 data -- 5-year old cohort](../../unc-dissertation-markdown-p2/includes/scripts/paper1/Descriptive.Rmd)

  * [Read in 2017 data -- 1-year old cohort](../../unc-dissertation-markdown-p2/includes/scripts/paper1/read-phenotypes.Rmd)
  
  * [preliminary descriptive statistics](../../unc-dissertation-markdown-p2/includes/scripts/paper1/descriptive_statistics.Rmd)

  * [data imputation](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table3-data-handle-weight-impute.Rmd)

<p></p>

## 3. Table of descriptive statistics

  * [Table 1](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table1.pdf) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table1.Rmd)

<p></p>

## 4. Evaluate model fit for the SITAR models

  * [Results for model fit for weight, height and wfl outcomes](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table3-w-fcns.pdf){:target="_blank"} -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table3-w-fcns.Rmd)

## 5. Association between the maternal predictors and infant growth through random effects from SITAR

### 5a. First set with a lasso approach to choose subset of confounders

1. [Results for weight](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev/table2-mice.html) -- [code](../includes/scripts/paper1/sitar-rev/table2-mice.Rmd)

2. [Results for height](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev/table2-mice-ht.html) -- [code](../includes/scripts/paper1/sitar-rev/table2-mice-ht.Rmd)

3. [Results for weight-for-length (wfl)](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev/table2-mice-wfl.html) -- [code](../includes/scripts/paper1/sitar-rev/table2-mice-wfl.Rmd)

### 5b. Same approach as Pizzi 2014 **[no longer using these results. For reference only.]**

**Paper**: Pizzi, Costanza, Tim J. Cole, Lorenzo Richiardi, Isabel dos-Santos-Silva, Camila Corvalan, and Bianca De Stavola. 2014. “Prenatal Influences on Size, Velocity and Tempo of Infant Growth: Findings from Three Contemporary Cohorts.” Edited by Guoying Wang. PLoS ONE 9 (2): e90291. doi:10.1371/journal.pone.0090291.

1. [Results for weight](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table2-mice.html) -- [code](../includes/scripts/paper1/table2-mice.Rmd)

2. [Results for height](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table2-mice-ht.html) -- [code](../includes/scripts/paper1/table2-mice-ht.Rmd)

3. [Results for weight-for-length (wfl)](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table2-mice-wfl.html) -- [code](../includes/scripts/paper1/table2-mice-wfl.Rmd)

---

## 6. Association between the maternal predictors and latent growth classes with latent class growth mixture models (LGMM)

### 6a. Model fit

  1. [Model fit info -- stratified by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/strat-sex/summarize-mplus-results-sex-strat.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/strat-sex/summarize-mplus-results-sex-strat.Rmd)

      - [Template used to create Mplus files](../includes/scripts/paper1/lgmm/virtuallab/template_mplus1-strat-sex.txt)

  2. [Model fit info -- pooled across sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/adj-sex/summarize-mplus-results.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/adj-sex/summarize-mplus-results.Rmd)

      - [Template used to create Mplus files](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/template_mplus1-bysex.txt)

### 6b. Association estimates

1. [Estimated association between maternal characterisics and child growth parameters -- pooled across sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/assn/models-results-plots-assn.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/assn/models-results-plots-assn.Rmd)

### NOTE

I create the Mplus models with [MplusAutomation in R](../includes/scripts/paper1/lgmm/export-mplus.Rmd) with scripts to create batches of Mplus files that I run on batches of files in virtuallab with an [.R script](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/run-models.R).
