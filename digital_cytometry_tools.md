```R
## BisqueRNA：https://github.com/cozygene/bisque
.libpath("/cluster/home/ylin/miniconda3/envs/bisque/lib/R/library/")
library(BisqueRNA)

## CPM：https://cran.r-project.org/web/packages/scBio/index.html
.libpath("/cluster/home/ylin/miniconda3/envs/CPM/lib/R/library/")
library(scBio)

## deconvSeq：https://github.com/rosedu1/deconvSeq
.libpath("/cluster/home/ylin/miniconda3/envs/deconvSeq/lib/R/library/")
library(deconvSeq)

## DWLS：https://github.com/dtsoucas/DWLS
.libpath("/cluster/home/ylin/miniconda3/envs/MUSIC/lib/R/library/") ## 这个包我没有新建环境了，就用MUSIC就可以
source("/cluster/home/ylin/digital_cytometry/DWLS-master (source)/Deconvolution_functions.R")

## MuSiC：https://github.com/xuranw/MuSiC
.libpath("/cluster/home/ylin/miniconda3/envs/MUSIC/lib/R/library/")
library(MuSiC)

## SCDC：https://github.com/meichendong/SCDC
.libpath("/cluster/home/ylin/miniconda3/envs/SCDC/lib/R/library/")
source('/cluster/home/ylin/digital_cytometry/SCDC-master (source)/R/Basic_Functions.R')
source('/cluster/home/ylin/digital_cytometry/SCDC-master (source)/R/Deconvolution.R')
source('/cluster/home/ylin/digital_cytometry/SCDC-master (source)/R/ENSEMBLE.R')
source('/cluster/home/ylin/digital_cytometry/SCDC-master (source)/R/Visualization.R')

## notice：这些包的原文件都在"/cluster/home/ylin/digital_cytometry/"下面，有需自己cp
```

