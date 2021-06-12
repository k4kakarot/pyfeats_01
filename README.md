# Image Feature Extraction in ROI (Python)
A collection of python functions for feature extraction. The features are calculated inside a Region of Interest (ROI) and not for the whole image: the image is actually a polygon! More and more features will be added. Please feel free to point out any mistakes or improvemets. The aim is to create a library for image feature extraction. Message me for more details.

## A. Single point based statistical plaque features
### A.1  Single/Multi ROI
1. GSM
2. Stratified GSM
3. JBA
### A.2 Histogram based features
1. Histogram
2. Multi-region histogram
3. Correlogram
## B. Spatial based plaque features
### B.1 Early texture
1. First Order Statistics/Statistical Features (FOS/SF)
2. Gray Level Co-occurence Matrix (GLCM/SGLDM)
3. Gray Level Difference Statistics (GLDS)
4. Neighborhood Gray Tone Difference Matrix (NGTDM)
5. Statistical Feature Matrix (SFM)
6. Law's Texture Energy Measures (LTE/TEM)
7. Fractal Dimension Texture Analysis (FDTA)
8. Gray Level Run Length Matrix (GLRLM)
9. Fourier Power Spectrum (FPS)
10. Shape Parameters
### B.2 Later texture
1. Gray Level Size Zone Matrix (GLSZM)
2. Higher Order Spectra (HOS)
3. Local Binary Pattern (LPB)
### B.3 Morphological
1. Grayscale Morphological Analysis
2. Multilevel Binary Morphological Analysis
### B.4 Multi-scale
1. Fractal Dimension Texture Analysis (FDTA)
2. Amplitude Modulation – Frequency Modulation (AM-FM)
3. Discrete Wavelet Transform (DWT)
4. Stationary Wavelet Transform (SWT)
5. Wavelet Packets (WP)
6. Gabor Transform (GT)
### B.5 Other
1. Zernikes’ Moments
2. Hu’s Moments
3. Threshold Adjacency Matrix (TAS)
4. Histogram of Oriented Gradients (HOG)

## Use
Download the folder Features, add to path and call
```python
from Features import *
```

## Support
Reach out to me:
- [giakou4's email](mailto:giakonick98@gmail.com "giakonick98@gmail.com")

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/giakou4/Features/LICENSE)
