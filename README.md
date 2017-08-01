## Learning Through Utility Optimization in Regression Tasks

This repository has all the code used in the experiments carried out in the paper *"Learning Through Utility Optimization in Regression Tasks"* [1].


This repository is organized as follows:

* **Code** folder - contains all the code for reproducing the experiments presented in the paper;
* **Figures** folder - contains all the figures and tables obtained from the experimental evaluation;
* **Data** folder - contains the 16 regression data sets used in the experiments carried out;


### Requirements

The experimental design was implemented in R language. Both code and data are in a format suitable for R environment.

In order to replicate these experiments you will need a working installation
  of R. Check [https://www.r-project.org/] if you need to download and install it.

In your R installation you also need to install the following additional R packages:

  - randomForest
  - e1071
  - performaceEstimation
  - UBL
  - uba


  All the above packages with the exception of uba, can be installed from CRAN Repository directly as any "normal" R package. Essentially you need to issue the following command within R:

```r
install.packages(c("randomForest", "e1071", "performanceEstimation", "UBL"))
```

The package uba needs to be installed from a tar.gz file that you
  can download from http://www.dcc.fc.up.pt/~rpribeiro/uba/.
  Download the tar.gz file into your folder and then issue:

```r
install.packages("uba_0.7.7.tar.gz",repos=NULL,dependencies=T)
```


To replicate the figures in this repository you will also need to install the package:

  - ggplot2

As with any R package, we only need to issue the following command:

```r
install.packages("ggplot2")
```

Check the other README files in each folder to see more detailed instructions on how to run the experiments.

*****

### References
[1] Branco, P. and Torgo, L. and Ribeiro R.P. and Frank E. and Pfahringer B. and Rau M. M. (2017) *"Learning Through Utility Optimization in Regression Tasks"* Data Science and Advanced Analytics (DSAA), 2017 IEEE International Conference on. IEEE, 2017. Tokyo, Japan *(to appear)*.

