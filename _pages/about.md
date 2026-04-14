---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am Yuhuan Xie (Xavian) and I am currently working as a remote Research Assistant at the **University of Hong Kong (HKU)**. I received my Master of Science degree in Electrical and Electronic Engineering from HKU in 2025, and my Bachelor's degree in Communication Engineering from Harbin Engineering University.

I'm particularly interested in AI and generative technologies, including video generation, 3D reconstruction, Diffusion Models, and Gaussian Splatting. 

Feel free to reach out if you have interesting ideas to discuss!

### News
- **[Feb. 2026]** Our paper *"ObjectMorpher"* has been accepted by CVPR 2026!
- **[2025]** Our paper *"2D Instance Editing in 3D Space"* was accepted by ICCVW 2025!

### Publications

{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
