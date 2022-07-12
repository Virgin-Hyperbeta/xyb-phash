# XYB-pHash

This is an attempt to make modern[^1] perceptual hash. This hash does not try to reduce hash length, as there's extremely fast nearest neighbor libraries.

## Color decomposition
First, we decompose colors into XYB color space. This perceptually orthogonal color space is used by JPEG XL, and performs uniformly well in high-frequency domain unlike CIECAM16.

## position-momentum distribution
We'll explore bilinear time–frequency distributions, and downscale it. 

[^1]: Does not care about computational difficulties. /s
