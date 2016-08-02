Datasets of Annotated Semantic Relationships
============================================

This repository contains a annotated datasets used for the task of semantic relationship extraction. It's divided in two main groups, Traditional Information Extraction, where each relationship is annotated with a type, and Open Information Extraction where different possible relationship are annotated, with no particular type specified.

If you know any more datasets please let me know or simple make a pull request.

-------

Traditional Information Extraction
-------
-------

###AImed 


**Dateset**: [aimed.tar.gz](datasets/aimed.tar.gz)

**Cite**: [Subsequence Kernels for Relation Extraction](erk-nips-05.pdf)

**Description**: It consists of 225 Medline abstracts, of which 200 are known to describe interactions between human proteins, while the other 25 do not refer to any interaction. There are 4084 protein references and around 1000 tagged interactions in this dataset.






###SemEval

**Dateset**: [SemEval2010_task8_all_data.tar.gz](datasets/SemEval2010_task8_all_data.tar.gz)

**Cite**: [SemEval-2010 Task 8: Multi-Way Classification of Semantic Relations Between Pairs of Nominals](papers/semeval.pdf)

**Description**: SemEval-2010 Task 8 as a multi-way classification task in which the label for each example must be chosen from the complete set of ten relations and the mapping from nouns to argument slots is not provided in advance. We also provide more data: 10,717 annotated examples, compared to 1,529 in SemEval-1 Task 4.




###ReRelEM

**Dateset**: [ReRelEM.tar.gz](datasets/ReRelEM.tar.gz)

**Cite**: [Relation detection between named entities: report of a shared task](papers/FreitasetalSEW2009.pdf)

**Description**: First evaluation contest (track) for Portuguese whose goal was to detect and classify relations betweennamed entities in running text, called ReRelEM. Given a collection annotated with named entities belonging to ten different semantic categories, we marked all relationships between them within each document. We used the following fourfold relationship classification: identity, included-in, located-in, and other (which was later on explicitly detailed into twenty different relations).

      
###Wikipedia

**Dateset**: [wikipedia_datav1.0.tar.gz](datasets/wikipedia_datav1.0.tar.gz)

**Cite**: [Integrating Probabilistic Extraction Models and Data Mining to Discover Relations and Patterns in Text](papers/culotta06integrating.pdf)

**Description**: We sampled 1127 paragraphs from 271 articles from the online encyclopedia Wikipedia and labeled a total of 4701 relation instances. In addition to a large set of person-to-person relations, we also included links between people and organizations, as well as biographical facts such as birthday and jobTitle. In all, there are 53 labels in the training data.


###Web

**Dateset**: [hlt-naacl08-data.txt](datasets/hlt-naacl08-data.txt)

**Cite**: [Learning to Extract Relations from the Web using Minimal Supervision](papers/bunescu-acl07.pdf)

**Description**: Corporate Acquisition Pairs and Person-Birthplace Pairs taken from the web. The corporate acquisition test set has a total of 995 instances, out of which 156 are positive. The person-birthplace test set has a total of 601 instances, and only 45 of them are positive.


----

Open Information Extraction
----
----



###ReVerb

**Dateset**: [reverb_emnlp2011_data.tar.gz](datasets/emnlp2011_data.tar.gz)

**Cite**: [Identifying Relations for Open Information Extraction](papers/Fader-emnlp11.pdf)

**Description**: 500 sentences sampled from the Web, using Yahoo’s random link service.


  
  
  
  
###ClausIE

**Dateset**: [ClausIE-datasets.tar.gz](datasets/ClausIE-datasets.tar.gz)

**Cite**: [ClausIE: Clause-Based Open Information Extraction](papers/delcorro13clausie.pdf)

**Description**: 


  
  
  
  
###EEffectiveness and Efficiency of Open Relation Extraction

**Dateset**: [emnlp13_ualberta_experiments_v2.zip](datasets/emnlp13_ualberta_experiments_v2.zip)

**Cite**: [Effectiveness and Efficiency of Open Relation Extraction](papers/Effectiveness_OIE.pdf)

**Description**: 
