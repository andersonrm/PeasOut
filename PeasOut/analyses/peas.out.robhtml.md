---
title: "Peas Out Rob"
author: "Rob Clark & Riley Anderson"
date: 'October 09, 2023'
graphics: yes
output:
  html_document:
    keep_md: yes
    theme: readable
    mathjax: default
  github_document:
    toc: yes
    toc_depth: 5
    pandoc_args: --webtex
  html_notebook:
    code_folding: hide
    theme: readable
    mathjax: default
  pdf_document:
    toc: yes
header-includes:
  \usepackage{float}
  \floatplacement{figure}{H}
editor_options:
  chunk_output_type: console
---





## Overview

This analysis explores Rob Clark's "Peas Out" data. 

## Experimental Design

24 bug dorms (2m x 2m x 2m) were established on an experimental farm plot that was sown with banner pea. The dorms were laid out in a square design with 8 control dorms in the center. Control dorms were flanked by 2 sides (4 dorms/side) where common vetch was planted in the distal half (the outer circumference of the square) and banner pea was planted in the proximal half (the inner circumference of the square). Diagonally from the vetch dorms were 2 sides similarly planted with red clover.




```r

knitr::include_graphics("images/peas.out.design.png", error = FALSE)
```

![](images/peas.out.design.png)<!-- -->



### Summary of Results
* 










## Session Information


```
R version 4.2.3 (2023-03-15 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 19045)

Matrix products: default

locale:
[1] LC_COLLATE=English_United States.utf8 
[2] LC_CTYPE=English_United States.utf8   
[3] LC_MONETARY=English_United States.utf8
[4] LC_NUMERIC=C                          
[5] LC_TIME=English_United States.utf8    

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] sjPlot_2.8.13      glmmTMB_1.1.6      multcompView_0.1-9 piecewiseSEM_2.3.0
 [5] MuMIn_1.47.5       emmeans_1.8.5      lubridate_1.9.2    forcats_1.0.0     
 [9] stringr_1.5.0      dplyr_1.1.1        purrr_1.0.1        readr_2.1.4       
[13] tidyr_1.3.0        tibble_3.2.1       ggplot2_3.4.1      tidyverse_2.0.0   
[17] multcomp_1.4-23    TH.data_1.1-2      MASS_7.3-58.2      survival_3.5-3    
[21] mvtnorm_1.1-3      car_3.1-2          carData_3.0-5      lme4_1.1-32       
[25] Matrix_1.6-1      

loaded via a namespace (and not attached):
 [1] nlme_3.1-162        insight_0.19.1      RColorBrewer_1.1-3 
 [4] rprojroot_2.0.3     numDeriv_2016.8-1.1 backports_1.4.1    
 [7] tools_4.2.3         TMB_1.9.2           bslib_0.4.2        
[10] utf8_1.2.3          R6_2.5.1            sjlabelled_1.2.0   
[13] colorspace_2.1-0    withr_2.5.0         tidyselect_1.2.0   
[16] compiler_4.2.3      performance_0.10.2  cli_3.6.1          
[19] sandwich_3.0-2      bayestestR_0.13.0   sass_0.4.5         
[22] scales_1.2.1        digest_0.6.31       minqa_1.2.5        
[25] rmarkdown_2.21      pkgconfig_2.0.3     htmltools_0.5.5    
[28] fastmap_1.1.1       highr_0.10          htmlwidgets_1.6.2  
[31] rlang_1.1.0         rstudioapi_0.14     visNetwork_2.1.2   
[34] jquerylib_0.1.4     generics_0.1.3      zoo_1.8-12         
[37] jsonlite_1.8.4      magrittr_2.0.3      Rcpp_1.0.10        
[40] munsell_0.5.0       fansi_1.0.4         abind_1.4-5        
[43] lifecycle_1.0.3     stringi_1.7.12      yaml_2.3.7         
[46] grid_4.2.3          sjmisc_2.8.9        lattice_0.20-45    
[49] ggeffects_1.2.0     splines_4.2.3       sjstats_0.18.2     
[52] hms_1.1.3           knitr_1.42          pillar_1.9.0       
[55] boot_1.3-28.1       estimability_1.4.1  codetools_0.2-19   
[58] stats4_4.2.3        glue_1.6.2          evaluate_0.20      
[61] modelr_0.1.11       vctrs_0.6.1         nloptr_2.0.3       
[64] tzdb_0.3.0          gtable_0.3.3        datawizard_0.7.0   
[67] cachem_1.0.7        xfun_0.38           xtable_1.8-4       
[70] broom_1.0.4         timechange_0.2.0    DiagrammeR_1.0.10  
```


