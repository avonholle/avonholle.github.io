---
layout: single
title : "Analyses for manuscript 2 -- Infant Growth Trajectories and Lipid Levels in Adolescence: Evidence from a Chilean Infancy Cohort"
permalink: /diss/ms2-analyses/
---

<sub><sup>Analyses for manuscript 2 include estimating the association between infant physical growth from months 0 to 5 as an exposure and lipid levels at an average age of 17 years as an outcome. Two different types of analyses will be used to test the hypothesis that extreme levels of infant growth will influence lipid levels in adolescence. First, growth will be characterized by the SITAR method, which extracts out up to three different aspects of growth for an individual and uses that as an exposure in regression models with univariate measures of lipids. Second, a latent growth mixture model (LGMM) divides growth patterns into distinct 'latent growth classes' that serves as the exposure and the lipids, either as univariate or combined into one latent factor, will serve as the outcome.</sup></sub>


# Manuscript

<!--  * Draft manuscript in
    * [word format](../../unc-dissertation-markdown-p2/includes/scripts/paper2/draft/ms2.docx)
    * [pdf format](../../unc-dissertation-markdown-p2/includes/scripts/paper2/draft/ms2.pdf)
    * [html format](../../unc-dissertation-markdown-p2/includes/scripts/paper2/draft/ms2.html)
-->

<!--
[Tables and figures, html version](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-all.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-all.Rmd)  
-->

  * [Tables and figures, pdf version](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-all-pdfversion.pdf) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-all-pdfversion.Rmd) 

---

  * [Tables and figures with breastfeeding as confounder, pdf version](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-all-bf-pdfversion.pdf) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-all-bf-pdfversion.Rmd) 

<!--[Tables and figures](../../unc-dissertation-markdown-p2/includes/scripts/paper2/ms-tables/tables-ms.pdf) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/ms-tables/tables-ms.Rmd) 
-->

<!--
# Overall summary

[Overall summary of results](../../unc-dissertation-markdown-p2/includes/scripts/paper2/overall-summary.html)
-->

# AHA Epi/Lifestyle 2018 abstract

  * [abstract](../../unc-dissertation-markdown-p2/includes/scripts/paper2/aha2018/abstract-m2.html) -- [word version](../../unc-dissertation-markdown-p2/includes/scripts/paper2/aha2018/abstract-m2.docx)

  * [slides](../../unc-dissertation-markdown-p2/includes/scripts/paper2/aha2018/slides-growth-lipid-levels.pdf)


---

# 1. Statistical analysis plan

  * [Statistical analysis plan (SAP)](../../unc-dissertation-markdown-p2/includes/scripts/paper2/sap2.html) -- [code for SAP](../../unc-dissertation-markdown-p2/includes/scripts/paper2/sap2.Rmd)

<p></p>

# 2. Data handling scripts

  * **Note**: data handling done with the [first paper](/diss/ms1-analyses).

<p></p>

## 3. Misc

  * [Check association between breastfeeding status and lipid outcomes](../../unc-dissertation-markdown-p2/includes/scripts/paper2/misc-table-compare-bf.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/misc-table-compare-bf.Rmd)


<!--
# 3. Table of descriptive statistics

  * [Table 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/table1.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/table1.Rmd)

<p></p>


# 4. Association between infant growth and lipid measurements

## 4a. SITAR 

  * [Association between growth parameters and lipids](../../unc-dissertation-markdown-p2/includes/scripts/paper2/initial-m2.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/initial-m2.Rmd)

## 4b. LGMM

[Results, .pdf](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-all-pdfversion.pdf) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-all-pdfversion.Rmd)

-->




<!--
### Tables for manuscript

- [Pooled sample](../../unc-dissertation-markdown-p2/includes/scripts/paper2/ms-tables/table2-ms.pdf) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/ms-tables/table2-ms.Rmd)

- [Stratified sample](../../unc-dissertation-markdown-p2/includes/scripts/paper2/ms-tables/table2-strat-ms.pdf) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/ms-tables/table2-strat-ms.Rmd)
-->

<!--
### Pooled by sex of child

- [Association between latent growth classes and an observed univariate distal outcome (lipid) -- Using BCH 3-step approach for distal variable. Pooled by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read.Rmd)
  
    - Templates used to create Mplus .inp files
        - [Step 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step1-pooled-univ.txt)
        - [Step 3](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step3-2-class-pooled-univ.txt)
    
    
- [Unadjusted association between latent growth classes and an observed univariate distal outcome (lipid) -- Using BCH 3-step approach for distal variable. Pooled by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-unadj-read.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-unadj-read.Rmd)
  
    - Templates used to create Mplus .inp files
        - [Step 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step1-pooled-bch-noadjust.txt)
        - [Step 3](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step3-2-class-pooled-univ.txt)
        
-->
        
<!--      * Sensitivity analysis. Subset of data.

          * These analyses use the exact same scripts as the prior one except outliers (>3sd of lipid distribution) are excluded (<5% of the data).

          - [Restricted analyses: Association between latent growth classes and an observed univariate distal outcome (lipid) -- Using DU3step 3-step approach for distal variable. Pooled by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/v2-pooled/sensitivity/models-2-results-univariate-distal-assn-pooled-du3step-sens.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/v2-pooled/sensitivity/models-2-results-univariate-distal-assn-pooled-du3step-sens.Rmd)
