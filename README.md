                                                                                                                                                  ![ITU_LOGO](logo/ITU_logo.png)

# Change-Detection

This code calculates difference from NDTI images. It can be used for change detection on the images with different dates.
It can be easily modified for other indices.

## Libraries that are used in jupyter notebook on python 3.8.5

- rasterio 1.1.8
- numpy 1.19.4
- matplotlib 3.3.3
- gdal 3.1.4
- scipy 1.5.3

## Input Bands for landsat8

- Band6 (SWIR1)
- Band7 (SwIR2)

## Outputs

- NDTI Images
- NDTI difference
- NDTI threshold Image
- NDTI threshold removed noise Image

**NDTI difference Threshold square image**  ![MODE_THRESHOLD_SQUARE_NDTIDIF](https://github.com/cengizhunter/Change-Detection/blob/main/Output/threshold_square_ndtidif.png)

**After 3x3 Mode Filter**  ![MODE_THRESHOLD_SQUARE_NDTIDIF](https://github.com/cengizhunter/Change-Detection/blob/main/Output/mode_threshold_square_ndtidif.png)

 
 
 ### References that I used for this code
- [Change Detection between NDVI Images]
-  [NDVI Index calculation Hatari Labs]
 
[Change Detection between NDVI Images]: https://github.com/tkorting/youtube/tree/master/basic-change-detection-in-rs
[NDVI Index calculation Hatari Labs]: https://www.hatarilabs.com/ih-en/ndvi-calculation-from-landsat8-images-with-python-3-and-rasterio-tutorial

