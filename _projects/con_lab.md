---
layout: page
title: Controls Optimization and Networks Lab
description: my work at Controls Optimization and Networks Lab at UT Dallas
img: assets/img/publication_preview/risk-bounded.gif
importance: 2
category: research
---

<div>
  <iframe width="800" height="500" src="https://www.youtube.com/embed/YyquJ1Hh-6A" title="Risk Bounded Nonlinear Robot Motion Planning With Integrated Perception &amp; Control" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<div class="caption">
    As part of UT Dallas Controls Optimization and Networks Lab (CON lab), I have been working on using different simulation environments like Airsim (Aerial Robotics and Simulation) and Carla for developing and simulating control algorithms on autonomous Cars and drones in a high fidelity environment.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/projects/con_lab/carla.png" title="Airsim " class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    CARLA is an urban driving simulator developed for autonomous driving research. We are using it to simulate uncertainty propagation in risk based motion planning. We implement perception uncertainties into planning by using a non linear model predictive control for steering law, camera sensor model and an unscented Kalman filter for state estimation. Carla was used as it provided the basic framework to build our simulation on top.
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/projects/con_lab/airsim.jpeg" title="Carla" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Airsim is specifically being used for drones since it provides a steppable clock and both software and hardware in the loop features.
    I developed a cascaded LQR controller that provided low level controls for the drone which could then be used by the lab for simulating various control methods. 
    Airsim, including this controller, is then being used for simulating a data driven distributionally robust trust based consensus model on a multi drone setup hovering together in a given formation as shown in the image.
</div>

Publications:

[1] [Venkatraman Renganathan, Sleiman Safaoui, Aadi M. Kothari, Benjamin Gravell, Iman Shames, and Tyler Summers. “Risk bounded nonlinear robot motion planning with integrated perception & control”. Artificial Intelligence Journal by Elsevier.](https://www.sciencedirect.com/science/article/pii/S0004370222001527)

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-V1HSZE1Y7M"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-V1HSZE1Y7M');
</script>