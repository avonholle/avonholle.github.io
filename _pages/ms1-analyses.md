---
layout: single
title : analyses for manuscript 1 -- Sociodemographic predictors of early postnatal growth
permalink: /diss/ms1-analyses/
---

## Description

Analyses for manuscript 1 include estimating the association between prenatal predictors and infant physical growth from months 0 to 5 as an outcome. In the manuscripte, we will focus on characterizing growth by the SITAR method, which extracts out up to three different aspects of growth for an individual and uses that as an exposure in regression models with univariate measures of lipids.


## Manuscript draft

  * Manuscript formatted for BMJ Open, 1/2019
    * [Word format](../../unc-dissertation-markdown-p2/includes/scripts/paper1/draft/full-manuscript-tosubmitdraft-bmjopen.docx)

<!--   * [Word format](../../unc-dissertation-markdown-p2/includes/scripts/paper1/draft/full-manuscript-submitted.docx) -- [pdf format](../../unc-dissertation-markdown-p2/includes/scripts/paper1/draft/full-manuscript-submitted.pdf) -- [code for manuscript](../../unc-dissertation-markdown-p2/includes/scripts/paper1/draft/full-manuscript.Rmd) and [titlepage script](../../unc-dissertation-markdown-p2/includes/scripts/paper1/draft/ms-jech-titlepage.Rmd) and [tables](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev5/tables-ms-jech.Rmd) -->
    
