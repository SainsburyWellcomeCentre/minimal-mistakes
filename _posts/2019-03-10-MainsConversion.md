---
title: "Converting TissueCyte PSUs from 120V to 240V"
excerpt: "Post on how to switch the AC input voltage on the TissueCyte control boxes"
header:
  teaser: "/assets/images/home/GCamp6s_brain.jpg"
tags: 
  - hacks
  - TissueCyte
toc: false
share: false
---


Our microscope is in the EU but requires 120V AC, which is not convenient. 
We re-wired the PSUs to accept 240V AC instead. 
CAUTION: this involves re-wiring mains lines.


* The transformers have secondary windings that allow them to be switched to 240 V. Look up their model numbers on line and re-wire them. If you can't find this information, you shouldn't be performing this mod.
* Unplug the 120V AC fan underneath the galvo heat sink. You can run without.
* Replace the 120V MPS-80 PSU that powers the z-jack with a 240V version. Order from AMS directly.
* Pay attention to the wiring of the motor control box. Ours had the neutral mains line going to the shield cable of the stepper motor (!). Remove that if so. We also had three mystery wires that went to the distribution rails and connected only to each other and nothing else. The box three a breaker in our room unless these were removed.
