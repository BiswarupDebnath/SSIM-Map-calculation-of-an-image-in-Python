# SSIM-Map-calculation-of-an-image-in-Python
This is the exact Python version of the following MATLAB code:  https://ece.uwaterloo.ca/~z70wang/research/ssim/ssim_index.m  
SSIM index is a full reference image quality index. For more details, refer to the following paper:  
Z. Wang, A. C. Bovik, H. R. Sheikh, and E. P. Simoncelli, "Image quality assessment: From error measurement to Structural similarity" IEEE Transactios on Image Processing, vol. 13, no. 1, Jan. 2004.  

In the above Python version of the code, constants used are the default constants as mentioned in the MATLAB code.  

Usage: 
ssim_index, ssim_map = cal_ssim(img1, img2)  

img1, img2 are single channel or RBG image
