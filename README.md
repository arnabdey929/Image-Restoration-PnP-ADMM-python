# PnP-ADMM-using-BM3D-python

This is a Super-Resolution implementation of PnP ADMM using BM3D as the denoiser inside.
Link to paper - https://arxiv.org/abs/1605.01710

There is an official MATLAB implementation of this paper also : https://engineering.purdue.edu/ChanGroup/

# Example shown in Notebook

The example in the notebook uses an image I found on the internet, and downsampled it by a factor of 3.
Upon applying the PnP ADMM algorithm as described in the paper, the result is quite astonishing, a PSNR of 22.71, even after a 3x "upsampling".

# Note
I have tried to keep the python code as similar as possible to the MATLAB code so that debugging would be easy.
Currently I have included only BM3D, and will shortly update for the other methods.
