# An Automatic Essay Scoring Framework for Portuguese Essays


In this first version, the framework is composed by the resources: dataset, discourse marker list, and biased lexicon list.

## Dataset


The dataset is composed by 1840 essays distributed among 95 topics. We crawled the essays from the Essays database of the [UOL Educação web portal](https://educacao.uol.com.br/bancoderedacoes). Each month, the UOL Educação release a topic, and students can send by e-mail an essay related to the topic. Then, an anonymous human evaluator assesses approximately 20 essays to publish. The essays are evaluated according to the five aspects of the  Exame Nacional do Ensino Médio (ENEM), which is an exam that millions of Brazilians high school students enroll each year. The official evalutor's manual can be found in the following [link](http://download.inep.gov.br/educacao_basica/enem/guia_participante/2018/manual_de_redacao_do_enem_2018.pdf).

The dataset tarball contains 95 directories, each one is named after its respective topic. Each directory contains two subdirectories and two files. The two subdirectories contain the essays, one subdirectory has the XML version of essays and another directory has the HTML version of the essay. The two files are the HTML and XML of the prompt about the released topic. There is another README in the tarball file that details the XML strutucture of the essays and the prompts.

Please report any issue in the dataset.

## Discourse Marker List

Discourse markers are linguistic units that establish connections between sentences to build coherent and knit discourse. Then, we assemble a list using a Portuguese grammar 
[1] that list the main connectors employed for this purpose.

Please report any issue in the list.

# References

[1] Clélia Jubran and Ingedore Koch. 2006. Gramática do português culto falado no Brasil: construção do texto falado, volume 1. UNICAMP.

# Please Cite

If you are going to use the dataset and the discourse markers list, then you should cite the following paper:

*A Multi-aspect Analysis of Automatic Essay Scoring for Brazilian Portuguese, Amorim, Evelin and Veloso, Adriano, Proceedings of the Student Research Workshop at the 15th Conference of the European Chapter of the Association for Computational Linguistics, p. 94--102, 2017.*

If you are going to use the biased lexicon list, then you should cite the following paper:

*Automated Essay Scoring in the Presence of Biased Ratings, Amorim, Evelin and Cançado, Marcia and Veloso, Adriano, Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1, p. 229--237, 2018.*


Thank you.
