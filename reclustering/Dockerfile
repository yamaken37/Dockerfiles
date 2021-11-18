# Base Image
FROM bioconductor/bioconductor_docker:RELEASE_3_14

# Install R Packages
RUN R -e 'BiocManager::install(c("rTensor", "einsum"),update = FALSE)'