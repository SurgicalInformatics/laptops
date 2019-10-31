# R
https://www.stats.bris.ac.uk/R/

# R Tools
https://cran.r-project.org/bin/windows/Rtools/Rtools35.exe

# RStudio
https://download1.rstudio.org/desktop/windows/RStudio-1.2.5001.exe

# git
https://git-scm.com/download/win

# R packages

```{r}

healthyr_notebooks = c("tidyverse", "boot", "finalfit", "flexdashboard",
"gapminder", "here", "kableExtra", "knitr", "remotes",
"rmarkdown", "shiny", "survminer", "tinytex")
install.packages(healthyr_notebooks)

```

## Then Restart R

## to then run these two lines (same as before, copy-paste to the Console):

```{r}

remotes::install_github("thomasp85/patchwork")
tinytex::install_tinytex()

```
