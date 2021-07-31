
## TODO

https://search.r-project.org/CRAN/refmans/xfun/html/gsub_file.html
metadata
prepare-locs (as a first stage, general use preparing. not to handle specific eg. movement ecology preparation etc)


``` bash
grep -rni ../ --include \*.Rmd -e 'TODO:' || true;
```

    ## ../06-git.Rmd:4:**TODO: ALR**
    ## ../06-git.Rmd:140:**TODO: add examples / links to ci for package checks, website builds, host static public sites**
    ## ../06-git.Rmd:144:**TODO: expand to example of using ci to run tests script on output data**
    ## ../04-viz.Rmd:47:**TODO: ALR - examples, use ##C layout, & theme**
    ## ../04-viz.Rmd:73:**TODO: links, fill, grab from https://ropensci.org/packages/ under vis**
    ## ../08-research.Rmd:3:**TODO: zotero/mendeley**
    ## ../08-research.Rmd:4:**TODO: jbf hypo/bac**
    ## ../README/README.Rmd:11:grep -rni ../ --include \*.Rmd -e 'TODO:' || true;
    ## ../05-writing.Rmd:6:**TODO: (Eric)**
    ## ../05-writing.Rmd:47:**TODO: images**
    ## ../05-writing.Rmd:54:**TODO: link basic YAML Rmd**
    ## ../05-writing.Rmd:55:**TODO: add classic error not working because tabs instead of spaces**
    ## ../05-writing.Rmd:77:**TODO: example image of this** 
    ## ../98-etc.Rmd:3:**TODO: fill**
    ## ../03-analysis.Rmd:5:**TODO: ALR basic resources, and grab from slides**
    ## ../03-analysis.Rmd:6:**TODO: list columns**
    ## ../03-analysis.Rmd:84:**TODO: more examples**
    ## ../03-analysis.Rmd:126:**TODO: ALR link to ee best practices, ee developers docs, your repo of scripts**
    ## ../03-analysis.Rmd:131:**TODO: add model summary tables, fake data**
    ## ../03-analysis.Rmd:135:**TODO: organize into spatial/ plotting/ helper/ etc**

### aes

  - coool <https://bookdown.org/yihui/bookdown/custom-blocks.html>
  - spell check

### content

#### general/misc

  - which license - no derivatives (see geocompr)
  - other resources are first class

#### slides

  - include PDF version with pagedown

#### navbar

  - pdf/epub download doesnt exist - ci fix?
  - add rmd download?

#### lab

  - lab meeting presentations

#### research

  - developing a question
  - a-priori hypotheses
  - multiple competing hypotheses
  - Visualizing your predictions
  - bacon popper

#### misc

  - style guide
  - Supporting the project, eg cite it, contributing

#### new content

  - ~~Makefiles, also eg snakemake etc etc~~ targets
  - bibtex, csl files
  - gitlab ci/cd
  - ask jbf/kak things we’ve learned
  - general data things: no spaces in column names, no weird characters
  - reshaping melt/dcast with data.table
  - lapply rbindlist
  - parse out functions, why functions
  - basic roxygen
  - basic shiny
  - bash?
  - add ifd to sharing
  - landscapemetrics
  - wg shiny?

#### other resources

  - bookdown, rmarkdown sites
  - data.table wiki / site
  - efficient R
  - advanced R
  - geocompr
  - <https://vickysteeves.gitlab.io/repro-papers/prereq.html#gitlab>
