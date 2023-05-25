# EEG-Brain-Visualization-Tool
![logo](https://github.com/ortizo-117/Brain-Visualization-Tool/assets/71515296/7f33a48d-122b-4e8b-837b-eb85488261e5)

Tool to visualize epoched data in the time frequency domain. Functionality at this point includes:
-  Time domain peak identification and extraction
-  Time frequency decomposition using complex wavelet transform
-  Extraction of ROIs of time frequency decomposition 
-  Experimental: Wavelet filter using non-parametric statistic testing

Requirements:
- Matlab 2020 or higher
- Signal Procesing Toolbox for Matlab
- EEGLab


Can be installed by downloading the current packaged "Brain Visualization Tool.mlappinstall" app and following this tutorial (https://www.mathworks.com/videos/packaging-and-installing-matlab-apps-101563.html)

With this app you can manually select and extract peaks in the time domain:

![Capture4](https://github.com/ortizo-117/Brain-Visualization-Tool/assets/71515296/704f0862-5d7e-406d-bc15-8b434f266e70)


Perform time frequency decomposition of the signals using wavelet transforms:

![Capture5](https://github.com/ortizo-117/Brain-Visualization-Tool/assets/71515296/cb56e676-5ed2-42d8-9c75-5385f44bc81c)


Easily inspect diferent aspects of the wavelet transform like phase-locked, non-phase-locked, ITC, and manually extract regions of interest from any channel:

![Capture](https://github.com/ortizo-117/EEG-Brain-Visualization-Tool/assets/71515296/074bfe2a-cd70-4880-968e-a8d49676ea93)

Experimental Feature: Wavelet-Assisted Reconstruction Method (WARM) filter: An adaptive wavelet filter used to identify significant features of your waveform based on non-parametric permutation testing.

![Capture_2](https://github.com/ortizo-117/EEG-Brain-Visualization-Tool/assets/71515296/2e01831f-f3f2-423b-afdd-a0cda9f381f1)
