FROM r-base:latest
RUN apt-get update \
	&& apt-get install -y --no-install-recommends pandoc \
	r-cran-data.table \
	r-cran-httr \
	r-cran-rmarkdown \
	r-cran-ggplot2
RUN Rscript -e 'utils::install.packages(c("renv"))'
