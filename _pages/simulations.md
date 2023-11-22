---
layout: archive
title: "Selected Course Projects/ Simulations"
permalink: /simulations/
author_profile: True
---

## Branched Cylinders: Dendritic Tree Approximations
Explored some of the time independent electrical properties of single branched cables. Branched cables are an important means of modelling the passive electrical properties of axonal and dendritic trees. For convenience, trees exhibiting only one order of branching were considered. Nevertheless, the principles could be easily extended to higher order trees.
<p align="center"><img src="../images/dendritic.png" width="450"/><img src="../images/ss.png" width="400"/></p>
In the above diagram, V<sub>1</sub>,V<sub>21</sub> and V<sub>22</sub> are the membrane potentials of the respective branches. d<sub>1</sub>, d<sub>21</sub> and d<sub>22</sub> are the diameters of the parent and daughter branches respectively and X is axial distance.

By solving the differential equations with the given nodal and boundary conditions, steady-state voltage profile in each branch could be determined. 

## Properties of the Hodgkin-Huxley equations
Many of the properties of the propagating action potential are similar to the membrane action potential. The features; <b>threshold, refractoriness</b> (absolute and relative), <b>repetitive activity, temperature dependence</b> that are observed physiologically, were simulated using the Hodgkin-Huxley equations.
<p align="center"><img src="../images/hh.png" width="450"/></p>

## Mathematical Modelling of Compartmental Systems
Many compartmental systems can be represented by a series of first-order differential equations.
* Bolies Glucose/ Insulin Model
* Riggs Model for Iodine Metabolism
<p align="center"><img src="../images/cs.png" width="450"/><img src="../images/gi.png" width="400"/></p>

## Image Downsampling Processor
Designed and simulated/implemented a processor that could down-sample an input image using Vivado Design Suite. The input image was transmitted to the processor where the image is down-sampled and once finished, the results were sent back for display purposes.
<p align="center"><img src="../images/downsample_proc.png" width="800"/></p>
<p align="center"><img src="../images/image_cameraman.jpg" width="350"/>      <img src="../images/cameraman_downsampled.jpg" width="175"/></p>
<p align="center">Original and Downsampled Image</p>


## Object Counting on a Moving Conveyor Belt
Hexagonal nuts on a moving conveyor belt were detected and localized from a video stream using a conventional image processing pipeline including;
* Otsu Thresholding
* Morphological Closing
* Connected Component Analysis
* Contour Analysis
<p align="center"><img src="../images/com_vision.png" width="1050"/></p>