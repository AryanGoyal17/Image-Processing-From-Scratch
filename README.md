# UAI302 – Image Processing from Scratch

B.E. (AI & Data Science), Thapar Institute of Engineering and Technology, Patiala

## About
A small image-processing toolkit written from scratch in plain Python and NumPy,
with no OpenCV, scikit-image, SciPy ndimage or PIL filters. Every algorithm is
implemented with explicit loops so each line can be explained.

## What's inside
- **Part A – Exploration:** image loading, RGB to grayscale, histograms, mean/variance/median
- **Part B – Point operations:** negative, gamma correction, contrast stretching, histogram equalisation
- **Part C – Noise and filtering:** `conv2d`, salt-and-pepper and Gaussian noise, mean/Gaussian/median filters, MSE and PSNR
- **Part D – Edges and thresholding:** Sobel, gradient magnitude and direction, Otsu's method
- **Part E – Inference:** written analysis of the results

## Dataset
USC-SIPI Image Database, Miscellaneous volume:
4.2.07 (Peppers), 4.2.03 (Mandrill), 5.1.09 (Moon surface),
boat.512 (Fishing Boat), gray21.512 (21-level step wedge).

## Repository structure

```
├── Assignment4_ImagePreprocessing.ipynb   # main notebook
├── data/                                  # test images
└── figures/                               # output plots
```

## How to run
1. Open the notebook in Google Colab.
2. Make sure the images are in `data/`.
3. Run all cells from top to bottom.

## Author
Aryan – [@AryanGoyal17](https://github.com/AryanGoyal17)