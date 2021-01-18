---
layout: post
title:  "TF Image Classification for Belle Epoque Posters"
author: camelia
ptheme: paint
categories: [ Tensorflow, ResNet50, declarative ML, custom Callbacks, Lambda Layer, Keras Tuner, tf.data, tf.feature_column, tabular data, Optunity, CatBoost, Image classification, OpenCV, Computer Vision ]
image: assets/images/thumbnail_posters.png
---


In this mini-project we train a Tensorflow model to perform multiclass classification on images of old posters, dating from the Belle Epoque period in France.  
The classifier is trained to predict if a given poster had a cultural focus (theater, exposition), promoted a touristic destination, or if it had a retail focus (product, store).   

The image set is gathered from various museums collections in France and target the late XIX century and early XX century.  

In the preprocessing stage we deduplicate images based on image hashing (fingerprinting) and we use OpenCV to remove bottom border when this contained museum -added metadata.  

For the model we use declarative ML (based on YAML config files) and several custom callbacks.  
In the end, we experiment with an ensemble of top best performing models, whose hyperparams are searched for automatically. 

Results:

![]({{ site.baseurl }}/assets/images/posters1.png) 



There are 2 notebooks that form this project:

- part 1:  

[Notebook in Github](https://github.com/camelia-c/techfolio/blob/main/tf_image_classif_old_posters/part1_TF_Image_Classification_BelleEpoque_Posters.ipynb){:target="_blank"}

[Notebook in Nbviewer](https://nbviewer.jupyter.org/github/camelia-c/techfolio/blob/main/tf_image_classif_old_posters/part1_TF_Image_Classification_BelleEpoque_Posters.ipynb){:target="_blank"}

- part 2:  

[Notebook in Github](https://github.com/camelia-c/techfolio/blob/main/tf_image_classif_old_posters/part2_TF_Image_Classification_BelleEpoque_Posters.ipynb){:target="_blank"}

[Notebook in Nbviewer](https://nbviewer.jupyter.org/github/camelia-c/techfolio/blob/main/tf_image_classif_old_posters/part2_TF_Image_Classification_BelleEpoque_Posters.ipynb){:target="_blank"}
