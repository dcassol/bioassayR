PKG_NAME=bioassayR

all:
	#"$(R_HOME)/bin$(R_ARCH_BIN)/Rscript" -e "library(knitr); knit2html('bioassayR.Rmd',options=c('toc',markdown::markdownHTMLOptions(TRUE)))"
	#"$(R_HOME)/bin$(R_ARCH_BIN)/Rscript" -e "library(knitr); knit('bioassayR.Rmd')"
	#pandoc --self-contained --output bioassayR.html -H header.html --from markdown --smart --table-of-contents --template html.template bioassayR.md;

	#"$(R_HOME)/bin$(R_ARCH_BIN)/Rscript" -e "library(knitrBootstrap); knit_bootstrap('${PKG_NAME}.Rmd',show_code=TRUE)"
	"$(R_HOME)/bin$(R_ARCH_BIN)/Rscript" -e "library(rmarkdown); library(BiocStyle); rmarkdown::render('${PKG_NAME}.Rmd')"
clean:
	rm -f *.md
