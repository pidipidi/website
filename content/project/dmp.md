+++
date = "2017-04-20T22:46:22-04:00"
title = "Dynamic Obstacle Avoidnace"
highlight = true
summary = "Dynamic Movement Primitives"
math = false
external_link = ""
image_preview = "projects/placing_goalchange.jpg"
tags = ["dynamic-movement-primitives"]

[header]
  caption = "Dynamic obstacle avoidance"
  image = "headers/dmp.png"

+++

Robots in a human environment need to be compliant. This compliance requires that a pre-planed movement can be adapted to an obstacle that may be moving or appearing unexpectedly. Here, we present a general framework for movement generation and mid-flight adaptation to obstacles. For robust motion generation, Ijspeert et al developed the dynamic movement primitives, which represent a demonstrated movement with a differential equation. This equation allows adding a perturbing force without sacrificing stability. We extend this framework such that arbitrary movements in end-effector space can be represented - which was not possible before. Furthermore, we include obstacle avoidance by adding to the equation of motion a repellent force - a gradient of a potential field centered around the obstacle. In addition, this article studies the effect of different potential fields and shows how to avoid obstacle-link collisions within this framework. We demonstrate the abilities of our framework in simulations and with an anthropoid robot arm.


Supervised Learning (Dynamic Movement Primitives)
Obstacle Avoidance by Potential Field Approach
7-DoF Redudant Manipulator
Null-Space Elbow Avoidance