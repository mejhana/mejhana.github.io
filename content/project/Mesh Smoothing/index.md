---
title: Mesh Smoothing
date: 2022-08-28
tags:
  - Graphics
---

Implicit mesh smoothing using the Laplace-Beltrami operator.

<!--more-->

{{< video src="featured.mp4" controls="yes" >}}

Implicit Mesh Smoothing involves analyzing the curvature of each vertex of the mesh using the Laplace-Beltrami operator. We examine how much each vertex protrudes compared to its neighbors and iteratively remove sudden bumps (high-frequency noise) while preserving the overall shape of the mesh. This is achieved by iteratively adjusting the locations of each vertex to move it closer to the local average. 











