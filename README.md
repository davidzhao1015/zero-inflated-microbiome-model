# zero-inflated-microbiome-model

Differential abundance analysis and/ or association between taxa and environmental variables is the research interest of many researchers. However, microbiome abundance data often contains too many zeros, which may disturb assumptions of traditional mathematical algorithms, such as the Poisson model. In other words, insisting on traditional models with ignoring inflated zero issues in data may cause significant false positive or negative events. However, there is good news. Biostatisticians have developed powerful "weapons", the models specializing in zero-inflated data, releasing microbiome researchers from the bottleneck. 

This repository aims to establish a reproducible pipeline for robust models specialized in zero-inflated microbiome data. This repository is public. Hopefully, the information in the repository might be helpful not only to my research but also to peers in the microbiome research field.  

I made use of the state-fo-art models recommended by Drs. Xia and Sun in their Book, Statistical analysis of microbiome with R (2018). In addition, I used a real-world dataset, HMP2, as an instance. 
