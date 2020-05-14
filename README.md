# RG-CACHE

![](https://img.shields.io/badge/MATLAB-R2017b-green.svg)

![](https://img.shields.io/badge/MATLAB-Image%20Processing%20Toolbox-green.svg)

![](https://img.shields.io/badge/OS-CentOS%206.5-green.svg)

Code of the paper "[Reflectance-guided, contrast-accumulated histogram equalization](https://www.researchgate.net/publication/341083911_Reflectance-guided_contrast-accumulated_histogram_equalization)"

* In this paper, we proposed a histogram equalization-based image enhancement method that adapts to the data-dependent requirements of brightness enhancement and improves the visibility of details without losing the global contrast.

* Please read `LICENSE.md` for license details.

* The original code was tested using MATLAB R2017b on a machine running CentOS 6.5, but should also work on other OSs.

* Requirements

  * MATLAB
  * Image Processing Toolbox (Required by LIME)

* run `mex ContrastAccumulatedHistogram.c` to build mex function

* run `demo.m` for the demo

* `LIME.p` is provided by [Guo et al.] (https://sites.google.com/view/xjguo/lime) , which is used as an edge preserving filter for illumination estimation.

* Test images are provided by [USC-SIPI] (http://sipi.usc.edu/database/) and by [Guo et al.] (https://sites.google.com/view/xjguo/lime)

* Technical questions should be directed to the contact author, Xiaomeng Wu, using the following email address:

  ![qr](qr.png)
