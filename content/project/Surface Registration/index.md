---
title: Surface Registration
date: 2023-01-10
share: False
image:
  placement: 1
  focal_point: 'Center'
  preview_only: true
tags:
  - Graphics
---

Surface registration with iterative closest point (ICP) algorithm.

<!--more-->
{{< video src="featured.mp4" controls="yes" >}}

This project finds the transformation matrix to rotate and translate multiple meshes to align them to the same coordinate system and align the overlapping parts of the mesh. Using ICP, we can align several scans of an object taken from multiple angles and merge them into a single mesh. You can find the derivation of the point-to-point implementation [here](https://github.com/mejhana/SurfaceRegistration/blob/main/icp_derivation.pdf)






