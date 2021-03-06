---
layout: post
title:  "TF Siamese Neural Network for Identifying Architectural Style of Buildings Facades"
author: camelia
ptheme: architecture
categories: [ Tensorflow, Siamese Net, ResNet50, Embeddings, similarity, Lambda Layer, Custom Callback, TF Dataset, Computer Vision ]
image: assets/images/thumbnail_baroque.jpg
---



In this mini-project we train a Tensorflow model to identify the architectural style of a church facade. Initially we include three styles :

- "CLASSIC" : Classic , Classical Revival , Neo-Classic
- "GOTHIC" : Gothic , Neo-Gothic
- "BAROQUE" : Baroque , Rococo, Baroque Revival

Moreover, we use only a few exemplars per class and perform few-shot learning via a Siamese Neural Network.

Results:   

Nearest neighbors for a Baroque test image:
![]({{ site.baseurl }}/assets/images/scr2_sn.png) 

<br>
Nearest neighbors for a Gothic test image:
![]({{ site.baseurl }}/assets/images/scr3_sn.png) 

<br>
Nearest neighbors for a Classic test image:
![]({{ site.baseurl }}/assets/images/scr4_sn.png) 

[Notebook in Github](https://github.com/camelia-c/techfolio/blob/main/tf_siamesenet_buildings_facades_styles/TF_Training_SiameseNet_to_Identify_Architecture_Style.ipynb){:target="_blank"}

[Notebook in Nbviewer](https://nbviewer.jupyter.org/github/camelia-c/techfolio/blob/main/tf_siamesenet_buildings_facades_styles/TF_Training_SiameseNet_to_Identify_Architecture_Style.ipynb){:target="_blank"}



<!-- The notebook is shown below (please allow nbviewer time to load 13.6 MB) :
<p><iframe style="width:100%;" height="915" src="https://nbviewer.jupyter.org/github/camelia-c/techfolio/blob/main/tf_siamesenet_buildings_facades_styles/TF_Training_SiameseNet_to_Identify_Architecture_Style.ipynb" frameborder="0" allowfullscreen></iframe></p>
-->
