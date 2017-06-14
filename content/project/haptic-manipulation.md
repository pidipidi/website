+++
title = "Haptic manipulation"
math = false
tags = ["haptic-manipulation"]
image_preview = "publications/iros_2015_haptic.png"
summary = "Tactile sensing, mapping, planning, and manipulation"
date = "2017-04-19T23:19:50-04:00"
highlight = true
external_link = ""

[header]
  caption = "" #"Tactile sensing, mapping, planning, and manipulation"
  image = "" #"projects/haptic_manipulation.png"

+++

{{< youtube ic_M-NldXec >}}
{{< youtube WHHv3womkYs >}}
{{< youtube Gjy-MDEbZUU >}}


We consider the problem of enabling a robot to efficiently obtain a dense haptic map of its visible surroundings using the complementary properties of vision and tactile sensing. Our approach assumes that visible surfaces that look similar to one another are likely to have similar haptic properties. We present an iterative algorithm that enables a robot to infer dense haptic labels across visible surfaces when given a color-plus-depth (RGB-D) image along with a sequence of sparse haptic labels representative of what could be obtained via tactile sensing. Our method uses a color-based similarity measure and connected components on color and depth data. We evaluated our method using several publicly available RGB-D image datasets with indoor cluttered scenes pertinent to robot manipulation. We analyzed the effects of algorithm parameters and environment variation, specifically the level of clutter and the type of setting, like a shelf, table top, or sink area. In these trials, the visible surface for each object consisted of an average of 8602 pixels, and we provided the algorithm with a sequence of haptically-labeled pixels up to a maximum of 40 times the number of objects in the image. On average, our algorithm correctly assigned haptic labels to 76.02% of all of the
object pixels in the image given this full sequence of labels. We also performed experiments with the humanoid robot DARCI reaching in a cluttered foliage environment while using our algorithm to create a haptic map. Doing so enabled the robot to reach goal locations using a single plan after a single greedy reach, while our previous tactile-only mapping method required 5 or more plans to reach each goal.