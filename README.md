# ChemistryRWorkbook

https://shiny.reed.edu/s/users/vestoj/chem/#section-intro-to-workbook

# How to use shiny.reed.edu to create and edit a website:

URL: shiny.reed.edu/r/ 

First create a folder labeled “ShinyApps”. Inside ShinyApps folder create a secondary folder labeled with the title that will be part of the URL (i.e. chem, chemistry, upperdivision, chemistry-reference). Inside URL folder create an RMD file labeled “index”.

The header for the document should look like (assuming creating a document similar to the R Workbook): 

```{r setup, include=FALSE}
#devtools::install_github("lionel-/redpen")
#devtools::install_github("dtkaplan/checkr")
library(tidyverse)
library(shiny)
library(devtools)
library(chemistr)
library(learnr)
library(checkr)
library(redpen)

knitr::opts_chunk$set(echo = FALSE)
tutorial_options(exercise.checker = checkr::check_for_learnr) 
```

Make sure to save the document. Then go ahead and publish it.

For possible issues that may arise when publishing or accessing the workbook see "Issues" tab and filter for closed issues.
