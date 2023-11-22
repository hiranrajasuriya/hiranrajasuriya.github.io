---
layout: archive
title: "Selected Projects/ Simulations"
permalink: /simulations/
author_profile: True
---

## Digital Filters for Biosignal Processing
Implemented the following digital filters on MATLAB and filtered biomedical signals, specifically noisy ECG signals. 
* Smoothing Filters
  - Moving average filters
  - Savitzky-Golay filters
* Ensemble Averaging
* FIR Derivative Filters
* FIR Filters based on Windows
  - Rectangular window
  - Hanning window
  - Hamming window
  - Blackman window
  - Kaiser window
* IIR Filters
  - Butterworth LPF
<p align="center"><img src="../images/ecg_filt_1.png" width="800"/></p>

For more details: <a href = 'https://drive.google.com/file/d/1GRp5eKdRQ7RfSJI6jinCFlwDzy3G_77w/view?usp=sharing'>Report</a>

## Optimum and Adaptive Filters for Biosignal Processing
Conventional FIR and IIR filters are designed based on limited information on temporal and spectral characteristics of the signal. Moreover, one might say that they are ad-hoc filters as trial-and-error method is sometimes used to determine the filter specifications. 

On the other hand, optimum filters such as the Wiener filter could be employed for a given time series by considering the statistical characteristics of the signal and noise, under the following assumptions.
* Signal and noise processes are independent
* Signal and noise are stationary
* Desired signal is known
* Noise characteristics are known

When the signal and noise are non-stationary, we would have to apply filters that are optimal as well as adaptive. Some examples for such filters are, 
* Least Mean Square (LMS) method
* Recursive Least Squares (RLS) method
<p align="center"><img src="../images/ecg_filt_2.png" width="800"/></p>

For more details: <a href = 'https://drive.google.com/file/d/1o5V144nOX08O-X7uEo6TzVeLjodfKjWH/view?usp=sharing'>Report</a>

## Continuous and Discrete Wavelet Transforms
Implemented continuous and discrete wavelet transforms using built-in MATLAB functions and applied them for denoising and compression of different signals. 

In the context of continuous wavelet transforms (CWT), there are many wavelet families such as Shannon, Mexican hat, Morlet, etc. However, the drawbacks of CWT include highly redundant computations which leads to the requirement of additional computational power and time consumption. Avoiding this, in discrete wavelet transform (DWT), the scaling and translation are performed in a discrete manner.
<p align="center"><img src="../images/ecg_filt_3.png" width="800"/></p>

For more details: <a href = 'https://drive.google.com/file/d/1ibvX1KQhU91rrmV9r5tyR29LXqCfo0OY/view?usp=sharing'>Report</a>


## Branched Cylinders: Dendritic Tree Approximations
Explored some of the time independent electrical properties of single branched cables. Branched cables are an important means of modelling the passive electrical properties of axonal and dendritic trees. For convenience, trees exhibiting only one order of branching were considered. Nevertheless, the principles could be easily extended to higher order trees.
<p align="center"><img src="../images/dendritic.png" width="450"/><img src="../images/ss.png" width="400"/></p>
In the above diagram, V<sub>1</sub>,V<sub>21</sub> and V<sub>22</sub> are the membrane potentials of the respective branches. d<sub>1</sub>, d<sub>21</sub> and d<sub>22</sub> are the diameters of the parent and daughter branches respectively and X is axial distance.

By solving the differential equations with the given nodal and boundary conditions, steady-state voltage profile in each branch could be determined. 

For more details: <a href = 'https://drive.google.com/file/d/1jjmqrKMkHgaRf0pqWFG-mMN3Vr79IYv7/view?usp=sharing'>Report</a>

## Properties of the Hodgkin-Huxley equations
Many of the properties of the propagating action potential are similar to the membrane action potential. The features; <b>threshold, refractoriness</b> (absolute and relative), <b>repetitive activity, temperature dependence</b> that are observed physiologically, were simulated using the Hodgkin-Huxley equations.
<p align="center"><img src="../images/hh.png" width="450"/></p>

For more details: <a href = 'https://drive.google.com/file/d/1UFPYGIXockZTfHUblWP9migdCa2Y3OCP/view?usp=sharing'>Report</a>

## Mathematical Modelling of Compartmental Systems
Many compartmental systems can be represented by a series of first-order differential equations.
* Bolies Glucose/ Insulin Model
* Riggs Model for Iodine Metabolism
<p align="center"><img src="../images/cs.png" width="450"/><img src="../images/gi.png" width="400"/></p>

For more details: <a href = 'https://drive.google.com/file/d/1D8cFy-ad_XFkPkeByfzMhiE7XNZY3Tkx/view?usp=sharing'>Report</a>

## Image Downsampling Processor
Designed and simulated/implemented a processor that could down-sample an input image using Vivado Design Suite. The input image was transmitted to the processor where the image is down-sampled and once finished, the results were sent back for display purposes.
<p align="center"><img src="../images/downsample_proc.png" width="800"/></p>
<p align="center"><img src="../images/image_cameraman.jpg" width="350"/>      <img src="../images/cameraman_downsampled.jpg" width="175"/></p>
<p align="center">Original and Downsampled Image</p>

For more details: <a href = 'https://drive.google.com/file/d/17boW2Lucrl8q1lLBczsg5-FsFSRw2sct/view?usp=sharing'>Report</a>


## Object Counting on a Moving Conveyor Belt
Hexagonal nuts on a moving conveyor belt were detected and localized from a video stream using a conventional image processing pipeline including;
* Otsu Thresholding
* Morphological Closing
* Connected Component Analysis
* Contour Analysis
<p align="center"><img src="../images/com_vision.png" width="1050"/></p>

For more details: <a href = 'https://drive.google.com/file/d/1A49N0SqSG2mHoBpuD9Ckj3xq1O-_QkWk/view?usp=sharing'>Report</a>