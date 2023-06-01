# gx-live




![Untitled (2)](https://github.com/im-tanyasuri/gx-live/assets/109717636/6393cfe5-c381-44de-bfba-0685ecbac447)

**GEDI L2A data contains following columns:**

> "BEAM", "shot_number", "Latitude", "Longitude", "index", "degrade_flag", "delta_time", "digital_elevation_model", "digital_elevation_model_srtm",
>  "elev_lowestmode", "elevation_bias_flag", "num_detectedmodes", "quality_flag",
>  "rh_0": -2.0099999904632568, "rh_1": -1.8999999761581421, "rh_2",........."rh_100",
>  "rx_assess_quality_flag", "selected_algorithm", "sensitivity", "solar_elevation", "surface_flag"




```
The latitude and longitude here is the central coordinate for which we are provided with the relative height metrics.
We have to geo reference the rh values with sentinel -2 bands
Get the mean value for the 25m diameter radius and form a table with all the band mean and rh ground truth values
```



### Heatmap showing various Tree canopy heights
- ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) `>=8.6`


![tch_adani](https://github.com/im-tanyasuri/gx-live/assets/109717636/0a92c59e-2df2-4118-a75e-1ba7c586792a)
