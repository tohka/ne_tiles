# XYZ tiles

Original data: Made by [Natural Earth](https://www.naturalearthdata.com/about/terms-of-use/). 1:10m Raster Data [Cross Blended Hypso with Relief, Water, Drains, and Ocean Bottom](https://www.naturalearthdata.com/downloads/10m-cross-blend-hypso/cross-blended-hypso-with-relief-water-drains-and-ocean-bottom/)

```shell-session
$ wget https://www.naturalearthdata.com/http//www.naturalearthdata.com/download/10m/raster/HYP_LR_SR_OB_DR.zip
$ unar HYP_LR_SR_OB_DR.zip
$ gdal2tiles.py -s EPSG:4612 -z 0-7 HYP_LR_SR_OB_DR/HYP_LR_SR_OB_DR.tif .
```
