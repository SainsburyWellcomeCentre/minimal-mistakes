---
title: "Registering widefield functional imaging data to the Allen Atlas"
excerpt: "Using blood vessel patterns to register in vivo data"
header:
  teaser: "/assets/images/posts/volume_view_vessels_teaser.jpg"
categories:
  - Analysis
tags: 
  - Registration
toc: false
---
 
Is it possible to use serial section imaging to determine the borders of cortical areas from in vivo widefield imaging experiments?

![image-left]({{ site.baseurl }}/assets/images/posts/volume_view_vessels.jpg){: .align-left} Displaying downsampled serial section data in Fiji's volume viewer it becomes obvious that at least the larger blood vessels are clearly visible on the surface rendering. Ivana Orsolic and Petr Znamenskiy decided to use the vessels to register widefield functional imaging data to serial section stacks and so to the Allen Atlas.

The brain was sliced and imaged then the downsampled volume was [registered to the Allen Atlas as usual](/registered). 
The 3D image stack is now in the same space as the Allen Atlas.
Using Petr's [recoverVasculature function](https://github.com/SainsburyWellcomeCentre/StitchIt/blob/master/code/stitchedStackManipulation/recoverVasculature.m) found in [StitchIt](https://github.com/SainsburyWellcomeCentre/StitchIt) the blood vessel patterns (now also in the Atlas space) are extracted from the downsampled serial section data. 
An affine transformation brings the in vivo data into the same space as the sample and hence into the same space as the Atlas. 



<figure>
    <img src="{{ site.baseurl }}/assets/images/posts/VasculatureRegFig.jpg" >
</figure>

