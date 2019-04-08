# Image_dominant_color_identification
## About
In this notebook we are using Python(OpenCV) to identify the dominant colors (hex code) and also eliminating the neutral colors (white, black and greys).

## Contents
- Loading Libraries
- Loading image from url
- Filter neutral colors (shades of gray)
- Define number of clusters for K-Means
- Fit KMeans on non-neutral image
- Dominant color in Hex format
- Function to extract dominant colors and examples

## Loading Libraries
We are using numpy,OpenCV,matplotlib,sklearn in this notebook.

## Loading image from url
Created fucntion to read image from url, which we extend at the end to also accept a list of urls.

## Filter neutral colors (shades of gray)
Converted colors to HSV, and converted gray color to white, which will be excluded at the end.

## Define number of clusters for K-Means
Number of clusters means number of dominant colors to be identified.

## Fit KMeans on non-neutral image
Kmeans is used to cluster the centroids together, to identify dominant colors.

## Dominant color in Hex format
Dominant colors are identified and converted to HEX format.

## Function to extract dominant colors and examples
A final function to extract dominant colors as well as example images.

![alt text](https://github.com/pranavrajwade/Image_dominant_color_identification/blob/master/Dominant1.PNG)
![alt text](https://github.com/pranavrajwade/Image_dominant_color_identification/blob/master/Dominant2.PNG)
![alt text](https://github.com/pranavrajwade/Image_dominant_color_identification/blob/master/Dominant3.PNG)
![alt text](https://github.com/pranavrajwade/Image_dominant_color_identification/blob/master/Dominant4.PNG)
