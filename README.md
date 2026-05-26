# Image-Compression_FFT
Simple implementation of image compression using FFT in MATLAB

## Introduction
Image Compression is a method in which the information content of the image is reduced in such a way that the image maintains a level of clarity with a reduced size. It is a method to reduce/remove the fine details of the image and retain the major broader features of the image.

## Working
A 2-Dimensional Fast Fourier Transform Function *[fft2()]* is applied on the image, which returns its frequency mapped image in 2-Dimensions. In this form, the pixel have certain frequency values which correspond to the features of the image before transformation at that point.
Then an appropriate threshold is selected (99%, 10%, 1%, 0.1%, etc) is selected, and any frequency values that do not meet the threshold, will be delected and all other frequencies will remain.
Finally, the thresholded image is converted back into its time domain form to get the compressed image output.

## Credits
This is an implementation of image compression in MATLAB for various compression sizes.
This is an implementation of Steve Brunton's Video on the same topic.
### Video Link:
https://youtu.be/KGiV_2i713I


