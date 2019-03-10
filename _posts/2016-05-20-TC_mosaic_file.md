---
title: "TissueCyte Mosaic File"
excerpt: "Meaning of the fields in the TissueCyte mosaic file"
header:
  teaser: "/assets/images/home/GCamp6s_brain.jpg"
categories:
  - Acquisition
tags: 
  - TissueCyte
toc: false
---

This post describes the meaning of the fields in the Mosaic file. 
The following shows the field names, example value, and a description of what the field means. 

- **rows**: 832 - number of rows of pixels in a single tile 
- **columns**: 832 - number of columns of pixels in a single tile 
- **layers**: 2 - number of optical sections
- **xres**: 0.875  - nominal pixel separation in x (microns). [*You might want to confirm this by direct measurement*]
- **yres**: 0.875  - nominal pixel separation in y (microns)
- **zres**: 10  - nominal resolution between z planes (microns). When doing optical sectioning, the separation between - z planes is twice the zres value 
- **mrows**: 11 - The number of rows of tiles
- **mcolumns**: 17 - The number of columns of tiles
- **mrowres**: 710 - The step size in microns along rows
- **mcolumnres**: 684 - The step size in microns along columns
- **sections**: 300 - Number of sections
- **sectionres**: 45 - Section thickness in microns
- **channels**: 3 - Number of channels
- **Pixrestime**: 0.8 - pixel dwell time in nanoseconds
- **PdTauFwd**: 9.95 - Correction factor for bidirectional scanning
- **PdTauRev**: 9.95 - Correction factor for bidirectional scanning
- **MCSkew**: 3 - Unknown
- **ScanRange**: 2.2 - The x mirror scanner amplitude
- **ScannerVScalar**: 0.49 - The y mirror scanner amplitude is ScanRange * ScannerVscalar
- **TriggerLevel**: 0.737305 - Unknown
- **ImageAdjFactor**: 0.95 - Unknown
- **ZWaitTime**: 100 - PIFOC settling time in microseconds
- **Zposition**: 0 - Starting z position
- **Zscan**: 1 - 1 if optical sectioning 0 otherwise 
- **ZdefaultVoltage**: 0 - offset?
- **ZScanDirection**: 1 - should aways be 1, or the PIFOC will move upwards instead of downwards
- **SliceTranslationSpeed**: 0.3 - X stage speed in microns per second during cutting 
- **Vibratome Frequency**: 60 - cycles per second of the vibrotome DC motor during cutting 
- **VibratomeStageSpeed**: 20 - X stage speed in microns per second during blade approach
- **VibratomeDelay**: 8 - Time to wait in seconds with the blade still vibrating after the cut is complete. 
- **startnum**: 0 - The first section number
- **excwavelength**: 800 - Laser wavelength (value entered manually by user) 
- **excpower**: 50 - Laser power (value entered manually by user)
- **objective**: - objective name (value entered manually by user)
- **Description**: Sample information  - Entered by user
- **Sample ID**: K102 -  Entered by user
- **acqDate**: 9/26/2015 1:29:10 PM -  Acquisition start time (automatically filled in)
- **comments**: Enter comments here - Entered by user
- **ScannerID**: GolgiDoodle - Name of the scanning system system
