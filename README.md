# EstSimLex-999

EstSimLex-999 is a data set for evaluation of models of similarity for Estonian Language. This data set contains 999 human annotated Estonian word pairs. This data set is translation of SimLex-999 [1]. 

## Download the Data Set

Link to EstSimLex-999 and results can be found [here](https://docs.google.com/spreadsheets/d/12IWabZzPIn0QvetZJvxAshZPX_g0fhoLh1g6OYYSZ0E/edit#gid=0). 

Original data set can be downloaded [here](https://fh295.github.io/simlex.html). 

## Code 

This repository contains all the scripts used for evalaution of different computational models of similarity. All the used resources are cited inside the script files and are downloadable with the exception of Estonian Wikipedia page and category taxonomy, which can be browsed online in [MultiWiBi website](http://wibitaxonomy.org/).

## State-of-the-Art 

The [EA's CBOW word embeddings](http://datadoi.ut.ee/handle/33/91) trained on [etTenTen: Corpus of the Estonian Web](https://doi.org/10.15155/1-00-0000-0000-0000-0012el) achieved a Spearman Correlation of **0.47** on EstSimLex-999 and **0.42** on SimLex-999 data set. 

Estonian WordNet 2.2 path similarity measure achieved a Spearman Correlation of **0.52** on EstSimLex-999 and **0.47** on SimLex-999 data set. 

ResNet-18 achieved Spearman Correlation of **0.38** on both data sets. 



[1] SimLex-999: Evaluating Semantic Models with (Genuine) Similarity Estimation. 2014. Felix Hill, Roi Reichart and Anna Korhonen. Computational Linguistics. 2015

