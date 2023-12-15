# perovXimager
X-ray direct-converting detector characterization app, made by researchers from ETH Zurich, Kovalenko group: https://kovalenkolab.ethz.ch/

Features:

1) Calculation of main figures-of-merits for X-ray direct-converting detectors:
Detection and attenuation efficiency (DE, AE), noise equivalent dose (NED), detective quantum efficiency (DQE), modulation transfer function (MTF), spatial resolution, DQE vs. spatial frequency. Additional DE, NED, DQE vs. X-ray energy dependencies. Photon count event and rise time evaluation.
2) Plots saving (by click)
3) Units can be specified near the load button for every input data.
4) Added a few sets of input data for known materials for X-ray detection. All necessary files can be loaded by clicking on the button "Load example". Example raw data is provided.
5) The colors of the plots can be changed.

How to install

Application is made in MATLAB 2022b and converted into a standalone application for OS Windows. To install, launch perovXimager_instalation.exe. The installer will download MATLAB Runtime (you don't need any MATLAB license) and install the program. Folder "Examples", which contains TXT files with raw data, is not needed during installation. You have to download it in case you want to work with the source code, provided in perovXimager.mlapp (here, an actual MATLAB license is required).
**DISCLAIMER**
Created by the installer shortcut will launch the application incorrectly, so the button "Load example" will not work for a currently unknown reason. Therefore, avoid this option and create a shortcut manually from the .exe file, installed by default in C:\Program Files\ETH Zurich-Kovalenko Group\perovXimager_converted\application or the one you have specified during installation.
