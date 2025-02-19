---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /portfolio
---

{% include base_path %}

For now, the information here will largely be taken from the Github repositories for these projects, which are [publicly available](https://github.com/Ege-Cakar?tab=repositories). I will also be adding more information on the research I've done outside of projects soon!



## **Eco-Civilization MDP: A Multi-Agent Environment for Sustainable Growth**



**[Eco-Civilization MDP](https://github.com/Ege-Cakar/Eco-Civilization-MDP)** is a reinforcement learning project that adapts the *Civilization* game to explore sustainable development strategies. Utilizing **Multi-Agent Proximal Policy Optimization (MAPPO)**, the project trains AI agents to balance economic growth with environmental responsibility. The modified game introduces **environmental penalties**, challenging agents to optimize strategies that mitigate climate impact while expanding their civilizations. With the work, our aim is to use reinforcement learning for finding strategies for enabling countries to stay competitive economically while taking environmentally conscious actions. 



## FocusCaption: Image Captioning Utilizing Saliency Models 

[This project](https://github.com/Ege-Cakar/FocusCaption) aims to implement an image captioning method that  utilizes 2 CNNs in parallel with a saliency prediction model to extract  extra information from where "should be focused" in an image. For this  implementation, the saliency model being utilized is [TranSalNet](https://github.com/LJOVO/TranSalNet/tree/master). After figuring out the location that should be focused on, the portion  is cut out and fed into an identical CNN, and at the end, the  information from the full image and the focused portion is combined and  fed into a decoder. 