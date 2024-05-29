---
title: Face Morpher
date: 2022-09-07
tags:
  - CV
---

Seamless affine transformation the facial features from one face to another.

<!--more-->
{{< video src="featured.mp4" controls="yes" >}}

Face Morpher seamlessly morphs the facial features from one face to another by stretching and squishing them to match. This is accomplished by identifying facial landmarks using dlib's 68-point landmark detector and creating triangles using the Delaunay triangulation algorithm. These triangles are then subjected to affine transformation, ensuring alignment with the features of the target face. A video can be generated using linear interpolation, where the transformation is applied iteratively. You can find the python implementation [here](https://github.com/mejhana/SurfaceRegistration/blob/main/icp_derivation.pdf)







