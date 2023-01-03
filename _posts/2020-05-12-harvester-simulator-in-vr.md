---
layout: post
title:  Harvester simulator in VR
image:  /assets/images/blog/harvester_VR.png 
author: João
resume: Oculus Rift app
---


This project is a real-time simulator of a Harvester CAD model in a virtual forest. 

The CAD model used is the [Forest Master Turbo Harvester](http://usewood.fi/en/forest-master-turbo-harvester/) by Usewood Oy. The model was provided in SolidWorks format file. For convenience, it was converted to [SpaceClaim CAD software](http://www.spaceclaim.com/en/default.aspx) from Ansys. 

The model contains more than 500 bodies modelled on their real size. Some dynamics simulations were performed with [AGX Momentum](https://www.algoryx.se/momentum/), allowing to export the model as a .agx file. 

[Unity](https://unity.com/) is a game engine platform, frequently used for professional gaming development.  Due to its flexibility of embodying other software tools, it has been performing an important role in the industry as well, allowing to develop virtual environments to simulate prototypes or hypothetical real scenarios with human participation.  

[AGXUnity](https://github.com/Algoryx/AGXUnity) is a plugin that allows to run AGX Models in real-time simulator in Unity environment. 

Together with the Harvester CAD model, a virtual forest was designed to provide a context of the simulator. In the end, the user is able to drive the machine and interact with the boom as a real operator. For that, it uses the VR controllers from Oculus Rift. 

Whatch the video demo about the simulator: 
<p  class="img-container" align="center">
<iframe width="100%" src="https://www.youtube.com/embed/X0Z1mlTdyoM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<p>

<!--Know more about my master thesis work <a href="{{ //2019-06-25-master-thesis }}" >here</a>. 

<a href="{{ post.url | relative_url }}" class="btn btn-xs btn-primary">Read More</a>-->