<!--  * Draft manuscript in 
    * [Word format](../../unc-dissertation-markdown-p2/includes/scripts/paper1/draft/ms1.docx)
    * [pdf format](../../unc-dissertation-markdown-p2/includes/scripts/paper1/draft/ms1.pdf)
    * [html format](../../unc-dissertation-markdown-p2/includes/scripts/paper1/draft/ms1.html)-->

  * [Formatted tables 1-4 for manuscript (pdf)](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev5/tables-ms.pdf) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev5/tables-ms.Rmd)
  
    * Code: [Table 1](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev5/table1-rev-ms.Rmd) -- [Table 2](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev5/table2-mice-ms.Rmd) -- [Table 3](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev5/table2-mice-ht-ms.Rmd) -- [Table 4](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev5/table2-mice-wfl-ms.Rmd)

  * [Google docs source document for manuscript](https://docs.google.com/document/d/1sqjSOwP_TUdE20elaogdvLT-J9tWwCOA5NEZTfCg3X0/edit?usp=sharing)

    * Note: I use this google doc as my source to create the following files using Rmarkdown as shown [here](/misc/edits/).
    

## Manuscript draft outline for discussion

  * [Outline as requested 4/2018](../../unc-dissertation-markdown-p2/includes/scripts/paper1/draft/ms1-discussion-outline.docx)
      * [Google docs draft](https://docs.google.com/document/d/1gdWsKwNg9iOMS9-bPFRTJq3RE0W64rEeFBDBTzccfeU/edit?usp=sharing)


# SER 2018

  * [Poster](../../unc-dissertation-markdown-p2/includes/scripts/paper1/draft/SER/sociodemographic-predictors-early.pdf) -- [Overleaf source code](https://www.overleaf.com/read/fjhffmnyjykc)

  * [Abstract html draft](../../unc-dissertation-markdown-p2/includes/scripts/paper1/draft/SER/SER2018-abstract-ms1.html)  -- [Word draft, .docx](../../unc-dissertation-markdown-p2/includes/scripts/paper1/draft/SER/SER2018-abstract-ms1.docx) -- [link to google doc for editing](https://docs.google.com/document/d/1cz2wNXp2VFLM3jG2q8v4F7hbK9Upsk_1_Y2BdhTi3pk/edit?usp=sharing)


<!--An overall summary can be found [here](../../unc-dissertation-markdown-p2/includes/scripts/paper1/overall-summary.html).-->


## 1. Statistical analysis plan

  * [Statistical analysis plan (SAP)](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sap1.html) -- [code for SAP](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sap1.Rmd)

<p></p>

## 2. Data handling scripts

  * [Read in 2014 data -- 5-year old cohort](../../unc-dissertation-markdown-p2/includes/scripts/paper1/Descriptive.Rmd)

  * [Read in 2017 data -- 1-year old cohort](../../unc-dissertation-markdown-p2/includes/scripts/paper1/read-phenotypes.Rmd)
  
  * [preliminary descriptive statistics](../../unc-dissertation-markdown-p2/includes/scripts/paper1/descriptive_statistics.Rmd)

  * [data imputation](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table3-data-handle-weight-impute.Rmd)

<p></p>

## 3. Table of descriptive statistics

  * [Table 1, for full infancy cohort](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table1-rev.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table1-rev.Rmd)


  * [Table 1, for age 17 cohort subset](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table1.pdf) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table1.Rmd)

<p></p>

## 4. Evaluate model fit for the SITAR models

  * [Results for model fit for weight, height and wfl outcomes](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev5/fit-summary.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev5/fit-summary.Rmd)


<!--
## 5. Association between sociodemographic predictors and infant growth through random effects from SITAR

### 5a. First, infancy cohort (full sample) with lasso point estimates


* [Results for weight](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev5/table2-mice.html) -- [code](../includes/scripts/paper1/sitar-rev5/table2-mice.Rmd)

* [Results for height](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev5/table2-mice-ht.html) -- [code](../includes/scripts/paper1/sitar-rev5/table2-mice-ht.Rmd)

* [Results for weight-for-length (wfl)](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev5/table2-mice-wfl.html) -- [code](../includes/scripts/paper1/sitar-rev5/table2-mice-wfl.Rmd)


### 5b. Subset (year 17 cohort) with a lasso approach to choose subset of confounders

1. [Results for weight](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev/table2-mice.html) -- [code](../includes/scripts/paper1/sitar-rev/table2-mice.Rmd)

2. [Results for height](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev/table2-mice-ht.html) -- [code](../includes/scripts/paper1/sitar-rev/table2-mice-ht.Rmd)

3. [Results for weight-for-length (wfl)](../../unc-dissertation-markdown-p2/includes/scripts/paper1/sitar-rev/table2-mice-wfl.html) -- [code](../includes/scripts/paper1/sitar-rev/table2-mice-wfl.Rmd)

### 5c. Same approach as Pizzi 2014 **[no longer using these results. For reference only.]** with subset (year 17 cohort)

**Paper**: Pizzi, Costanza, Tim J. Cole, Lorenzo Richiardi, Isabel dos-Santos-Silva, Camila Corvalan, and Bianca De Stavola. 2014. “Prenatal Influences on Size, Velocity and Tempo of Infant Growth: Findings from Three Contemporary Cohorts.” Edited by Guoying Wang. PLoS ONE 9 (2): e90291. doi:10.1371/journal.pone.0090291.

1. [Results for weight](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table2-mice.html) -- [code](../includes/scripts/paper1/table2-mice.Rmd)

2. [Results for height](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table2-mice-ht.html) -- [code](../includes/scripts/paper1/table2-mice-ht.Rmd)

3. [Results for weight-for-length (wfl)](../../unc-dissertation-markdown-p2/includes/scripts/paper1/table2-mice-wfl.html) -- [code](../includes/scripts/paper1/table2-mice-wfl.Rmd)

---
-->

## 5. Latent class growth mixture models (LGMM) model fit

  1. [Model fit info -- stratified by sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/strat-sex/summarize-mplus-results-sex-strat.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/strat-sex/summarize-mplus-results-sex-strat.Rmd)

      - [Template used to create Mplus files](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/template_mplus1-strat-sex.txt)
      
  2. [Model fit info -- pooled by sex of child and growth factors adjusted for sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/pooled-fit/summarize-mplus-results-sex-pooled.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/pooled-fit/summarize-mplus-results-sex-pooled.Rmd)
  
        - [Template used to create Mplus files](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/template_mplus1-pooled-fit.txt)
        

## 6. Misc

  * [Check association between breastfeeding status and graffar index](../../unc-dissertation-markdown-p2/includes/scripts/paper1/misc-table-compare-bf2.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/misc-table-compare-bf2.Rmd)


   * [check dropout by attrition status](../../unc-dissertation-markdown-p2/includes/scripts/paper1/check-dropout.html)


<!-- The following scripts didn't adjust for sex -- just pooled

2. [Model fit info -- pooled across sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/adj-sex/summarize-mplus-results.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/adj-sex/summarize-mplus-results.Rmd)

      - [Template used to create Mplus files](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/template_mplus1-bysex.txt)
-->

<!--
### 6b. Association estimates

1. [Estimated association between maternal characterisics and child growth parameters -- pooled across sex of child](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/assn/models-results-plots-assn.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/assn/models-results-plots-assn.Rmd)

### NOTE

I create the Mplus models with [MplusAutomation in R](../includes/scripts/paper1/lgmm/export-mplus.Rmd) with scripts to create batches of Mplus files that I run on batches of files in virtuallab with an [.R script](../../unc-dissertation-markdown-p2/includes/scripts/paper1/lgmm/virtuallab/run-models.R).

-->
