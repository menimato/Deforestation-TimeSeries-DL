## Reference data

To the full execution of all the scripts, reference data is stored in `./Data/ref`. Some pre-processing steps are needed in order to use them, and an example of these data is stored 

+ [SRTM](https://code.earthengine.google.com/2049cabd3e13f222468f49ae37c0ad5b)
    + The slope data must be clipped and resamples to the same extent, width and height in pixels, and EPSG to match the cubes generated.
+ [PRODES](http://terrabrasilis.dpi.inpe.br/en/download-2/)
    + **Yearly increment in native vegetation suppression - Shapefile** and **Accumulated area mask of native vegetation suppression - Shapefile** can be used to create the reference for the U-Net and LSTM references.
+ Study Area
    + Shapefile for the study area.
+ nodata_{cell}.tif
    + File with same extent, width and height in pixels, and EPSG as the clipped bands, for the Brazil Data Cube `{cell}` processed.
+ unet_chips.shp
    + Shapefile with points that correspond to the U-Net chips centroids.