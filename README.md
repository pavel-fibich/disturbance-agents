# Distribution of disturbance agents
Distribution of disturbance agents as a part of project "Global pattern of forest disturbances and its shift under climate change" by Jan Altman, Pavel Fibich, Volodymyr Trotsiuk and Nela Maredova.

We provide raw input data (DataS1.csv) and 3 multi-band GeoTiff files here:
* agentsDistribution.tiff with disturbance agents proportions (0-100), in R e.g.
```
library(raster)
ad<-raster("agentsDistribution.tiff",band=1)
plot(ad,main="Fire disturbance distribution")
 ```
band in the code corresponds to individual agents, 1 is for fire, 2 for hydro-geo, 3 for outbreak, and 4 for wind.
* under2Cchange.tiff corresponds to percentage change under 2C climate change scenario,
* under4Cchange.tiff corresponds to percentage change under 4C climate change scenario.
