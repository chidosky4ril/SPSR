## SPSR
Separable property-based super-resolution of lousy image data (PAAA2019)
Authors: Ike, C. S. & Muhammad, N. 
Pattern Analysis & Applications 
https://doi.org/10.1007/s10044-019-00854-8

## Abstract
This paper presents a novel wavelet-based approach for single-image super-resolution. Our technique integrates wavelet transform and the learned locally regularized anchored neighborhood regression model for more robust frequency estimation and image restoration. First, we decomposed the low-resolution input image into four frequency sub-bands by applying discrete wavelet transform and then processed these frequency sub-bands based on separable property of neighborhood filtering to achieve a fast parallel and vectorized operation by reducing computational burden resulting from computing the weighted function of every pixel for each pixel in an image. We then applied inverse discrete wavelet transform to reconstruct the original image. Super-resolution is achieved using the learned model to predict the high-resolution image features. Lastly, we explicitly unified both the locality structure and nonlocal self-similarity properties in natural image and incorporated them into our super-resolution framework to regularize the nonlinear correlation between low-resolution and high-resolution space and improve the reconstructed results. Experiments on standard images validate the effectiveness of our proposed method for effective denoising, deblurring and super-resolution reconstruction tasks compared to other top performing state-of-the-art methods both quantitatively and qualitatively.











## Citation

Please cite our paper if you find the work useful:

  @article{ike2020separable,
  title={Separable property-based super-resolution of lousy image data}
  author={Ike, Chidiebere Somadina and Muhammad, Nazeer},
  journal={Pattern Analysis and Applications},
  volume={23},
  number={3},
  pages={1407--1420},
  year={2020},
  publisher={Springer}
}
