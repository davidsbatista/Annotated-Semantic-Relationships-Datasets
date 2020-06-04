Datasets of Annotated Semantic Relationships
============================================

This repository contains annotated datasets which can be used to train supervised models for the task of semantic relationship extraction. If you know any more datasets, and want to contribute, please, notify me or submit a PR.

It's divided in 3 groups:

[__Traditional Information Extraction__](#tie): relationships are manually annotated, and belongs to pre-determined type, i.e. a closed number of classes.

[__Open Information Extraction__](#oie): relationships are manually annotated, but don't have any specific type.

[__Distantly Supervised__](#ds): relationships are annotated by appying some [Distant Supervision](https://www.aclweb.org/anthology/P09-1113) technique and are pre-determined.

<br><br>

| Dataset                           | Nr. Classes   | Language | Cite | 
| --------------------------------- |:-------------:| :-------:|---------|
| [DBpediaRelations-PT-0.2.txt.bz2](datasets/DBpediaRelations-PT-0.2.txt.bz2)| 10 | Portuguese |[Exploring DBpedia and Wikipedia for Portuguese Semantic Relationship Extraction](papers/minwise-linguamtica-13.pdf)|
| [aimed.tar.gz](datasets/aimed.tar.gz)| 2 | English | [Subsequence Kernels for Relation Extraction](erk-nips-05.pdf)|
| [SemEval2007-Task4.tar.gz](datasets/SemEval2007-Task4.tar.gz) | 7 | English | [SemEval-2007 Task 04: Classification of Semantic Relations between Nominals](papers/semeval2007.pdf)
| [SemEval2010_task8_all_data.tar.gz](datasets/SemEval2010_task8_all_data.tar.gz) | 10 / 19 (directional) | English | [SemEval-2010 Task 8: Multi-Way Classification of Semantic Relations Between Pairs of Nominals](papers/semeval.pdf)
| [ReRelEM.tar.gz](datasets/ReRelEM.tar.gz) | 4 | Portuguese | [Relation detection between named entities: report of a shared task](papers/FreitasetalSEW2009.pdf) |
| [wikipedia_datav1.0.tar.gz](datasets/wikipedia_datav1.0.tar.gz) | 53 | English | [Integrating Probabilistic Extraction Models and Data Mining to Discover Relations and Patterns in Text](papers/culotta06integrating.pdf) |
| [hlt-naacl08-data.txt](datasets/hlt-naacl08-data.txt) | 2 | English | [Learning to Extract Relations from the Web using Minimal Supervision](papers/bunescu-acl07.pdf) |
| [BioNLP.tar.gz](datasets/BioNLP.tar.gz) (2011) | 2 | English | [Overview of BioNLP Shared Task 2011](papers/W11-1801.pdf) |
| [ADE-Corpus-V2.zip](datasets/ADE-Corpus-V2.zip) | 2 | English | [Development of a benchmark corpus to support the automatic extraction of drug-related adverse effects from medical case reports](papers/ADE-V2.pdf) |
| [kbp37-master.zip](datasets/kbp37-master.zip) | 37 directional | English | [Relation Classification via Recurrent Neural Network](papers/KBP37.pdf) |

<br><br>

| Dataset                           | Nr. Classes   | Language | Cite | 
| --------------------------------- |:-------------:| :-------:|---------|
| [reverb_emnlp2011_data.tar.gz](datasets/emnlp2011_data.tar.gz) | Open | English | [Identifying Relations for Open Information Extraction](papers/Fader-emnlp11.pdf) |
| [ClausIE-datasets.tar.gz](datasets/ClausIE-datasets.tar.gz) | Open | English | [ClausIE: Clause-Based Open Information Extraction](papers/delcorro13clausie.pdf) |
| [emnlp13_ualberta_experiments_v2.zip](datasets/emnlp13_ualberta_experiments_v2.zip) | Open | English | [Effectiveness and Efficiency of Open Relation Extraction](papers/Effectiveness_OIE.pdf) |
| [DataSet-IJCNLP2011.tar.gz](datasets/DataSet-IJCNLP2011.tar.gz) | Open | English | [Extracting Relation descriptors with Conditional Random Fields](papers/rel_descriptors_with_crf.pdf) |

<br><br>

| Dataset                           | Nr. Classes   | Language | Cite | 
| --------------------------------- |:-------------:| :-------:|---------|
| [http://iesl.cs.umass.edu/riedel/ecml/](http://iesl.cs.umass.edu/riedel/ecml/) | Distant | English | [Modeling Relations and Their Mentions without Labeled Text](papers/Ridel2010.pdf) |
| [https://github.com/google-research-datasets/relation-extraction-corpus](https://github.com/google-research-datasets/relation-extraction-corpus) | Distant | English | [https://research.googleblog.com/2013/04/50000-lessons-on-how-to-read-relation.html](https://research.googleblog.com/2013/04/50000-lessons-on-how-to-read-relation.html) |




<br><br>

<a name="tie"></a>
# Traditional Information Extraction

### DBpediaRelations-PT

**Dateset**: [DBpediaRelations-PT-0.2.txt.bz2](datasets/DBpediaRelations-PT-0.2.txt.bz2)

**Cite**: [Exploring DBpedia and Wikipedia for Portuguese Semantic Relationship Extraction](papers/minwise-linguamtica-13.pdf)

**Description**: A collections of sentences in Portuguese that express semantic relationships between pairs of entities extracted from
DBPedia. The sentences were collected by distant supervision, and were than manuall revised.

---

### AImed


**Dateset**: [aimed.tar.gz](datasets/aimed.tar.gz)

**Cite**: [Subsequence Kernels for Relation Extraction](erk-nips-05.pdf)

**Description**: It consists of 225 Medline abstracts, of which 200 are known to describe interactions between human proteins, while the other 25 do not refer to any interaction. There are 4084 protein references and around 1000 tagged interactions in this dataset.

---

### SemEval 2007

**Dateset**: [SemEval2007-Task4.tar.gz](datasets/SemEval2007-Task4.tar.gz)

**Cite**: [SemEval-2007 Task 04: Classification of Semantic Relations between Nominals](papers/semeval2007.pdf)

**Description**: Small data set, containing 7 relationship types and a total of 1,529 annotated examples.

---

### SemEval 2010

**Dateset**: [SemEval2010_task8_all_data.tar.gz](datasets/SemEval2010_task8_all_data.tar.gz)

**Cite**: [SemEval-2010 Task 8: Multi-Way Classification of Semantic Relations Between Pairs of Nominals](papers/semeval.pdf)

**Description**: SemEval-2010 Task 8 as a multi-way classification task in which the label for each example must be chosen from the complete set of ten relations and the mapping from nouns to argument slots is not provided in advance. We also provide more data: 10,717 annotated examples, compared to 1,529 in SemEval-1 Task 4.

---

### ReRelEM

**Dateset**: [ReRelEM.tar.gz](datasets/ReRelEM.tar.gz)

**Cite**: [Relation detection between named entities: report of a shared task](papers/FreitasetalSEW2009.pdf)

**Description**: First evaluation contest (track) for Portuguese whose goal was to detect and classify relations betweennamed entities in running text, called ReRelEM. Given a collection annotated with named entities belonging to ten different semantic categories, we marked all relationships between them within each document. We used the following fourfold relationship classification: identity, included-in, located-in, and other (which was later on explicitly detailed into twenty different relations).

---

### Wikipedia

**Dateset**: [wikipedia_datav1.0.tar.gz](datasets/wikipedia_datav1.0.tar.gz)

**Cite**: [Integrating Probabilistic Extraction Models and Data Mining to Discover Relations and Patterns in Text](papers/culotta06integrating.pdf)

**Description**: We sampled 1127 paragraphs from 271 articles from the online encyclopedia Wikipedia and labeled a total of 4701 relation instances. In addition to a large set of person-to-person relations, we also included links between people and organizations, as well as biographical facts such as birthday and jobTitle. In all, there are 53 labels in the training data.

---

### Web

**Dateset**: [hlt-naacl08-data.txt](datasets/hlt-naacl08-data.txt)

**Cite**: [Learning to Extract Relations from the Web using Minimal Supervision](papers/bunescu-acl07.pdf)

**Description**: Corporate Acquisition Pairs and Person-Birthplace Pairs taken from the web. The corporate acquisition test set has a total of 995 instances, out of which 156 are positive. The person-birthplace test set has a total of 601 instances, and only 45 of them are positive.

---

### BioNLP Shared Task

**Dateset**: [BioNLP.tar.gz](datasets/BioNLP.tar.gz)

**Cite**: [Overview of BioNLP Shared Task 2011](papers/W11-1801.pdf)

**Description**: The task involves the recognition of two binary part-of relations between entities: PROTEIN-COMPONENT and SUBUNITCOMPLEX. The task is motivated by specific challenges: the identification of the components of proteins in text is relevant e.g. to the recognition of Site arguments (cf. GE, EPI and ID tasks), and relations between proteins and their complexes relevant to any task involving them. REL setup is informed by recent semantic relation tasks (Hendrickx et al., 2010). The task data, consisting of new annotations for GE data, extends a previously introduced resource (Pyysalo et al., 2009; Ohta et al., 2010a).

---

### ADE-V2

**Dateset**: [ADE-Corpus-V2.zip](datasets/ADE-Corpus-V2.zip)

**Cite**: [Development of a benchmark corpus to support the automatic extraction of drug-related adverse effects from medical case reports](papers/ADE-V2.pdf)

**Description**: The work presented here aims at generating a systematically annotated corpus that can support the development and validation of methods for the automatic extraction of drug-related adverse effects from medical case reports. The documents are systematically double annotated in various rounds to ensure consistent annotations. The annotated documents are finally harmonized to generate representative consensus annotations. In order to demonstrate an example use case scenario, the corpus was employed to train and validate models for the classification of informative against the non-informative sentences. A Maximum Entropy classifier trained with simple features and evaluated by 10-fold cross-validation resulted in the F1 score of 0.70 indicating a potential useful application of the corpus. 

---

### KBP-37

**Dateset**: [kbp37-master.zip.zip](datasets/kbp37-master.zip)

**Cite**: [Relation Classification via Recurrent Neural Network](papers/KBP37.pdf)

**Description**: This dataset is a revision of MIML-RE annotation dataset, provided by Gabor Angeli et al. (2014). They use both the 2010 and 2013 KBP official document collections, as well as a July 2013 dump of Wikipedia as the text corpus for annotation, 33811 sentences been annotated. To make the dataset more suitable for our task, we made several refinement: 

1. First, we add direction to the relation names, such that ‘per:employee of’ is splited into two relations ‘per:employee of(e1,e2)’ and ‘per:employee of(e2,e1)’ except for ‘no relation’. According to description of KBP task,3 we replace ‘org:parents’ with ‘org:subsidiaries’ and replace ‘org:member of’ with ‘org:member’ (by their reverse directions). This leads to 76 relations in the dataset.

2. Then, we statistic the frequency of each relation with two directions separately. And relations with low frequency are discarded so that both directions of each relation occur more than 100 times in the dataset. To better balance the dataset, 80% ‘no relation’ sentences are also randomly discarded.

3. After that, dataset are randomly shuffled and then sentences under each relation are all split into three groups, 70% for training, 10% for
development, 20% for test. Finally, we remove those sentences in the development and test set whose entity pairs and relation are appeared in a training sentence simultaneously. 


<br><br>






<a name="oie"></a>
# Open Information Extraction

### ReVerb

**Dateset**: [reverb_emnlp2011_data.tar.gz](datasets/emnlp2011_data.tar.gz)

**Cite**: [Identifying Relations for Open Information Extraction](papers/Fader-emnlp11.pdf)

**Description**: 500 sentences sampled from the Web, using Yahoo’s random link service.

---

### ClausIE

**Dateset**: [ClausIE-datasets.tar.gz](datasets/ClausIE-datasets.tar.gz)

**Cite**: [ClausIE: Clause-Based Open Information Extraction](papers/delcorro13clausie.pdf)

**Description**:

Three different datasets. First, the Reverb dataset consists of 500 sentences with manually labeled extractions. The sentences have been obtained via the random-link service of Yahoo and are generally very noisy. Second, 200 random sentences from Wikipedia pages. These sentences are shorter, simpler, and less noisy than those of the Reverb dataset. Since some Wikipedia articles are written by non-native speakers, however, the Wikipedia sentences do contain some incorrect grammatical constructions. Third, 200 random sentences from the New York Times collection these sentences are generally very clean but tend to be long and complex.

---

### Effectiveness and Efficiency of Open Relation Extraction

**Dateset**: [emnlp13_ualberta_experiments_v2.zip](datasets/emnlp13_ualberta_experiments_v2.zip)

**Cite**: [Effectiveness and Efficiency of Open Relation Extraction](papers/Effectiveness_OIE.pdf)

**Description**: WEB-500 is a commonly used dataset, developed for the TextRunner experiments (Banko and Etzioni, 2008). These sentences are often incomplete and grammatically unsound, representing the challenges of dealing with web text. NYT-500 represents the other end of the spectrum with formal, well written new stories from the New York Times Corpus (Sandhaus, 2008). PENN-100 contains sentences from the Penn Treebank recently used in an evaluation of the TreeKernel method (Xu et al., 2013). We manually annotated the relations for WEB-500 and NYT-500 and use the PENN-100 annotations provided by TreeKernel’s authors (Xu et al., 2013).

---

### Extracting Relation descriptors with Conditional Random Fields

**Dateset**: [DataSet-IJCNLP2011.tar.gz](datasets/DataSet-IJCNLP2011.tar.gz)

**Cite**: [Extracting Relation descriptors with Conditional Random Fields](papers/rel_descriptors_with_crf.pdf)

**Description**: New York Times data set contains 150 business articles from New York Times. The articles were crawled from the NYT website between November 2009 and January 2010. After sentence splitting and tokenization, we used the Stanford NER tagger (URL: http://nlp.stanford.edu/ner/index.shtml) to identify PER and ORG named entities from each sentence. For named entities that contain multiple tokens we concatenated them into a single token. We then took each pair of (PER, ORG) entities that occur in the same sentence as a single candidate relation instance, where the PER entity is treated as ARG-1 and the ORG entity is treated as ARG-2.

Wikipedia data was previously created by Aron Culotta et al.. Since the original data set did not contain the annotation information we need, we re-annotated it. Similarly, we performed sentence splitting, tokenization and NER tagging, and took pairs of (PER, PER) entities occurring in the same sentence as a candidate relation instance. We always treat the first PER entity as ARG-1 and the second PER entity as ARG-2.

<br><br>

<a name="ds"></a>
# Distant Supervision for Relation Extraction

### NYT dataset

**Dateset**: [http://iesl.cs.umass.edu/riedel/ecml/](http://iesl.cs.umass.edu/riedel/ecml/)

**Cite**: [Modeling Relations and Their Mentions without Labeled Text](papers/Ridel2010.pdf)

**Description**: The NYT dataset is a widely used dataset on distantly supervisied relation extraction task. This dataset was generated by aligning freebase relations with the New York Times (NYT) corpus, with sentences from the years 2005-2006 used as the training corpus and sentences from 2007 used as the testing corpus.

---

### Google's relation-extraction-corpus

**Dateset**: [https://github.com/google-research-datasets/relation-extraction-corpus](https://github.com/google-research-datasets/relation-extraction-corpus)

**Cite**: [https://research.googleblog.com/2013/04/50000-lessons-on-how-to-read-relation.html](https://research.googleblog.com/2013/04/50000-lessons-on-how-to-read-relation.html)

**Description**: [https://research.googleblog.com/2013/04/50000-lessons-on-how-to-read-relation.html](https://research.googleblog.com/2013/04/50000-lessons-on-how-to-read-relation.html)

