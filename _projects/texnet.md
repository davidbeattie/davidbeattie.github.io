---
layout: page
title: TexNet
description: A Predictive Model For Tactile Sensations Produced From Visual Stimuli
img: /assets/img/texnet.jpg
importance: 3
---

<script type="text/javascript">
 function showhide(id) {
    var e = document.getElementById(id);
    e.style.display = (e.style.display == 'block') ? 'none' : 'block';
 }
</script>
   
With [Rory Clark](https://twitter.com/rorydotgames), [Orestis Georgiou](https://www.orestisgeorgiou.com).


#### Git Repositories

##### TexNet: Image Texture Prediction Model

> TexNet is a machine learning model that enables the automatic creation of mid-air haptic feedback based on visual image textures. It operates by extracting statistical measures of the variance in pixel co-occurrences contained within different types of image texture. These measures are then fed into a machine learning model and are used to predict visual perceptual quantities of different texture dimensions for a given image. 

Images were used from open-source image texture database and were presented via Amazon's Mechanical Turk to have users visually assess the underlying textural qualities and provide ratings for them. Having determined a method through which visual perceptual judgements could be predicted, these values were than converted into a mid-air haptic sensation using a linear mapping. A user study was finally conducted to assess the accuracy of the output sensations.

___

##### Intensity Modulation from Image Displacement Maps

> This textures open-source project is part of an internal research project exploring the possibility of rendering varying surface textures using a UH device. This work currently enables the generation of haptic textures from images by modulating haptic sensation intensity via image displacement map greyscale values. From this information, the roughness and bumpiness of a texture can be effectively presented using ultrasonic mid-air haptics. In addition, both visual and haptic feedback are directly linked which ensures congruency for the user whilst exploring a visuo-haptic texture.


Code: <a class="github-button" href="https://github.com/ultraleap/TexNet-Image-Texture-Prediction-Model" data-size="large" aria-label="texnet_on_github">TexNet Github Repository</a> and <a class="github-button" href="https://github.com/ultraleap/ultraleap-labs/tree/master/HapticTextures" data-size="large" aria-label="unity_textures">Haptic Textures Unity Demo Project</a>

___

#### Conference Papers

##### Incorporating the Perception of Visual Roughness into the Design of Mid-Air Haptic Textures

> _How can we connect visual and haptic feedback to create more congruent stimuli and automate this to improve the design process?_

<i class="fa fa-sticky-note" aria-hidden="true"></i> <a href="javascript:showhide('texnet')">_Abstract_</a>
<div id="texnet" style="display:none;">
<p>  <div style="font-size:0.85em; text-align: justify;">Ultrasonic mid-air haptic feedback enables the tactile exploration of virtual objects in digital environments. However, an object’s shape and texture is perceived multimodally, commencing before tactile contact is made. Visual cues, such as the spatial distribution of surface elements, play a critical first step in forming an expectation of how a texture should feel. When rendering surface texture virtually, its verisimilitude is dependent on whether these visually inferred prior expectations are experienced during tactile exploration. To that end, our work proposes a method where the visual perception of roughness is integrated into the rendering algorithm of mid-air haptic texture feedback. We develop a machine learning model trained on crowd-sourced visual roughness ratings of texture images from the Penn Haptic Texture Toolkit (HaTT). We establish tactile roughness ratings for different mid-air haptic stimuli and match these ratings to our model’s output, creating an end-to-end automated visuo-haptic rendering algorithm. We validate our approach by conducting a user study to examine the utility of the mid-air haptic feedback. This work can be used to automatically create tactile virtual surfaces where the visual perception of texture roughness guides the design of mid-air haptic feedback.</div> </p>
</div>

<i class="fa fa-download fa-ld" aria-hidden="true"></i> PDF: <a class="link" href="{https://dl.acm.org/doi/10.1145/3385955.3407927}">Incorporating the Perception of Visual Roughness into the Design of Mid-Air Haptic Textures</a>