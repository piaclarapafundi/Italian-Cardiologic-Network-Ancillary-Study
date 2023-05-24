# Italian-Cardiologic-Network-Ancillary-Study
Post-hoc power calculation

#' TO INSTALL THE PACKAGE
#' install.packages("pwr") 	  

#' TO LAOD THE PACKAGE
#' library(pwr)

#' @references
#'citation(package = "pwr")	  
#' Champely S (2020). _pwr: Basic Functions for Power Analysis_. R
#' package version 1.3-0, <https://CRAN.R-project.org/package=pwr>.
#'
#' Function

function <- pwr.t.test(n = 500, d = 0.2, sig.level = 0.05, power = NULL, type = "two.sample", alternative = "two.sided")

#' n = Number of observations (per sample)
#' d = Effect size (Cohen's d) - difference between the means divided by the pooled standard deviation
#' sig.level = Significance level (Type I error probability)
#' power = Power of the test (1 minus Type II error probability)
#' type = type of t test: "one.sample", "two.samples", or "paired"
#' alternative = character string specifying the alternative hypothesis, either "two.sided" (default), "greater" or "less"


#' Two-sample t test power calculation 

              n = 500
              d = 0.2
      sig.level = 0.05
          power = 0.8847885
    alternative = two.sided

#' NOTE: n is number in *each* group
