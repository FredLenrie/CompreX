# Image-Compression

This project implements the JPEG algorithm for image compression. JPEG is a lossy compression in which some of the data from the original image is lost

## JPEG Compression

JPEG (Joint Photographic Experts Group) is a popular image compression standard that achieves high compression ratios by applying a series of mathematical transformations on the image data. The JPEG encoder in this project takes a color/grayscale image as input and applies the following steps:

1. Divide the image into blocks.

2. Apply a discrete cosine transform (DCT) on each block to convert it into a frequency domain representation.

3. Quantize the DCT coefficients by dividing by the quantization matrix.

4. Perform zigzag scanning for each block.

5. Truncate each encode block to the specified number of coefficient parameters and return the encoded image

The JPEG decoder reverses the above steps to reconstruct the original image from the compressed data.


![233417587-5d362e93-45d5-438d-add2-e1ed3a407128](https://github.com/FredLenrie/CompreX/assets/138697797/c0d0f403-b844-431e-ad91-647aecdcbfac)


