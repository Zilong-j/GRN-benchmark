R version 4.3.1 (2023-06-16)
Platform: x86_64-conda-linux-gnu (64-bit)
Running under: AlmaLinux 9.4 (Seafoam Ocelot)

Matrix products: default
BLAS/LAPACK: /mnt/iusers01/fatpou01/bmh01/msc-healthdatasci-2023-2024/z89953zj/.conda/envs/R1/lib/libopenblasp-r0.3.21.so;  LAPACK version 3.9.0

locale:
 [1] LC_CTYPE=en_GB.UTF-8       LC_NUMERIC=C              
 [3] LC_TIME=en_GB.UTF-8        LC_COLLATE=en_GB.UTF-8    
 [5] LC_MONETARY=en_GB.UTF-8    LC_MESSAGES=en_GB.UTF-8   
 [7] LC_PAPER=en_GB.UTF-8       LC_NAME=C                 
 [9] LC_ADDRESS=C               LC_TELEPHONE=C            
[11] LC_MEASUREMENT=en_GB.UTF-8 LC_IDENTIFICATION=C       

time zone: Europe/London
tzcode source: system (glibc)

attached base packages:
 [1] stats4    grid      parallel  stats     graphics  grDevices utils    
 [8] datasets  methods   base     

other attached packages:
 [1] peakRAM_1.0.2                     circlize_0.4.16                  
 [3] ComplexHeatmap_2.18.0             hdf5r_1.3.11                     
 [5] bench_1.1.3                       pryr_0.1.6                       
 [7] MOJITOO_1.0                       ggraph_2.2.1                     
 [9] igraph_2.0.3                      TFBSTools_1.38.0                 
[11] JASPAR2020_0.99.10                dplyr_1.1.4                      
[13] EnsDb.Hsapiens.v86_2.99.0         ensembldb_2.26.0                 
[15] AnnotationFilter_1.26.0           GenomicFeatures_1.54.4           
[17] AnnotationDbi_1.62.2              BSgenome.Hsapiens.UCSC.hg38_1.4.5
[19] BSgenome_1.68.0                   rtracklayer_1.60.0               
[21] Biostrings_2.68.1                 XVector_0.40.0                   
[23] Nebulosa_1.10.0                   patchwork_1.2.0                  
[25] scMEGA_1.0.2                      Signac_1.11.0                    
[27] SeuratObject_5.0.0                Seurat_4.4.0                     
[29] rhdf5_2.46.1                      SummarizedExperiment_1.30.2      
[31] Biobase_2.60.0                    MatrixGenerics_1.12.2            
[33] Rcpp_1.0.12                       Matrix_1.6-1.1                   
[35] GenomicRanges_1.52.0              GenomeInfoDb_1.36.1              
[37] IRanges_2.34.1                    S4Vectors_0.38.1                 
[39] BiocGenerics_0.46.0               matrixStats_1.3.0                
[41] data.table_1.14.8                 stringr_1.5.1                    
[43] plyr_1.8.9                        magrittr_2.0.3                   
[45] ggplot2_3.5.1                     gtable_0.3.5                     
[47] gtools_3.9.5                      gridExtra_2.3                    
[49] ArchR_1.0.2                      

loaded via a namespace (and not attached):
  [1] ica_1.0-3                   plotly_4.10.4              
  [3] Formula_1.2-5               zlibbioc_1.46.0            
  [5] tidyselect_1.2.1            bit_4.0.5                  
  [7] doParallel_1.0.17           clue_0.3-65                
  [9] lattice_0.22-6              rjson_0.2.21               
 [11] factoextra_1.0.7            blob_1.2.4                 
 [13] S4Arrays_1.0.4              dichromat_2.0-0.1          
 [15] hdrcde_3.4                  seqLogo_1.66.0             
 [17] png_0.1-8                   cli_3.6.3                  
 [19] ProtGenerics_1.34.0         goftest_1.2-3              
 [21] textshape_1.7.5             VIM_6.2.2                  
 [23] textshaping_0.3.7           BiocIO_1.10.0              
 [25] purrr_1.0.2                 chromVAR_1.22.1            
 [27] uwot_0.1.16                 curl_5.2.1                 
 [29] deSolve_1.40                mime_0.12                  
 [31] evaluate_0.24.0             leiden_0.4.3.1             
 [33] stringi_1.8.4               backports_1.5.0            
 [35] XML_3.99-0.17               httpuv_1.6.15              
 [37] rappdirs_0.3.3              splines_4.3.1              
 [39] RcppRoll_0.3.1              mclust_6.1.1               
 [41] jpeg_0.1-10                 rainbow_3.8                
 [43] pcaPP_2.0-4                 DT_0.33                    
 [45] sctransform_0.4.1           ggbeeswarm_0.7.2           
 [47] DBI_1.2.3                   smoother_1.3               
 [49] withr_3.0.0                 corpcor_1.6.10             
 [51] class_7.3-22                systemfonts_1.1.0          
 [53] rprojroot_2.0.4             lmtest_0.9-40              
 [55] tidygraph_1.3.1             htmlwidgets_1.6.4          
 [57] biomaRt_2.58.2              SingleCellExperiment_1.22.0
 [59] IRkernel_1.3.2              ggrepel_0.9.5              
 [61] labeling_0.4.3              SparseArray_1.0.10         
 [63] ranger_0.16.0               DEoptimR_1.1-3             
 [65] annotate_1.78.0             reticulate_1.38.0          
 [67] VariantAnnotation_1.48.1    hexbin_1.28.3              
 [69] zoo_1.8-12                  knitr_1.48                 
 [71] ggplot.multistats_1.0.0     TFMPvalue_0.0.9            
 [73] foreach_1.5.2               fansi_1.0.6                
 [75] fda_6.1.8                   caTools_1.18.2             
 [77] R.oo_1.26.0                 poweRlaw_0.80.0            
 [79] RSpectra_0.16-1             irlba_2.3.5.1              
 [81] ggrastr_1.0.2               lazyeval_0.2.2             
 [83] yaml_2.3.9                  survival_3.7-0             
 [85] scattermore_1.2             crayon_1.5.3               
 [87] RcppAnnoy_0.0.22            IRdisplay_1.1              
 [89] RColorBrewer_1.1-3          tidyr_1.3.1                
 [91] progressr_0.14.0            tweenr_2.0.3               
 [93] later_1.3.2                 ggridges_0.5.6             
 [95] fds_1.8                     codetools_0.2-20           
 [97] base64enc_0.1-3             GlobalOptions_0.1.2        
 [99] KEGGREST_1.40.0             Rtsne_0.17                 
