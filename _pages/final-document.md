---
layout: single
title : Dissertation document
permalink: /diss/final-doc/
---

## Draft 

* [Dissertation draft, pdf format](../../unc-dissertation-markdown-p2/dissertation.pdf)

    * Note: -- in [pdf format as expected for submission](https://gradschool.unc.edu/academics/thesis-diss/guide/submission.html)
    
    * [Departmental guidelines for dissertation submission](https://sph.unc.edu/files/2017/09/Acad_Policies_Fall_2017.pdf)

## Scripts used to create tables and figures for dissertation document

### Initial parts of dissertation document

* [R markdown document to compile and format dissertation](../../unc-dissertation-markdown-public/dissertation.Rmd)

### Manuscript 1
    
* [Compile tables into one pdf document](../../unc-dissertation-markdown-public/includes/scripts/paper1/tables-ms.Rmd)

   * [Table 1](../../unc-dissertation-markdown-public/includes/scripts/paper1/table1-rev-ms.Rmd)
   * [Table 2](../../unc-dissertation-markdown-public/includes/scripts/paper1/table2-mice.Rmd)

   * [Table 3](../../unc-dissertation-markdown-public/includes/scripts/paper1/table2-mice-ht.Rmd)
            
   * [Table 4](../../unc-dissertation-markdown-public/includes/scripts/paper1/table2-mice-wfl.Rmd)
            
   * [Imputation script](../../unc-dissertation-markdown-public/includes/scripts/paper1/table3-data-handle-weight-impute-rev.Rmd)
            
### Manuscript 2

* [Compile tables into one pdf document](../../unc-dissertation-markdown-public/includes/scripts/paper2/bch-read-all-bf-pdfversion.Rmd)
            
   * [Table 1](../../unc-dissertation-markdown-public/includes/scripts/paper2/table1.Rmd)
   
   * [Table 2 (SITAR results)](../../unc-dissertation-markdown-public/includes/scripts/paper2/initial-m2-impute2.Rmd)
   
#### Table 3 -- LGMM results
   
   * [longleaf shell script](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/run-files-data.sh)
   
   * [.R file to run .Rmd file with Mplus analyses](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/run-mplus-prep.R)
   
   * [.Rmd file to run Mplus analyses via MplusAutomation package](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/m2-data-scripts-bf.Rmd)
   
   * Subsequent to the longleaf run I would transfer all files to my local desktop for further formatting.
   
      * [Aggregate all Mplus .out files into single R data frames with MplusAutomation](../../unc-dissertation-markdown-public/includes/scripts/paper2/bch-read-all-bf-pdfversion.Rmd)
   
   