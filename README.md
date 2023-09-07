# Magnetic Resonance Conductivity Imaging (MRCI) Toolbox
<ul>

The repository can provide various working algorithms for MREIT (Magnetic Resonance Electrical Impedance Tomography), MRCDI (Magnetic Resonance Current Density Imaging) and MREPT (Magnetic Resonance Electrical Properties Tomography) reconstructions and MRI data as well. These algorithms can be used to reconstruct images of the electrical conductivity of tissues using MRI data. Some of the preprocessing tool for reconstructing Magnetic flux density or Optimized Transmit phase has not been provided here.

# Please use https://iirc.khu.ac.kr/toolbox.html for downloading the MRCI Toolbox for conductivity imaging using MRI as described in [Software Toolbox for Low-Frequency Conductivity and Current Density Imaging Using MRI](https://ieeexplore.ieee.org/document/7994618). 

# For CoReHa (Conductivity Reconstructor using Harmonic Algorithms) software, please use https://iirc.khu.ac.kr/CoReHa.html for downloading. 

MRCI is a free open-source software toolbox package for electrical conductivity and current density image reconstruction using MRI data. It allows you to use multiple algorithms and state-of-the-art electromagnetic property imaging with conductivity phantom and in-vivo MR data. MRCI is a semiautomatic image reconstruction package run on Matlab [Python version is under development] and some functions need external software such as COMSOL Multiphysics [Mesh generation and forward solver] otherwise mentioned in documentation. Future updates will be without COMSOL but for the time being a mesh file is provided with tutorials.
  
If you are using Toolbox or this document, please cite **S. Z. K. Sajib, N. Katoch, H. J. Kim, O. I. Kwon and E. J. Woo, "Software Toolbox for Low-Frequency Conductivity and Current Density Imaging Using MRI," in [IEEE Transactions on Biomedical Engineering](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10), vol. 64, no. 11, pp. 2505-2514, Nov. 2017, doi: 10.1109/TBME.2017.2732502.**

This repository also provides implementations of several key mathematical functions for conductivity and current density image reconstructions. The list of techniques provided in this repository are:

<li> Magnetic Resonance Electrical Impedance Tomography (MREIT)</li> 
<li> Magnetic Resonance Current Density Imaging (MRCDI)</li> 
<li> Diffusion tensor-MREIT (DT-MREIT)</li>
<li> Magnetic Resonance Electrical Properties Tomography (MREPT)</li>
