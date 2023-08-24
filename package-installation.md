---
layout: page
title: Package installation
nav_exclude: true
permalink: /resources/package-installation/
---

# Local package installation

To install the required R packages on your computer, run the following lines of code from your R console: 

```
# data science
install.packages("tidyverse")    # the tidyverse

# class-specific functions
install.packages("devtools")
devtools::install_github("Katsevich-Teaching/stat471")

# textbook
install.packages("ISLR2")        # ISLR (v2)

# plotting/presentation
install.packages('cowplot')      # side-by-side plots
install.packages('GGally')       # nice pairs plots
install.packages('ggrepel')      # repelling point labels
install.packages('kableExtra')   # for nice tables
install.packages('maps')         # for plotting maps in ggplot
install.packages('lubridate')    # working with dates
install.packages('pROC')         # for ROC curves
install.packages('scales')       # for adjusting ggplot scales
install.packages('ggcorrplot')   # for correlation plots
install.packages('janitor')      # helpful auxiliary functions for data cleaning
install.packages('styler')       # for styling code
install.packages('rmarkdown')    # for R Markdown
install.packages('markdown')     # for R Markdown
install.packages('bookdown')     # for R Markdown

# learning
install.packages('FNN')           # KNN
install.packages('gbm')           # boosting
install.packages('glmnet')        # penalized regression
install.packages('glmnetUtils')   # penalized regression with formulas
install.packages('randomForest')  # random forests
install.packages('rpart')         # classification and regression trees
install.packages('rpart.plot')    # plotting for decision trees
install.packages("keras")         # deep learning (R package)
keras::install_keras()            # deep learning (Python backend)
install.packages('jpeg')          # plot images
```
