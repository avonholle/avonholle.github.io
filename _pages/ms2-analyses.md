---
layout: single
title : analyses for manuscript 2
permalink: /diss/ms2-analyses/
---

Analyses for manuscript 2 examines infant physical growth from months 0 to 5 as an exposure and lipid levels at an average age of 17 years as an outcome. Two different types of analyses will be used to test the hypothesis that extreme levels of infant growth will influence lipid levels in adolescence. First, growth will be characterized by the SITAR method, which extracts out up to three different aspects of growth for an individual and uses that as an exposure in regression models with univariate measures of lipids. Second, a latent growth mixture model (LGMM) divides growth patterns into distinct 'latent growth classes' that serves as the exposure and the lipids, either as univariate or combined into one latent factor, will serve as the outcome.

## 1. Statistical analysis plan

[Statistical analysis plan (SAP)](../../unc-dissertation-markdown-p2/includes/scripts/paper2/sap2.html) -- [code for SAP](../../unc-dissertation-markdown-p2/includes/scripts/paper2/sap2.Rmd)

<p></p>

## 2. Data handling scripts

**Note**: data handling done with the [first paper](/diss/ms1-analyses).

<p></p>

## 3. Table of descriptive statistics

[Table 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/table1.pdf) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/table1.Rmd)

<p></p>

## 4. Association between infant growth and lipid measurements

### SITAR 

  * [Association between growth parameters and lipids](../../unc-dissertation-markdown-p2/includes/scripts/paper2/initial-m2.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/initial-m2.Rmd)

### LGMM

  - [Association between latent growth classes and an observed univariate distal outcome (lipid)](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/models-2-results-univariate-distal-assn.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/models-2-results-univariate-distal-assn.Rmd) -- [Template used to create Mplus .inp files](../../unc-dissertation-markdown-p2/ncludes/scripts/paper2/lgmm/virtuallab/distal/univariate/template_mplus2-strat-sex-assn-classes-univ-distal.txt)

  - [Association between latent growth classes and a latent distal outcome](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/latent-class-and-latent-distal-outcome/models-2-results-lc-latent-distal-assn.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/latent-class-and-latent-distal-outcome/models-2-results-lc-latent-distal-assn.Rmd) -- [Template used to create Mplus .inp files](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/latent-class-and-latent-distal-outcome/template_mplus2-strat-sex-assn-classes-latentdistal.txt)
      * **Note**: Holding the latent distal outcome the same across different latent growth classes. If not employing that assumption then the comparison of associations between growth and the latent distal outcome would be like comparing apples and oranges.

  - [Association between growth and latent distal outcomes; no latent growth classes](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/models-2-results-latent-distal-assn.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/models-2-results-latent-distal-assn.Rmd) -- [Template used to create Mplus .inp files](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/template_mplus2-strat-sex-assn-latentdistal.txt)

      
  * **NOTE**: I create the Mplus models with [MplusAutomation in R](../includes/scripts/paper1/lgmm/export-mplus.Rmd) with scripts to create batches of Mplus files that I run in virtuallab with an [.R script](../includes/scripts/paper2/lgmm/virtuallab/run-models.R).