[101] shape_1.4.6.1               Rsamtools_2.16.0           
[103] filelock_1.0.3              foreign_0.8-87             
[105] pkgconfig_2.0.3             xml2_1.3.6                 
[107] GenomicAlignments_1.36.0    scatterplot3d_0.3-44       
[109] spatstat.sparse_3.1-0       viridisLite_0.4.2          
[111] biovizBase_1.50.0           xtable_1.8-4               
[113] interp_1.1-6                car_3.1-2                  
[115] httr_1.4.7                  tools_4.3.1                
[117] globals_0.16.3              beeswarm_0.4.0             
[119] htmlTable_2.4.2             checkmate_2.3.1            
[121] nlme_3.1-165                dbplyr_2.5.0               
[123] assertthat_0.2.1            digest_0.6.36              
[125] farver_2.1.2                tzdb_0.4.0                 
[127] reshape2_1.4.4              ks_1.14.2                  
[129] viridis_0.6.5               DirichletMultinomial_1.42.0
[131] rpart_4.1.23                glue_1.7.0                 
[133] cachem_1.1.0                BiocFileCache_2.10.2       
[135] polyclip_1.10-6             ramify_0.3.3               
[137] Hmisc_5.1-3                 generics_0.1.3             
[139] mvtnorm_1.2-5               profmem_0.6.0              
[141] parallelly_1.37.1           here_1.0.1                 
[143] RcppHNSW_0.6.0              ragg_1.2.6                 
[145] carData_3.0-5               pbapply_1.7-2              
[147] nabor_0.5.0                 spam_2.10-0                
[149] utf8_1.2.4                  graphlayouts_1.1.1         
[151] RcppEigen_0.3.4.0.0         shiny_1.8.1.1              
[153] GenomeInfoDbData_1.2.11     R.utils_2.12.3             
[155] rhdf5filters_1.14.1         RCurl_1.98-1.14            
[157] memoise_2.0.1               rmarkdown_2.27             
[159] scales_1.3.0                R.methodsS3_1.8.2          
[161] future_1.33.2               RANN_2.6.1                 
[163] Cairo_1.6-2                 spatstat.data_3.1-2        
[165] rstudioapi_0.16.0           cluster_2.1.6              
[167] spatstat.utils_3.0-5        hms_1.1.3                  
[169] fitdistrplus_1.1-11         munsell_0.5.1              
[171] cowplot_1.1.3               colorspace_2.1-0           
[173] rlang_1.1.4                 xts_0.14.0                 
[175] dotCall64_1.1-1             ggforce_0.4.2              
[177] mgcv_1.9-1                  laeken_0.5.3               
[179] xfun_0.45                   e1071_1.7-14               
[181] CNEr_1.36.0                 iterators_1.0.14           
[183] abind_1.4-5                 tibble_3.2.1               
[185] Rhdf5lib_1.24.2             motifmatchr_1.24.0         
[187] readr_2.1.5                 repr_1.1.7                 
[189] bitops_1.0-7                promises_1.3.0             
[191] RSQLite_2.3.4               DelayedArray_0.26.6        
[193] pbdZMQ_0.3-11               proxy_0.4-27               
[195] GO.db_3.17.0                compiler_4.3.1             
[197] prettyunits_1.2.0           boot_1.3-30                
[199] listenv_0.9.1               tensor_1.5                 
[201] MASS_7.3-60.0.1             progress_1.2.3             
[203] uuid_1.2-0                  BiocParallel_1.34.2        
[205] spatstat.random_3.2-3       R6_2.5.1                   
[207] fastmap_1.2.0               fastmatch_1.1-4            
[209] vipor_0.4.7                 TTR_0.24.4                 
[211] ROCR_1.0-11                 vcd_1.4-12                 
[213] nnet_7.3-19                 KernSmooth_2.23-24         
[215] latticeExtra_0.6-30         miniUI_0.1.1.1             
[217] deldir_2.0-4                htmltools_0.5.8.1          
[219] ggthemes_5.1.0              bit64_4.0.5                
[221] spatstat.explore_3.2-6      lifecycle_1.0.4            
[223] destiny_3.16.0              Gviz_1.46.1                
[225] restfulr_0.0.15             vctrs_0.6.5                
[227] robustbase_0.99-3           spatstat.geom_3.2-9        
[229] sp_2.1-4                    future.apply_1.11.2        
[231] pracma_2.4.4                pillar_1.9.0               
[233] pcaMethods_1.94.0           jsonlite_1.8.8             
[235] GetoptLong_1.0.5           
