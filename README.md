# Case study: model on over-dispersion, and zero-inflated microbiome count data

Many microbiome studies apply statistical models to explore the association between microbiota and environmental variables. However, microbiome count data is typically over-dispersed and zero excessive, failing to meet assumptions of traditional mathematical algorithms, such as the linear regression and Poisson model. Consequently, insisting on conventional models with ignorance of over-dispersion and zero inflation in data distribution will increase type I or II errors.

Fortunately, statisticians have developed powerful "weapons", robust models specializing in over-dispersion and zero-inflated data, releasing microbiome researchers from the bottleneck. A few R packages are accessible to implement such advanced models.

This repository aims to establish an R pipeline to build models to fit microbiome abundance data with over-dispersion and zero inflation. This repository is public and provides practical information to microbiome researchers.

I made use of the state-of-the-art models and R modules introduced by Drs. Xia and Sun in their Book, Statistical analysis of microbiome with R (2018). I demonstrate an entire R pipeline in a case study context, from data processing to model fitting to coefficient interpretation, with the real-world data set provided by the NIH Human Microbiome Project.
