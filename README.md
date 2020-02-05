# EstSimLex-999

Authors: Claudia Kittask and Eduard Barbu


EstSimLex-999 is a data set for evaluation of models of similarity for Estonian Language. This data set contains 999 human annotated Estonian word pairs. This data set is translation of SimLex-999 [1]. 

## Download the Data Set

Link to EstSimLex-999 and results can be found [here](https://docs.google.com/spreadsheets/d/12IWabZzPIn0QvetZJvxAshZPX_g0fhoLh1g6OYYSZ0E/edit#gid=0). 

All design details are outlined in the following paper. Please cite it if you use EstSimLex-999. 
<br>
[Is Similarity Visually Grounded? Computational Model of Similarity for the Estonian language](https://www.aclweb.org/anthology/R19-1064/) 2019. Claudia Kittask and Eduard Barbu

@inproceedings{kittask-barbu-2019-similarity,<br>
    title = "Is Similarity Visually Grounded? Computational Model of Similarity for the {E}stonian language",<br>
    author = "Kittask, Claudia  and <br>
      Barbu, Eduard", <br>
    booktitle = "Proceedings of the International Conference on Recent Advances in Natural Language Processing (RANLP 2019)",<br>
    month = sep,<br>
    year = "2019",<br>
    address = "Varna, Bulgaria",<br>
    publisher = "INCOMA Ltd.",<br>
    url = "https://www.aclweb.org/anthology/R19-1064",<br>
    doi = "10.26615/978-954-452-056-4_064",<br>
    pages = "541--549",<br>
    abstract = "Researchers in Computational Linguistics build models of similarity and test them against human judgments. Although there are many empirical studies of the computational models of similarity for the English language, the similarity for other languages is less explored. In this study we are chiefly interested in two aspects. In the first place we want to know how much of the human similarity is grounded in the visual perception. To answer this question two neural computer vision models are used and their correlation with the human derived similarity scores is computed. In the second place we investigate if language influences the similarity computation. To this purpose diverse computational models trained on Estonian resources are evaluated against human judgments",
}<br>

Original data set can be downloaded [here](https://fh295.github.io/simlex.html). 

## Code 

This repository contains all the scripts used for evalaution of different computational models of similarity. All the used resources are cited inside the script files and are downloadable with the exception of Estonian Wikipedia page and category taxonomy, which can be browsed online in [MultiWiBi website](http://wibitaxonomy.org/).

## State-of-the-Art 

The [EA's CBOW word embeddings](http://datadoi.ut.ee/handle/33/91) trained on [etTenTen: Corpus of the Estonian Web](https://doi.org/10.15155/1-00-0000-0000-0000-0012el) achieved a Spearman Correlation of **0.47** on EstSimLex-999 and **0.42** on SimLex-999 data set. 

Estonian WordNet 2.2 path similarity measure achieved a Spearman Correlation of **0.52** on EstSimLex-999 and **0.47** on SimLex-999 data set. 

ResNet-18 achieved Spearman Correlation of **0.38** on both data sets. 

<br>
@inproceedings{kittask-barbu-2019-similarity,
    title = "Is Similarity Visually Grounded? Computational Model of Similarity for the {E}stonian language",
    author = "Kittask, Claudia  and
      Barbu, Eduard",
    booktitle = "Proceedings of the International Conference on Recent Advances in Natural Language Processing (RANLP 2019)",
    month = sep,
    year = "2019",
    address = "Varna, Bulgaria",
    publisher = "INCOMA Ltd.",
    url = "https://www.aclweb.org/anthology/R19-1064",
    doi = "10.26615/978-954-452-056-4_064",
    pages = "541--549",
    abstract = "Researchers in Computational Linguistics build models of similarity and test them against human judgments. Although there are many empirical studies of the computational models of similarity for the English language, the similarity for other languages is less explored. In this study we are chiefly interested in two aspects. In the first place we want to know how much of the human similarity is grounded in the visual perception. To answer this question two neural computer vision models are used and their correlation with the human derived similarity scores is computed. In the second place we investigate if language influences the similarity computation. To this purpose diverse computational models trained on Estonian resources are evaluated against human judgments",
}
<br>
<br>
<br>
<br>

[1] SimLex-999: Evaluating Semantic Models with (Genuine) Similarity Estimation. 2014. Felix Hill, Roi Reichart and Anna Korhonen. Computational Linguistics. 2015

