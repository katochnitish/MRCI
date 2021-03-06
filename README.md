# Magnetic Resonance Conductivity Imaging (MRCI) Toolbox
<ul>

## Please use https://iirc.khu.ac.kr/toolbox.html for downloading  MRCI Toolbox for conductivity imaging using MRI as described in [Software Toolbox for Low-Frequency Conductivity and Current Density Imaging Using MRI](https://ieeexplore.ieee.org/document/7994618). For CoReHa (Conductivity Reconstructor using Harmonic Algorithms) software, please use https://iirc.khu.ac.kr/CoReHa.html for downloading. 

MRCI is a free open source software toolbox package for electrical conductivity and current density image reconstruction using MRI data. It allows you to use multiple algorithms and state of the art in electromagnetic property imaging with conductivity phantom and in-vivo MR data. MRCI is a semiautomatic image reconstruction package run on Matlab and some functions need external software such as COMSOL Multiphysics otherwise mentioned in documentation. Future updates will be COMSOL free but for the time being a mesh file is provided with tutorials.
  
If you are using toolbox or this document, please cite: **S. Z. K. Sajib, N. Katoch, H. J. Kim, O. I. Kwon and E. J. Woo, "Software Toolbox for Low-Frequency Conductivity and Current Density Imaging Using MRI," in [IEEE Transactions on Biomedical Engineering](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10), vol. 64, no. 11, pp. 2505-2514, Nov. 2017, doi: 10.1109/TBME.2017.2732502.**

This repository describes implementations of several key mathematical functions for conductivity and current density image reconstructions. The list of techniques provided in this repository are:

<li>Magneitic resonance electrical impedance tomography (MREIT)</li> 
<li>Magnetic resonance current density imaging (MRCDI)</li> 
<li>Diffusion tensor-MREIT (DT-MREIT)</li>
<li>Conductivity tensor imaging (CTI)</li>

  
## MREIT conductivity image reconstruction from Bz using CoReHa software

<li>Create Bz image from positive and negative current injected phase and reconstruct conductivity images using CoReHa software. It has been assumed that you have synchronized your current injection with MR pulse sequence and have acquired current perturbed phase.   

MR Signal equation corresponds to positive and negative current injection:
  
![](https://user-images.githubusercontent.com/14322345/122886072-98535100-d37a-11eb-9196-4376bb4579fc.png)
  
![image](https://user-images.githubusercontent.com/14322345/122886782-39420c00-d37b-11eb-9fe2-d98b431b0e4f.png)

![image](https://user-images.githubusercontent.com/14322345/122888373-c6d22b80-d37c-11eb-8027-e5b460d93123.png)

![image](https://user-images.githubusercontent.com/14322345/122888602-f8e38d80-d37c-11eb-953f-dcf4eb37db3b.png)
