---
layout: post
title:  "TF Image Segmentation on Landscape Paintings from Various Art Movements"
author: camelia
ptheme: paint
categories: [ Tensorflow, DeepLab, Lambda Layer, Image Segmentation, Confidence heatmap, webscraping, MongoDB, Computer Vision ]
image: assets/images/thumbnail_landscapes.jpeg
---



In this mini-project we use a pretrained DEEPLAB model with Tensorflow to segment landscape paintings from several Art Movements, automatically highlighting the spatial arrangement of vegetation, water bodies (sea, lake, river), boat, built environment, persons, animals painted in the composition.

Note 1. The paintings are webscraped from WikiArt and we store their metadata in MongoDB Atlas, temporarily for this demo.

Note 2: We use the model pretrained on ADE20K dataset, which includes classes of interest for this topic.


Results:   

Image segmentation for a landscape painting from Luminism:
![]({{ site.baseurl }}/assets/images/landscape1.png) 

<br>
Image segmentation for a landscape painting from Neoclassicism:
![]({{ site.baseurl }}/assets/images/landscape2.png) 

<br>
Image segmentation for a landscape painting from Northern Renaissance:
![]({{ site.baseurl }}/assets/images/landscape3.png) 

<br>
Image segmentation for a landscape painting from Romanticism:
![]({{ site.baseurl }}/assets/images/landscape4.png) 

<br>
Image segmentation for a landscape painting from Impressionism:
![]({{ site.baseurl }}/assets/images/landscape5.png) 




[Notebook in Github](https://github.com/camelia-c/techfolio/blob/main/tf_image_segmentation_wikiart/TF_Image_segmentaton_Landscape_Paintings.ipynb){:target="_blank"}

[Notebook in Nbviewer](https://nbviewer.jupyter.org/github/camelia-c/techfolio/blob/main/tf_image_segmentation_wikiart/TF_Image_segmentaton_Landscape_Paintings.ipynb){:target="_blank"}


