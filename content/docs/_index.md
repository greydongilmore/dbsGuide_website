+++
title= "Introduction"
description = ""
+++



## What is DBS Guide?
---

<p align="center"><img src="img/DBSLaunch.png" alt="drawing" width="50%"/></p>

**DBS Guide** is a surgical planning, visuazliation, and postoperative assessment tool used for deep brain stimulation. It is an extension that can be used with 3D Slicer (a well-known MRI Visualization software). DBS Guide provides capabilities across the entire surgical spectrum:

1. **Pre-operative**
   - Co-registration of MRI scans with 3D volumetric stealth MRI
   
   <p align="center"><img src="img/coregConfirmSlide.gif" alt="drawing" width="50%"/></p>
   
   - Planning DBS lead trajectory

2. **Intra-operative**
   - Co-restration of frame CT with MRI 
   - Confirmation of frame fiducials using automated frame detection (DBS Guide identifies the frame fiducials using image recognition)
   - Determining accuracy of (x,y,z) coordinates, arc and ring angles
   - Mapping of microelectrode (MER) recordings and plotting them in patient brain anatomy
   - Saving information regarding the trajectory used (medial, lateral, etc.) and other lead implant specs (e.g. depth)
3. **Post-operative**
   - Co-registration of post-op CT with pre-op MRI 
   - Visualization of implanted electrodes with high accuracy
   - Manipulation of stimulation settings 
   - Volume tissue activation model based on stimulation settings

To get a walk-through of DBS Guide and its capabilities in each phase of surgery (pre/intra/post-op), visit <a href="https://dbsguidedocs.readthedocs.io/en/latest/usage.html#usage" target="_blank">How to use DBS Guide</a>.
