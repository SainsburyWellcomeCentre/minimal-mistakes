---
title: "Imaging multiple samples at once"
excerpt: "BakingTray and StitchIt can now handle multiple samples at once"
header:
  teaser: "/assets/images/home/GCamp6s_brain.jpg"
categories:
  - Analysis
  - Acquisition
tags: 
  - Hacks
  - News
  - Sample prep
toc: false
---
 
It is now possible to image two or more brains at once with BakingTray and then split these up using the new StitchIt tool called "stitchit.sampleSplitter". 

The approach simply involves mounting the brains close together and imaging a single large ROI. 
After stitching, stitchit.sampleSplitter automatically identifies the ROIs associated with each brain and turns these into new sub-directories. 
One for each sample. 
The tool can also be used to crop an acquisition with a single ROI. e.g. perhaps because too much tissue was imaged. 
The doc text for the tool describes a workflow which allows these steps to be carried out on a remote analysis machine at the command line, without the need for a virtual desktop connection. 

Imaging multiple brains at once decreases setup time and makes more efficient use of the microscope, as short acquisitions can be run concurrently, keeping the microscope busy overnight.

### Links
[stitchit.sampleSplitter on GitHub](https://github.com/SainsburyWellcomeCentre/StitchIt/tree/master/code/%2Bstitchit/%40sampleSplitter)