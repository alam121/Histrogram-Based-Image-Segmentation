# Histrogram-Based-Image-Segmentation
Implementaion of python code for defining grey level ranges for each feature of interest to perform segmentation. The tutorial also covers basic image processing operations in order to clean up the segmented regions.

The process for this segmentation consits of 3 steps.
* Denoising the orignal image using Non-local means algorithm
* Plot a histogram of the flatten image to observe the grey level ranges
* Creating masks based on the grey level features and construct a new image based on these masks

## Orignal Image

![Orignal Image](https://github.com/alam121/Histrogram-Based-Image-Segmentation/blob/master/1.jpg)


## Denoised Image 
![denoised Image](https://github.com/alam121/Histrogram-Based-Image-Segmentation/blob/master/Denoised.JPG)

## Segmentaion result

![Segmented Image](https://github.com/alam121/Histrogram-Based-Image-Segmentation/blob/master/Segmented%20Image.JPG)
