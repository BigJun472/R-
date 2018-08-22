# R-
#R:GO、KEGG analysis
##included packages:

source("http://bioconductor.org/bioclite.R")
bioclite("clusterProfiler")
bioclite("topGO")
bioclite("Rgraphviz")
bioclite("pathview")
bioclite("org.Hs.eg.db")

#loda above packages
library(clusterProfiler)
library(topGO)
library(Rgraphviz)
library(pathview)
library(org.Hs.eg.db)

