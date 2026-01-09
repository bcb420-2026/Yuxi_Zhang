FROM risserlin/bcb420-base-image:winter2025

RUN R -e "install.packages('BiocManager', repos='http://cran.us.r-project.org')"
RUN R -e "BiocManager::install(c('DESeq2', 'enrichplot', 'pheatmap'))"
