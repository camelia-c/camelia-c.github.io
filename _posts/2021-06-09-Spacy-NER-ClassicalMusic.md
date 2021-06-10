---
layout: post
title:  Classical Music NER with Spacy v3"
author: camelia
ptheme: music
categories: [ NLP, Spacy, NER, Word2Vec, Gensim, Doccano, GCP]
image: assets/images/thumbnail_ner.png
---

In this mini-project we train a Spacy Named Entity Recognition model on titles of classical music compositions in French.  
We are interested to identify the work type, instruments, tonality (key), tempo, given that the titles may contain abbeviations thereof.  
We need to develop a custom Spacy tokenizer due to the spellings of the titles, and, in one of the experiments, we train Word2Vec embeddings with Gensim.



Results:

![]({{ site.baseurl }}/assets/images/ner1.png) 




[Notebook in Github](https://github.com/camelia-c/techfolio/blob/main/spacy_ner_classicalmusic/ClassicalMusic_NER_Spacy.ipynb){:target="_blank"}


[Notebook in Nbviewer](https://nbviewer.jupyter.org/github/camelia-c/techfolio/blob/main/spacy_ner_classicalmusic/ClassicalMusic_NER_Spacy.ipynb){:target="_blank"}


