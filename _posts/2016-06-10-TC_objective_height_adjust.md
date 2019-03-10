---
title: "Objective height"
excerpt: "Protocol for adjusting TissueCyte objective height"
header:
  teaser: "/assets/images/home/GCamp6s_brain.jpg"
categories:
  - Acquisition
tags: 
  - TissueCyte
  - Maintenance
toc: false
---

The coarse Z-stage on the TissueCyte is not motorized and will need tweaking from time to time. 
Here is how to do this:


If you change to a new blade type or adjust the blade holder you will need to adjust the objective height. 
This is sometimes also necessary between samples, although it is not clear why this should be the case. 
The objective is mounted to a manually driven translation stage.
The absence of a motor on this stage makes the objective height adjustment procedure rather laborious, but it is straight forward. 

You will know it is necessary to adjust the objective height if the objective is located over the sample and everything is set up correctly but you can not find the surface of the sample (or even see the sample at all) when manually seeking with the PIFOC. 
If you don't have enough range with the PIFOC for optical sectioning, you will also need to adjust the objective height. 

The goal of the objective height adjustment is to get the image plane at roughly the same level as the 
sample surface. 
In other words to make the the image plane and the blade tip be at roughly the same level. 
The blade is fixed, so obviously we move the objective. 

The objective is screwed into the PIFOC, which itself is attached to a metal plate. 
The metal plate is attached to a translation stage that moves the whole arrangement vertically up and down. 
The stage is moved by an adjustment bolt.
Screwing *in* the adjustment bolt will push *down* the translation stage and *lower* the objective. 
*Unscrewing* the adjustment bolt allows the translation stage to be raised. 
Our translation stage appears not to be sprung and must be manually push upwards by hand after the adjustment screw is turned. 
There is a lock bolt on the translation stage on its rear edge. 
The lock bolt is hard to reach and because the stage is so stiff, we leave the lock bolt loose. 
To change the objective height do the following:

- Check whether the objective translation stage lock bolt needs loosening (unlikely).
The screw locking the objective in place is located behind the objective. 
To turn it, reach to the right of the objective between the vibrotome and the objective holder. 
The screw is located directly opposite from the adjustment bolt.
A quarter turn is sufficient to unlock it. 
Do not touch the imaging dichroic adjusters.

- Turn off the room lights. 
It's OK to leave the doors of the enclosure open in order to alternate between moving the objective and imaging. 
It helps to do this with two people if using the Orchestrator scanning software, since this is not capable of scanning continuously.
One person sits by the computer and presses the "2D" button. 


- Translate the objective using the adjustment bolt. 
Rotate the bolt to move the objective up or down.
If you require the objective to move up, be sure to press upwards beneath the bolt on the stage, and verify that the stage engaged the bolt after you moved it.
Do not push upwards on the objective or the PIFOC.
This can damage the PIFOC. 
If you don't know what the PIFOC looks like, then get help.

- If you know which way to move (e.g. move down if you put in a longer blade) then move that way.
Otherwise, just move in small increments the surface is usually nearby. 
- If you get lost, then it's likely easiest to move down until you're near the sample then move up slowly.
- Do not seek up and down with the z-stage controls in the software. 
If you do this you will change the cutting depth on your next slice and you will become very confused about where the surface is. 
- You are finished when the sample surface is visible with the PIFOC in the 150 micron to 250 micron range.

