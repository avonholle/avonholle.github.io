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
   * This markdown document relies on following .tex files all adapted LaTeX files written by graduate students in the UNC Dept of Math(https://github.com/mmalahe/unc-dissertation)
      * [document settings](../../unc-dissertation-markdown-public/includes/tex/doc_prefix_unc.tex)
      * [more document settings](../../unc-dissertation-markdown-public/includes/tex/glossaryfile.tex)
      * [glossary](../../unc-dissertation-markdown-public/includes/tex/header-unc.tex)
      * [LaTeX Document Class File](../../unc-dissertation-markdown-public/uncdissertation.cls)

### Manuscript 1
    
* [Compile tables into one pdf document](../../unc-dissertation-markdown-public/includes/scripts/paper1/sitar-rev5/tables-ms.Rmd)  
   * [Table 1](../../unc-dissertation-markdown-public/includes/scripts/paper1/sitar-rev5/table1-rev-ms.Rmd)  
   * [Table 2](../../unc-dissertation-markdown-public/includes/scripts/paper1/sitar-rev5/table2-mice.Rmd)
   * [Table 3](../../unc-dissertation-markdown-public/includes/scripts/paper1/sitar-rev5/table2-mice-ht.Rmd)   
   * [Table 4](../../unc-dissertation-markdown-public/includes/scripts/paper1/sitar-rev5/table2-mice-wfl.Rmd)  
   * [Imputation script](../../unc-dissertation-markdown-public/includes/scripts/paper1/sitar-rev5/table3-data-handle-weight-impute-rev.Rmd)
   



### Manuscript 2

* [Compile tables into one pdf document](../../unc-dissertation-markdown-public/includes/scripts/paper2/bch-read-all-bf-pdfversion.Rmd)  
   * [Table 1](../../unc-dissertation-markdown-public/includes/scripts/paper2/table1.Rmd)  
   * [Table 2 (SITAR results)](../../unc-dissertation-markdown-public/includes/scripts/paper2/initial-m2-impute2.Rmd)  
   * Table 3 -- LGMM results  
       * [longleaf shell script](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/run-files-data.sh.txt)  
         * [.R file to run .Rmd file with Mplus analyses in longleaf](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/run-mplus-prep.R)  
         * [.Rmd file to run Mplus analyses via MplusAutomation on longleaf package](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/m2-data-scripts-bf.Rmd)  
             * Templates referenced in file above to generate Mplus models by sex of child, type of outcome, and type of lipid exposure: 
                 1. Pooled, adjusted: [step 1, make data](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step1-pooled-univ.txt), [step 3, 2 class](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step3-2-class-pooled-univ.txt), [step 3, 3-class](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step3-3-class-pooled-univ.txt)  
                 2. Pooled, not adjusted: [step 1, make data](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step1-pooled-noad.txt), [step 3, 2 class](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step3-2-class-pooled-noadj.txt), [step 3, 3-class](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step3-3-class-pooled-noadj.txt)  
                 3. Pooled ratio, adjusted: [step 3, 2 class](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step3-2-class-pooled-ratio.txt)
                 4. Pooled ratio, not adjusted: [step 3, 2 class](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step3-2-class-pooled-ratio-noadjust.txt)
                 5. Stratified, adjusted:  [step 1, make data](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step1-strat-univ.txt), [step 3, 2 class](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step3-2-class-strat-univ.txt), [step 3, 3-class](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step3-3-class-strat-univ.txt)  
                 6. Stratified, not adjusted:  [step 1, make data](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step1-strat-univ-noadj.txt), [step 3, 2 class](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step3-2-class-strat-univ-noadj.txt), [step 3, 3-class](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step3-3-class-strat-univ-noadj.txt)                   
                 7. Stratified ratio, adjusted:  [step 3, 2 class](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step3-2-class-strat-ratio.txt)
                 8. Stratified ratio, adjusted:  [step 3, 2 class](../../unc-dissertation-markdown-public/includes/scripts/paper2/longleaf/compile-mplus/mplus-templates-bf/template_mplus2-step3-2-class-strat-ratio-noadjust.txt)  
                 
    * Subsequent to the longleaf run I would transfer all .out files to my local desktop for further formatting.  
        * [Aggregate all Mplus .out files into single R data frames with MplusAutomation](../../unc-dissertation-markdown-public/includes/scripts/paper2/bch-read-all-bf-pdfversion.Rmd)  
   
   
### Manuscript 3

* [Compile tables into one pdf document](../../unc-dissertation-markdown-public/includes/scripts/paper3/ms3-read-all-pdfversion.Rmd)  
    * [Table 1](../../unc-dissertation-markdown-public/includes/scripts/paper3/table1.Rmd)  
    * [Tables 2-5](../../unc-dissertation-markdown-public/includes/scripts/paper3/ms3-read-all-pdfversion.Rmd)  
        * Tables 2-5 are from aggregate data compiled in the longleaf computing cluster:
            * [longleaf shell script for analyses](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/run-files-data.sh.txt) 
                * [.R file to run .Rmd file with Mplus analyses in longleaf](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/run-mplus-prep.R)  
                   * [.Rmd file to read in snps and merge with phenotypes](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/get-snp-data.Rmd)  
                      * [.Rmd file to get phenotype data phenotypes](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/get-phen-data.Rmd)  
                      * [.Rmd file to get phenotype data phenotypes](../../unc-dissertation-markdown-public/includes/scripts/power/aim3/power-calcs-ind-assoc.Rmd)  
                          * [.R file to get lipid SNPs](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/create-list-snps-for-vcf.R)  
                   * [.Rmd file to run Mplus analyses via MplusAutomation on longleaf package](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/m3-data-scripts.Rmd)  
                      * [Export growth phenotype data for merge](../../unc-dissertation-markdown-public/includes/scripts/paper1/lgmm/export-mplus.Rmd)
                      * Templates to generate Mplus files run in .Rmd file above
                           1. Pooled, unadjusted: [step 1](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/mplus-tempates/pooled/template-m3-mplus-univ-distal-step1-pooled.txt), [step 3, 2-class](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/mplus-tempates/pooled/template-m3-mplus-univ-distal-step3-2class-pooled.txt), [step 3, 3-class](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/mplus-tempates/pooled/template-m3-mplus-univ-distal-step3-3class-pooled.txt)
                           2. Pooled, adjusted: [step 1](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/mplus-tempates/pooled-adj/template-m3-mplus-univ-distal-step1-pooled-adj.txt), [step 3, 2-class](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/mplus-tempates/pooled-adj/template-m3-mplus-univ-distal-step3-2class-pooled-adj.txt), [step 3, 3-class](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/mplus-tempates/pooled-adj/template-m3-mplus-univ-distal-step3-3class-pooled-adj.txt)
                           3. Stratified, unadjusted: [step 1](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/mplus-tempates/strat/template-m3-mplus-univ-alt-distal-step1.txt), [step 3, 2-class](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/mplus-tempates/strat/template-m3-mplus-univ-alt-distal-step3-2class.txt), [step 3, 3-class](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/mplus-tempates/strat/template-m3-mplus-univ-alt-distal-step3-3class.txt)
                           4. Stratified, adjusted: [step 1](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/mplus-tempates/strat-adj/template-m3-mplus-univ-alt-distal-step1-adj.txt), [step 3, 2-class](../../unc-dissertation-markdown-public/includes/scripts/paper3/longleaf/compile-mplus/mplus-tempates/strat-adj/template-m3-mplus-univ-alt-distal-step3-2class-adj.txt)           


#### Appendices

  * [Appendix A: Graffar Index Component Description](../../unc-dissertation-markdown-public/sections/appendix-graffar-desc.Rmd)
      * [Set up data for table](../../unc-dissertation-markdown-public/includes/scripts/paper1/sitar-rev5/tables-ms.Rmd)  
      * [Data handling script 1](../../unc-dissertation-markdown-public/includes/scripts/paper1/Descriptive2.Rmd)  
      * [Data handling script 2](../../unc-dissertation-markdown-public/includes/scripts/paper1/descriptive_statistics.Rmd)  
  * [Appendix B: SITAR model fit](../../unc-dissertation-markdown-public/sections/appendix-model-fit-sitar.Rmd)
     * [Compile results from longleaf run](../../unc-dissertation-markdown-public/includes/scripts/paper1/sitar-rev5/fit-summary.Rmd)  
        * [Shell script for longleaf](../../unc-dissertation-markdown-public/includes/scripts/paper1/longleaf/model-fit/run-fit-files.sh.txt)  
        * [R file to knit docs in longleaf](../../unc-dissertation-markdown-public/includes/scripts/paper1/longleaf/model-fit/run-fit-files.R)       
        * [Run SITAR models on longleaf run](../../unc-dissertation-markdown-public/includes/scripts/paper1/longleaf/model-fit/table3-w-fcns.Rmd)  
          * [Data for SITAR models on longleaf run](../../unc-dissertation-markdown-public/includes/scripts/paper1/longleaf/model-fit/table3-data-handle-weight.Rmd)  
  * [Appendix C: LGMM model fit](../../unc-dissertation-markdown-public/sections/appendix-model-fit-lgmm.Rmd)
     * [Compile results for table, pooled](../../unc-dissertation-markdown-public/includes/scripts/paper1/longleaf/compile-mplus/summarize-mplus-results-sex-pooled.Rmd)
     * [Compile results for table, sex stratified](../../unc-dissertation-markdown-public/includes/scripts/paper1/longleaf/compile-mplus/summarize-mplus-results-sex-strat.Rmd)
        * [longleaf run shell script](../../unc-dissertation-markdown-public/includes/scripts/paper1/longleaf/compile-mplus/run-files-data.sh.txt)
        * [longleaf run .R file to knit documents](../../unc-dissertation-markdown-public/includes/scripts/paper1/longleaf/compile-mplus/run-mplus-prep.R)
        * [longleaf .Rmd file to run all Mplus scripts](../../unc-dissertation-markdown-public/includes/scripts/paper1/longleaf/compile-mplus/m1-data-scripts.Rmd)
           * [Mplus template, pooled](../../unc-dissertation-markdown-public/includes/scripts/paper1/longleaf/compile-mplus/mplus-templates/template_mplus1-pooled-fit.txt)
           * [Mplus template, sex  stratified](../../unc-dissertation-markdown-public/includes/scripts/paper1/longleaf/compile-mplus/mplus-templates/template_mplus1-strat-sex.txt)
  * [Appendix D: Lipid loci in Hispanic ancestry populations at genome-wide significance.](../../unc-dissertation-markdown-public/sections/appendix-a-rev.Rmd)
  * [Appendix E: All pairwise growth class differences in lipid distal outcome and mean lipid distal outcomes by latent class groups](../../unc-dissertation-markdown-public/sections/appendix-b-new.Rmd)
     * [Source of data: tables 2-5 in ms3 listed above](../../unc-dissertation-markdown-public/includes/scripts/paper3/ms3-read-all-pdfversion.Rmd)
  * [Appendix F: Background for power calculations](../../unc-dissertation-markdown-public/sections/appendix-d.Rmd)
    

