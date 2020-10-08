---
layout: post
title:  CAD in AR Smartphone
image:  /assets/images/blog/AR_harvester.png 
author: João
resume: Android app
---

This project intends to display a CAD model in a smartphone with Augmented Reality technology. 

The industry seeks new technologies and tools to achieve efficient solutions. When prototyping large and complex CAD models, it is essential that the design communication may be done most flexibly and effectively, allowing to the different stockholders (e.g. designers, engineers, customers, professional users) with different backgrounds remain engaged. 

Augmented Reality is becoming available to everyone since a smartphone is a common gadget in our pockets. Using this so well-known tool in complex environments, as virtual prototyping, may facilitate the design communication and enlarge model reviewing. In the end, improved products may be achieved.





<!--The model was provided in SolidWorks format file. For convenience, it was converted to [SpaceClaim CAD software](http://www.spaceclaim.com/en/default.aspx) from Ansys. 




The model contains more than 500 bodies modelled on their real size. Some dynamics simulations were performed with [AGX Momentum](https://www.algoryx.se/momentum/), allowing to export the model as a .fbx file. 

[Unity](https://unity.com/) is a game engine platform, frequently used for professional gaming development.  Due to its flexibility of embodying other software tools, it has been performing an important role in the industry as well, allowing to develop virtual environments to simulate prototypes or hypothetical real scenarios with human participation. -->

The CAD model used is the [Forest Master Turbo Harvester](http://usewood.fi/en/forest-master-turbo-harvester/) by Usewood Oy.  This project was set up with [Vuforia engine](https://www.ptc.com/en/products/augmented-reality/vuforia?cl1=AR_Vuforia_General_Google_CLC-cpc-ARBrandedxxxVuforiaUKNordics-38010&cmsrc=Google&cid=7015A000001oRiBQAU&elqCampaignId=13184&gclid=EAIaIQobChMI373k_t-m6QIVyIeyCh2Hpg17EAAYASAAEgLiIvD_BwE) from PTC. It was selected as an image ([Vuforia ThinkMark](https://github.com/joaoadpereira/Harvester_CAD-AR_Smartphone/blob/master/Vuforia_AR/Assets/Editor/Vuforia/ImageTargetTextures/thingmark/IMG_20190413_124844_scaled.jpg)) to perform as a target. This one, when recognized with a video camera, disposes of the harvester model (imported from SpaceClaim) with the same perspective view. 

 <!--Vuforia is a platform to develop Augmented Reality applications, with a high applicability range in the industry.-->





Check the results of the project in this video: 




<p  class="img-container" align="center">
<iframe width="840" height="472.5" src="https://www.youtube.com/embed/UnIzklv86Jo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<p>



The CAD model disposed on Spaceclaim can be seen in the next image: 



<p  class="img-container" align="center">
<img src="/assets/images/blog/harvester_CAD.png" alt="Harvester CAD" title="tHarvester CAD" height="400">
<p>





The Unity scene was then built for the Android platform, generating an apk. file to be installed in an Android smartphone. You can see the project configuration in the next image:


<p  class="img-container" align="center">
<img src="/assets/images/blog/harvester_project_ar.png" height="450"> 
</p>


With the use of a smartphone, the user may obtain the harvester model when pointing the camera to the image target. When moving it, the perspective of the model also changes. This project shows the process of converting industrial CAD models to Augmented Reality in a smartphone, using Unity and Vuforia engines. A similar process may be done with other complex CAD models and include dynamic simulation and human interaction. 