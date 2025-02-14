---
layout: post
title:  Visualize 3D models in Augmented Reality
image:  /assets/images/blog/arview3dmodel.png
author: João
resume: AR app
---

#### Mobile 3D model visualization

During my period at [GLARTEK](https://glartek.com/), one of the projects I was involved was to enable the visualization and interaction of 3D models in 2D and in Augmented Reality (AR) from a mobile device. 


The companie's mobile app allows the upload and save of different type of files in customers processes. The 3D models used where from the type of .glb/.gltf. It was used the library [model_viewer_plus](https://pub.dev/packages/model_viewer_plus) to load the 3D model and enable the interaction in 2D mode. The user had also the chance to open the 3D model in Augmented Reality mode, forwarding the app to the embebbed Unity plugin. Here, with the help of AR Foundation, the camera detects a surface to instantiate the 3D model in the real world.

##### Interactions available

The user could load the 3D model (uploaded from the web platform) in the mobile app. From here, with their fingers, it could rotate, scale up/down and play/stop the animation if the model has any. Similiarly, the user could do the same in AR mode: move the object on top of a real surficie, rotate and scale the object as also control the animation. The following 3 images shows the process of openning the 3D model (left image), visualize it in 2D mode (central image) and open it in AR mode (right image).


<p class="img-container" align="center">
   <img width="60%"  src="/assets/images/blog/mobile_view_3dmodel.png" alt="ar_model1" title="ar_model1" >
</p>

#### Save 3D model world position in HoloLens and open it from a mobile device

Other project I was involved was about instantiating 3D models from the mobile app in the same position and rotation saved from the HoloLens device. It was introduced the capabilities to HoloLens to retreive the customized position and rotation of the model in reference of a digital anchor (also positionated and saved with the help of Azure Spatial Anchors). 


My task was to implement a way to get the models referenced by that digital anchor and instantiate them in the same position, rotation and scale that where defined with the HoloLens. In the following images, you can see the 3D model positioned with the HoloLens (left image) and the same model in the same position opened in the mobile app (right image).


<p class="img-container" align="center">
   <img width="49%"  src="/assets/images/blog/hololens_3dmodel.png" alt="ar_model2" title="ar_model2" >
   <img width="49%" src="/assets/images/blog/mobile_3dmodel.png" alt="ar_model3" title="ar_model3" >
</p>


#### Change discountinued Azure Spatial Anchors system to Google Cloud Anchors

With the [retirement of the Azure Spatial Anchors](https://learn.microsoft.com/en-us/lifecycle/end-of-support/end-of-support-2024), I was in charge to change the AR system to [Google Cloud Anchors](https://developers.google.com/ar/develop/cloud-anchors). Thw work involved to adapt the product needs based on what Cloud Anchors could offer and make sure the same basic functions would keep working for the client. 


Project team members: 
<h6 class="text-light">  João Pereira, Rogério Junior, João Carreira </h6>