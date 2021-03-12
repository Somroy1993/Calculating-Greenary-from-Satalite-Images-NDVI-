# Calculating-Greenary-from-Satalite-Images-NDVI-
## Normalized Difference Vegetation Index (NDVI):
The concept of normalized difference vegetation index (NDVI) lies with the fact that plants have evolved to reflect near-infrared light, where visible light is strongly absorbed by almost all plants in photosynthesis. The measure is thus an index of these two aspects, helping to show how vigorous plant growth is happening in regions.

# NVDI = (NIR - RED) / (NIR+RED)

where NIR and Red stand for the reflected near-infrared light and reflected visible red light from the plants, respectively. It so happens that a healthy plant reflects more NIR and green light as compared to other wavelengths. However, it absorbs more red light. Thus, NDVI compares the reflected near-infrared light(NIR) to reflected visible red(Red) light, by the plants. The NDVI values range from +1.0 to -1.0, where 1 stands for the healthiest vegetation.

## Benefits of NDVI:
The NDVI values give a rough estimation of the type, amount and condition of a vegetation at a place which is very useful for researchers.
NDVI values can also be averaged over time to establish “normal” growing conditions in a region for a given time of year. This primarily helps in identifying areas where there are changes in vegetation due to human activities such as deforestation, natural disturbances such as wildfires, or changes in plants’ phenological stage.

## Data Sources:
Google earth, EARTHAI Notebook, Sentinel2 and many more.
I have used raster data, as it is free and also comes with python library rasterio.
The calculations and plots can be found on this Notebook .
Please have a look, and feel free to contact me for any other clarifications.

Thanks for reading.
