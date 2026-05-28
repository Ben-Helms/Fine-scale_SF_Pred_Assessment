
# Package loading function for new devices 
packageLoad <-
  function(x) {
    for (i in 1:length(x)) {
      if (!x[i] %in% installed.packages()) {
        install.packages(x[i])
      }
      library(x[i], character.only = TRUE)
    }
  }

packages <- c("Boruta",
              "randomForest",
              "car",
              "ggplot2",
              "dplyr",
              "leaps",
              "glmnet",
              "caret",
              "dplyr"
)

packageLoad(packages)

