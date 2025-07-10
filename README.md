# FLARE-UAVs-veg

This repository contains code central to:

- Talucci, A. C., E. Forbath, H. Kropp, H. D. Alexander, J. DeMarco, A. K. Paulson, N. S. Zimov, S. Zimov, and M. M. Loranty. 2020. Evaluating Post-Fire Vegetation Recovery in Cajander Larch Forests in Northeastern Siberia Using UAV Derived Vegetation Indices. Remote Sensing 12:2970.

[Link to publication](https://www.mdpi.com/2072-4292/12/18/2970)


![A map of the study area in northeastern Siberia, Russia. Panel (A) shows the location of the
Figure 1. A map of the study area in northeastern Siberia, Russia. Panel A shows the location of the
study area in Northeastern Siberia, Russia outlined by the blue box, which highlights the area of the
study area in Northeastern Siberia, Russia outlined by the blue box, which highlights the area of the
inset map. The inset map shows the location of the transects that are labeled with a background of a
inset map. The inset map shows the location of the transects that are labeled with a background of a
composite Landsat image. Panel (B) shows the NDVI image calculated from the multispectral UAV
composite Landsat image. Panel B shows the NDVI image calculated from the multispectral UAV
data for the CN transect 1. Panel (C) shows the visible spectrum (RGB) UAV data for the CN transect 1.](img/map.png)


## Research Objectives

1. Determined how GCC and NDVI relate to each other across a fine (25 cm) to coarse (10 m) spatial resolution to understand how fine-scale heterogeneity influences reflectance. 
2. Evaluated how these vegetation indices correspond to aboveground carbon biomass and basal area of live trees and tall deciduous shrubs. 
3. Assessed how vegetation indices distinguish burned versus unburned areas and edge effects. 

### Scripts assosciated with Research Objectives

Scripts are numerically ordered based on the processing steps. 

**Field Data**

- 1.1_Field-data-organization
- 1.2_Field-data-spatial

**Data organization and extraction**

- 2.1_Calculate-GCC-NDVI
- 2.2_GCC-field-data
- 2.3_NDVI-field-extract
- 2.4_UAV-Field-Raw-Data-Visualization

**Statistical Analysis**

- 3.1_UAV-GCC-NDVI-Correlations
- 3.2_UAV-GCC-NDVI-Mean-SD
- 3.3_UAV-Biomass-Analysis
- 3.4_Field-UAV-BasalArea
- 3.5_UAV-EdgeEffect_Analysis
