---
layout: single
title : analyses for manuscript 2
permalink: /diss/ms2-analyses/
---

Analyses for manuscript 2 examines infant physical growth from months 0 to 5 as an exposure and lipid levels at an average age of 17 years as an outcome. Two different types of analyses will be used to test the hypothesis that extreme levels of infant growth will influence lipid levels in adolescence. First, growth will be characterized by the SITAR method, which extracts out up to three different aspects of growth for an individual and uses that as an exposure in regression models with univariate measures of lipids. Second, a latent growth mixture model (LGMM) divides growth patterns into distinct 'latent growth classes' that serves as the exposure and the lipids, either as univariate or combined into one latent factor, will serve as the outcome.

# AHA Epi/Lifestyle 2018 abstract

[abstract](../../unc-dissertation-markdown-p2/includes/scripts/paper2/aha2018/abstract-m2.html) -- [word version](../../unc-dissertation-markdown-p2/includes/scripts/paper2/aha2018/abstract-m2.docx)


# Overall summary

[Overall summary of results](../../unc-dissertation-markdown-p2/includes/scripts/paper2/overall-summary.html)


# 1. Statistical analysis plan

[Statistical analysis plan (SAP)](../../unc-dissertation-markdown-p2/includes/scripts/paper2/sap2.html) -- [code for SAP](../../unc-dissertation-markdown-p2/includes/scripts/paper2/sap2.Rmd)

<p></p>


# 2. Data handling scripts

**Note**: data handling done with the [first paper](/diss/ms1-analyses).

<p></p>

# 3. Table of descriptive statistics

[Table 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/table1.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/table1.Rmd)

<p></p>


# 4. Association between infant growth and lipid measurements

## 4a. SITAR 

  * [Association between growth parameters and lipids](../../unc-dissertation-markdown-p2/includes/scripts/paper2/initial-m2.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/initial-m2.Rmd)

## 4b. LGMM


* Pooled by sex of child

    - [Association between latent growth classes and an observed univariate distal outcome (lipid) -- Using DU3step 3-step approach for distal variable. Pooled by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-pooled-du3step.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-pooled-du3step.Rmd)
  
    - [Template used to create Mplus .inp files](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-pooled-sex-univ-distal-v2.txt)
    
<!--      * Sensitivity analysis. Subset of data.

          * These analyses use the exact same scripts as the prior one except outliers (>3sd of lipid distribution) are excluded (<5% of the data).

          - [Restricted analyses: Association between latent growth classes and an observed univariate distal outcome (lipid) -- Using DU3step 3-step approach for distal variable. Pooled by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/v2-pooled/sensitivity/models-2-results-univariate-distal-assn-pooled-du3step-sens.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/v2-pooled/sensitivity/models-2-results-univariate-distal-assn-pooled-du3step-sens.Rmd)
-->          

  * TG / HDL ratios and TG-HDL correlations
      
      - [Table of estimated tg/hdl ratios and correlations for pooled sample](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-pooled-bch-ratio.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-pooled-bch-ratio.Rmd)
      - Templates used to create Mplus .inp files
        - [Step 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step1-pooled-ratio.txt)
        - [Step 3](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step3-2-class-pooled-ratio.txt)


* Stratified by sex of child

    - [Association between latent growth classes and an observed univariate distal outcome (lipid) -- Using 3-step approach for distal variable. Stratified by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-pooled-du3step-strat.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-pooled-du3step-strat.Rmd) -- [Template used to create Mplus .inp files](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-strat-sex-assn-classes-univ-distal-v2.txt)
    

<!--
      * Sensitivity analysis. Subset of data.

          * These analyses use the exact same scripts as the prior one except outliers (>3sd of lipid distribution) are excluded (<5% of the data).

          - [Restricted analyses: Association between latent growth classes and an observed univariate distal outcome (lipid) -- Using DU3step 3-step approach for distal variable. Stratified by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/v2/sensitivity/models-2-results-univariate-distal-assn-du3step-sens.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/v2/sensitivity/models-2-results-univariate-distal-assn-du3step-sens.Rmd)
-->

  * TG / HDL ratios and TG-HDL correlations
      
      - [Table of estimated tg/hdl ratios and correlations for stratified sample](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-strat-bch-ratio.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-strat-bch-ratio.Rmd)
          
      - Templates used to create Mplus .inp files
              
        - [Step 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step1-strat-ratio.txt)
        - [Step 3](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step3-2-class-strat-ratio.txt)
              

<!--
--- 

#### The following sections for LGMM use the default for distal variable (one-step method) and may not have a meaningful interpretation.

  - [Association between latent growth classes and an observed univariate distal outcome (lipid) -- Using default approach for distal variable](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/models-2-results-univariate-distal-assn.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/models-2-results-univariate-distal-assn.Rmd) -- [Template used to create Mplus .inp files](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/template_mplus2-strat-sex-assn-classes-univ-distal.txt)
  
  - Follow-up: [Checked overlap between height trajectory analyses for males](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/m2-univ-distal-compare-people-in-classes.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/m2-univ-distal-compare-people-in-classes.Rmd)
  

  - [Association between latent growth classes and a latent distal outcome -- using default approach](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/latent-class-and-latent-distal-outcome/models-2-results-lc-latent-distal-assn.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/latent-class-and-latent-distal-outcome/models-2-results-lc-latent-distal-assn.Rmd) -- [Template used to create Mplus .inp files](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/latent-class-and-latent-distal-outcome/template_mplus2-strat-sex-assn-classes-latentdistal.txt)
      * **Note**: Holding the latent distal outcome the same across different latent growth classes. If not employing that assumption then the comparison of associations between growth and the latent distal outcome would be like comparing apples and oranges.

  - [Association between growth and latent distal outcomes; no latent growth classes](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/models-2-results-latent-distal-assn.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/models-2-results-latent-distal-assn.Rmd) -- [Template used to create Mplus .inp files](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/template_mplus2-strat-sex-assn-latentdistal.txt)


  * **NOTE**: I create the Mplus models with [MplusAutomation in R](../includes/scripts/paper1/lgmm/export-mplus.Rmd) with scripts to create batches of Mplus files that I run in virtuallab with an [.R script](../includes/scripts/paper2/lgmm/virtuallab/run-models.R).


-->