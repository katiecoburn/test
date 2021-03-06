Estimating Weight-Function Models for Publication Bias in R
===========================================================

The package includes a function that estimates the Vevea and Hedges (1995) weight-function model in R. By specifying arguments, users can also estimate the modified model described in Vevea and Woods (2005), which may be more practical with small datasets. Users can also specify moderators to estimate a linear model. The package functionality allows users to easily extract the results of these analyses as R objects for other uses. In addition, the package includes a function to launch both models as a Shiny application. Although the Shiny application is also available online, this function allows users to launch it locally if they choose.

    install.packages("weightr")

There are two functions in this package. Call `weightfunct` to estimate the weight-function model. Call `shiny_weightr()` to launch the Shiny app locally.
