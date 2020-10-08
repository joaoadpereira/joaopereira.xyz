---
layout: post
title:  Product design in AR
image:  /assets/images/blog/product_design.png 
author: João
resume: Hololens app
---

This AR app enables the user to review the product design. 

When developing a new product, design variants requires to be discussed with different stockholders (e.g. designers, engineers, customers, professional users). The discussion many times passes through evaluating different solutions and testing prototypes. 

##### Solution

On this Hololens app, it is reviewed 3 different CAD solutions of snowplough (figures below) to attach to a Harvester machine. Through an interactive interface menu, the user can navigate and enable design information (dynamic simulation, exploded view and real size view) about the different prototypes solutions. 


The user interface was set up with [Unity](https://unity.com/), [Mixed Reality Toolkit](https://github.com/microsoft/MixedRealityToolkit-Unity) (MRTK) and deployed to [Microsoft HoloLens](https://www.microsoft.com/en-us/hololens).


Watch a video demo of the experience:

<p  class="img-container" align="center">
<iframe width="840" height="472.5" src="https://www.youtube.com/embed/YlznWJ-maCg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<p>
<!--<p align="center">
<img src="https://github.com/joaoadpereira/AR-Industry-Applications/blob/master/images/design1_CAD.PNG" alt="Design 1" title="Design 1" height="150"></a> 
<img src="https://github.com/joaoadpereira/AR-Industry-Applications/blob/master/images/design2_CAD.PNG" alt="Design 2" title="Design 2" height="150"></a> 
<img src="https://github.com/joaoadpereira/AR-Industry-Applications/blob/master/images/design3_CAD.PNG" alt="Design 3" title="Design 3" height="150"></a> 
</p>-->

The snowploughs were designed in CAD software. Here are the different design solutions:  

<p class="img-container" align="center">
<img src="/assets/images/blog/snowpiles.png" alt="snowploughs" title="snowploughs" height="200">
<p>


The virtual interface interaction was designed with MRTK. Each button enables and disables different hologram content. At the same time, the user can inspect these big models at their real size inside of a room or even outdoors.

This app shows how prototype review may be achieved with Augmented Reality, visualizing the different virtual model solutions and allowing their dynamic simulation, detailed information, exploded view and background context (model attached to the Harvester).