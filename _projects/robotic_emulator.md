---
layout: page
title: Robotic Emulator
description: robotic emulator for offshore wind turbine testing.
img: assets/projects/robotic_emulator/4dof_hardware.jpg
importance: 2
category: work
giscus_comments: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/projects/robotic_emulator/4dof_hardware.jpg" title="football_punting" class="img-fluid rounded z-depth-1" %}
    </div>
    <div>
        <iframe width="500" height="281" src="https://www.youtube.com/embed/F9IoTwHuRnw" title="Wind Tunnel testing of the robotic emulator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
</div>



As part of our senior capstone project, my team built a prototype of a floating platform for emulating the motion of floating offshore wind turbines, that can be fully controlled for prescribed motion, and is being tested with a model turbine at the UTD wind tunnel.
To emulate the motion profile and force envelope of a FOWT, we use a scaled-down version of a wind turbine and place it on a platform, capable of motion 3 degrees of freedom.
Aeroelastic scaling documents and OpenFast (whole turbine simulation tool) were used to define motion constraints in roll, pitch, yaw, and surge, sway and heave direction to optimize our robotic emulator for the given task.
As part of our preliminary design analysis, we considered a 6DOF Stewart platform that uses 6 linear actuators to perform the required motion. A Simulink model was set up for performing basic controls analysis and we plan on using the inbuilt Simulink optimization tool. Upon further analysis, it was determined that primarily independently controlling 3DOF (Heve, Roll, and Pitch) is our focus, and thus necessary modifications were made. 
Our project sponsor is Dr Valerio Iungo, a professor at UT Dallas and principal researcher at the Windflux lab.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/projects/robotic_emulator/controls_diagram.jpeg" title="football_punting" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-V1HSZE1Y7M"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-V1HSZE1Y7M');
</script>