-->          

<!--
---

* TG / HDL ratios and TG-HDL correlations
      
- [Estimated TG/HDL ratios and correlations for pooled sample, adjusted](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-pooled-bch-ratio.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-pooled-bch-ratio.Rmd)
    - Templates used to create Mplus .inp files
        - [Step 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step1-pooled-ratio.txt)
        - [Step 3](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step3-2-class-pooled-ratio.txt)
        
- [Estimated TG/HDL ratios and correlations for pooled sample, unadjusted](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-pooled-bch-ratio-unadj.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-pooled-bch-ratio-unadj.Rmd)
    - Templates used to create Mplus .inp files
        - [Step 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step1-pooled-ratio.txt)
        - [Step 3](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step3-2-class-pooled-ratio-noadjust.txt)
        

### Stratified by sex of child

- [Association between latent growth classes and an observed univariate distal outcome (lipid) -- Using 3-step approach for distal variable. Stratified by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-strat.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-strat.Rmd)

  - Templates used to create Mplus .inp files
    - [Step 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step1-strat-ratio.txt)
    - [Step 3](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step3-2-class-strat-ratio.txt)
    

- [Unadjusted association between latent growth classes and an observed univariate distal outcome (lipid) -- Using 3-step approach for distal variable. Stratified by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-unadj-strat.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-unadj-strat.Rmd)

  - Templates used to create Mplus .inp files
    - [Step 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step1-strat-ratio.txt)
    - [Step 3](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step3-2-class-strat-ratio-noadjust.txt)
-->


<!--
      * Sensitivity analysis. Subset of data.

          * These analyses use the exact same scripts as the prior one except outliers (>3sd of lipid distribution) are excluded (<5% of the data).

          - [Restricted analyses: Association between latent growth classes and an observed univariate distal outcome (lipid) -- Using DU3step 3-step approach for distal variable. Stratified by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/v2/sensitivity/models-2-results-univariate-distal-assn-du3step-sens.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/v2/sensitivity/models-2-results-univariate-distal-assn-du3step-sens.Rmd)
-->

<!--

- TG / HDL ratios and TG-HDL correlations
      
- [Estimated tg/hdl ratios and correlations for stratified sample, adjusted](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-strat-bch-ratio.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-strat-bch-ratio.Rmd)
          
    - Templates used to create Mplus .inp files
      - [Step 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step1-strat-ratio.txt)
      - [Step 3](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step3-2-class-strat-ratio.txt)
              
- [Unadjusted estimates of tg/hdl ratios and correlations for stratified sample](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-strat-bch-ratio-unadj.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/models-2-results-univariate-distal-assn-strat-bch-ratio-unadj.Rmd)
          
    - Templates used to create Mplus .inp files
      - [Step 1](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step1-strat-ratio.txt)
      - [Step 3](../../unc-dissertation-markdown-p2/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates/template_mplus2-step3-2-class-strat-ratio-noadjust.txt)
-->

<!--
#### The following sections for LGMM use the default for distal variable (one-step method) and may not have a meaningful interpretation.

  - [Association between latent growth classes and an observed univariate distal outcome (lipid) -- Using default approach for distal variable](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/models-2-results-univariate-distal-assn.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/models-2-results-univariate-distal-assn.Rmd) -- [Template used to create Mplus .inp files](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/template_mplus2-strat-sex-assn-classes-univ-distal.txt)
  
  - Follow-up: [Checked overlap between height trajectory analyses for males](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/m2-univ-distal-compare-people-in-classes.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/univariate/m2-univ-distal-compare-people-in-classes.Rmd)
  

  - [Association between latent growth classes and a latent distal outcome -- using default approach](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/latent-class-and-latent-distal-outcome/models-2-results-lc-latent-distal-assn.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/latent-class-and-latent-distal-outcome/models-2-results-lc-latent-distal-assn.Rmd) -- [Template used to create Mplus .inp files](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/latent-class-and-latent-distal-outcome/template_mplus2-strat-sex-assn-classes-latentdistal.txt)
      * **Note**: Holding the latent distal outcome the same across different latent growth classes. If not employing that assumption then the comparison of associations between growth and the latent distal outcome would be like comparing apples and oranges.

  - [Association between growth and latent distal outcomes; no latent growth classes](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/models-2-results-latent-distal-assn.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/models-2-results-latent-distal-assn.Rmd) -- [Template used to create Mplus .inp files](../../unc-dissertation-markdown-p2/includes/scripts/paper2/lgmm/virtuallab/distal/template_mplus2-strat-sex-assn-latentdistal.txt)


  * **NOTE**: I create the Mplus models with [MplusAutomation in R](../includes/scripts/paper1/lgmm/export-mplus.Rmd) with scripts to create batches of Mplus files that I run in virtuallab with an [.R script](../includes/scripts/paper2/lgmm/virtuallab/run-models.R).
-->