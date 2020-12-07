---
layout: post
title:  "TF Triplet Net for Identifying Architectural Style of Buildings Facades"
author: camelia
ptheme: architecture
categories: [ Tensorflow, Triplet Net, ResNet50, Embeddings, similarity, Lambda Layer, Custom Callback, Custom Loss, TF Dataset, Annoy index, Computer Vision ]
image: assets/images/thumbnail_baroque2.jpg
---



In this mini-project we train a Tensorflow model to identify the architectural style of a church facade. Initially we include three styles :

- "CLASSIC" : Classic , Classical Revival , Neo-Classic
- "GOTHIC" : Gothic , Neo-Gothic
- "BAROQUE" : Baroque , Rococo, Baroque Revival

Moreover, we use only a few exemplars per class and perform few-shot learning via a Triplet Net.

Nearest neighbors for a Baroque test image:
![]({{ site.baseurl }}/assets/images/scr2_tn.png) 

<br>
Nearest neighbors for a Gothic test image:
![]({{ site.baseurl }}/assets/images/scr3_tn.png) 

<br>
Nearest neighbors for a Classic test image:
![]({{ site.baseurl }}/assets/images/scr4_tn.png) 

[Notebook](https://nbviewer.jupyter.org/github/camelia-c/techfolio/blob/main/tf_tripletnet_buildings_facades_styles/TF_Training_TripletNet_to_Identify_Architecture_Style.ipynb){:target="_blank"}

<!--
The notebook is shown below (please allow nbviewer time to load 18.5 MB) :
<p><iframe style="width:100%;" height="915" src="https://nbviewer.jupyter.org/github/camelia-c/techfolio/blob/main/tf_tripletnet_buildings_facades_styles/TF_Training_TripletNet_to_Identify_Architecture_Style.ipynb" frameborder="0" allowfullscreen></iframe></p>
-->
