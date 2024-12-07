# Prioritizing Marine Aquaculture
Determining which West Coast Exclusive Economic Zones are best suited for developing marine aquaculture


## About
Marine aquaculture has the potential to be a sustainable protein option for global food supply ([Gentry et al.](https://www.nature.com/articles/s41559-017-0257-9)). In this project we will use data surrounding bathymetry, sea surface temperature (SST), and Exclusive Economic Zones (EEZ) to determine west coast areas suitable for marine aquaculture. We will specifically explore areas suitable for oysters and spiny lobsters.


## Highlights
- Combining raster and vector data
- Resampling raster data
- Masking raster data
- Map algebra
- Using functions for a generalizable workflow


## Repository Structure
```
|── marine-aquaculture 
|└── README.md
|└── marine-aquaculture.html
|└── marine-aquaculture.qmd  
|└── marine-aquaculture.Rproj
|└── marine-aquaculture_files
|  └── figure-html/
|    └── unnamed-chunk-5-1.png
|    └── unnamed-chunk-5-2.png
|    └── unnamed-chunk-5-3.png
|    └── unnamed-chunk-6-1.png
|  └── libs/
|    └── ~
|└── .gitignore  
|  └── data/ # Too large to push to github
│   └── average_annual_sst_2008.tif
│   └── average_annual_sst_2009.tif
│   └── average_annual_sst_2010.tif
│   └── average_annual_sst_2011.tif
│   └── average_annual_sst_2012.tif
│   └── cb_2018_us_state_20m
│      └── cb_2018_us_state_20m.cpg
│      └── cb_2018_us_state_20m.dbf
│      └── cb_2018_us_state_20m.prj
│      └── cb_2018_us_state_20m.shp
│      └── cb_2018_us_state_20m.shp.ea.iso.xml
│      └── cb_2018_us_state_20m.shp.iso.xml
│      └── cb_2018_us_state_20m.shx
│   └── depth.tif
│   └── wc_regions_clean.dbf
│   └── wc_regions_clean.prj
│   └── wc_regions_clean.shp
│   └── wc_regions_clean.shx
|  └── .Rproj.user
|  └── .Rhistory
|  └── .Rdata
|  └── .Ruserdata
```


## Data
The sea surface temperature data is generated from [NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php). It covers temperature from 2008-2012 and uses the averages within regions.

The bathymetry data used to determine ocean depth is from the [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area)

The third dataset was used to determine Exclusive Economic Zones on the US West Coast and is form [Marineregions.org](https://www.marineregions.org/eez.php).

Data on optimal growing conditions for oysters and spiny lobsters was obtained frm [SeaLifeBase](https://www.sealifebase.ca/search.php).


## References
1. National Oceanic and Atmospheric Administration. "NOAA Coral Reef Watch 5-km Satellite Sea Surface Temperature Anomaly Product." Accessed Nov. 11, 2024.

2. General Bathymetric Chart of the Oceans (GEBCO). "Gridded Bathymetry Data." Accessed Nov. 11, 2024.

3. Marine Regions. "Exclusive Economic Zones (EEZ)." Accessed Nov. 11, 2024.

4. SeaLifeBase. "Search Species." Accessed Nov. 26, 2024.

5. Gentry, R. R., Froehlich, H. E., Grimm, D., Kareiva, P., Parke, M., Rust, M., Gaines, S. D., & Halpern, B. S. Mapping the global potential for marine aquaculture. Nature Ecology & Evolution, 1, 1317-1324 (2017)


