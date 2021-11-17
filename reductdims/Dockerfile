# https://www.bioconductor.org/help/docker/
# 20211117_latest_3_14

# Base Image
FROM bioconductor/bioconductor_docker:RELEASE_3_14

# Add these files
ADD r/reductDims.R /
ADD r/cmd_reductDims.R /

# Install R Packages
RUN R -e 'install.packages(c("Rtsne", "irlba"), repos="http://cran.r-project.org")'