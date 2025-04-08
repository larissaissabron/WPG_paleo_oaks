# Pleistocene-Holocene Oak Paleoecology in the Willamette Valley-Puget Trough-Georgia Basin (WPG) Ecoregion

## Literature review, data mining, and filtering

All .xlsx files are provided because they include associated metadata. 

Table 1: Literature review, data mining, and filtering

| File | Description |
|---|---|
| [1_paleo_litreview.xlsx](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/1_paleo_litreview.xlsx) | Literature review with reference list. |
| [2_paleo_spatialfilter.xlsx](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/2_paleo_spatialfilter.xlsx) | Paleorecords within the ecoregion. |
| [3_wpg_oak_paleo_alldata.xlsx](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/3_wpg_oak_paleo_alldata.xlsx) | Data mining of paleorecords. |
| [4_wpg_oak_paleo_clean.xlsx](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/4_wpg_oak_paleo_clean.xlsx) | Cleaned up version of data mining to become .csv for use in R. |

## Spatial data products 

Table 2: Spatial data

| File | Description |
|---|---|
| [Pacific Northwest Ecoregions](https://data-wadnr.opendata.arcgis.com/datasets/3b9362e8f29e465a985aa8ddc8de2d86_0/about) | Puget Trough polygon was isolated and used to approximate ecoregion boundary. |
| [WPG Ecoregion Boundary](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/WPG.zip) | Ecoregion boundary which is the Puget Trough boundary extracted from PNW ecoregions shapefile. |
| [WPG 10km Buffer](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/WPG_10km.zip) | Polygon that is WPG + 10 km buffer used to spatially filter paleoecological research sites. |
| [WPG oak paleo research sites](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/wpg_paleo.zip) | Shapefiles for 31 oak paleoecology research sites in WPG. |

## Graphics

Table 3: Graphics

| File | Description |
|---|---|
| [Map oak paleo research sites](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/2025.04.07_wpg_oak_paleo.png) | Map of 31 oak paleoecology research sites in the WPG ecoregion. |
| [First oak pollen](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/2025.04.08_wpg_oakfirst_fig.png) | First ever and first continuous oak pollen records. |
| [First oak pollen filtered sites](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/2025.04.08_wpg_oakfirst_filtered_fig.png) | First ever and first continuous oak pollen records from sites with records too long or short to include in main figure. |
| [Maximum oak pollen](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/2025.04.08_wpg_oakmax_fig.png) | Maximum oak pollen records. |
| [Maximum oak pollen filtered sites](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/2025.04.08_wpg_oakmax_filtered_fig.png) | Maximum oak pollen records from sites with records too long or short to include in main figure. |
| [Modelled oak pollen trends](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/2025.04.08_wpg_oak_trends.png) | Oak pollen trends for first, first continuous, and maximum pollen visualized using a glm line of best fit. |

## R Code

Table 4: R Code

| File | Description |
|---|---|
| [RMarkdown script for figures](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/WPGOakRecords_Figures.Rmd) | RMarkdown script used to make figures. Use [clean records](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/4_wpg_oak_paleo_clean.xlsx) for data but save to your computer as a .csv. |
| [Resulting HTML file for figures](https://github.com/larissaissabron/WPG_paleo_oaks/blob/main/WPGOakRecords_Figures.html) | HTML file product of 'knitting' RMarkdown script used to make figures. To view, right click, 'save file as,' save as .html, choose to open in browser. |

