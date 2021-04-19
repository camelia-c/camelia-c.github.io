---
layout: post
title:  "Natural Language Processing for Semantics of Multicultural Proverbs"
author: camelia
ptheme: traditions
categories: [ NLP, Spacy, AllenNLP, WordNet, BabelNet, Tensorflow, BERT, Node2Vec, SupWSD, Part-of-speech, NetworkX, SPARQL, RDF, Blazegraph ]
image: assets/images/thumbnail_proverbs.jpg
---




In this mini-project we perform Natural Language Processing on proverbs and aphorisms from a variety of cultures, being primarily interested in their semantic analysis.

In PART 1, we develop an elaborated Spacy pipeline with multiple custom components, which include:

- expanding contractions,
- negated verbs detection,
- word sense disambiguation (WSD) based on WordNet 3.1 using SupWSD, BlazeGraph and SPARQL over BabelNet ,
- semantic role labelling (SRL) using AllenNLP,
- coreference resolution of pronouns (COREF) using AllenNLP.

In PART 2, we start by performing analytics at part of speech level.
Then, we use various embeddings techniques (static vectors from Spacy, Node2Vec on WordNet, BERT embeddings on dynamic word contexts) and evaluate how well these capture the semantic similarity between the nouns in our dataset.
Finally, we train a Tensorflow model using BERT embeddings to classify a proverb as figurative (metaphoric) vs realistic.

Results:

![]({{ site.baseurl }}/assets/images/proverbs1.png) 



There are 2 notebooks that form this project:

- part 1:  

[Notebook in Github](https://github.com/camelia-c/techfolio/blob/main/spacy_tf_nlp_proverbs/NLP_Semantics_Multicultural_Proverbs_GCP_PART1.ipynb){:target="_blank"}

[Notebook in Nbviewer](https://nbviewer.jupyter.org/github/camelia-c/techfolio/blob/main/spacy_tf_nlp_proverbs/NLP_Semantics_Multicultural_Proverbs_GCP_PART1.ipynb){:target="_blank"}

- part 2:  

[Notebook in Github](https://github.com/camelia-c/techfolio/blob/main/spacy_tf_nlp_proverbs/NLP_Semantics_Multicultural_Proverbs_GCP_PART2.ipynb){:target="_blank"}

[Notebook in Nbviewer](https://nbviewer.jupyter.org/github/camelia-c/techfolio/blob/main/spacy_tf_nlp_proverbs/NLP_Semantics_Multicultural_Proverbs_GCP_PART2.ipynb){:target="_blank"}
