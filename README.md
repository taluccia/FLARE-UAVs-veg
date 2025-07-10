# FLARE-UAVs-veg

## Overview

This repository hosts the scripts used for data cleaning, organization, and analysis to support the paper by Talucci et al. (2020).


Talucci, A. C., E. Forbath, H. Kropp, H. D. Alexander, J. DeMarco, A. K. Paulson, N. S. Zimov, S. Zimov, and M. M. Loranty. 2020. Evaluating Post-Fire Vegetation Recovery in Cajander Larch Forests in Northeastern Siberia Using UAV Derived Vegetation Indices. Remote Sensing 12:2970.

[Link to publication](https://www.mdpi.com/2072-4292/12/18/2970)

## Abstract

The ability to monitor post-fire ecological responses and associated vegetation cover
change is crucial to understanding how boreal forests respond to wildfire under changing climate
conditions. Uncrewed aerial vehicles (UAVs) oﬀer an aﬀordable means of monitoring post-fire
vegetation recovery for boreal ecosystems where field campaigns are spatially limited, and available
satellite data are reduced by short growing seasons and frequent cloud cover. UAV data could be
particularly useful across data-limited regions like the Cajander larch (Larix cajanderi Mayr.) forests
of northeastern Siberia that are susceptible to amplified climate warming. Cajander larch forests
require fire for regeneration but are also slow to accumulate biomass post-fire; thus, tall shrubs and
other understory vegetation including grasses, mosses, and lichens dominate for several decades
post-fire. Here we aim to evaluate the ability of two vegetation indices, one based on the visible
spectrum (GCC; Green Chromatic Coordinate) and one using multispectral data (NDVI; Normalized
Diﬀerence Vegetation Index), to predict field-based vegetation measures collected across post-fire
landscapes of high-latitude Cajander larch forests. GCC and NDVI showed stronger linkages with
each other at coarser spatial resolutions e.g., pixel aggregated means with 3-m, 5-m and 10-m radii
compared to finer resolutions (e.g., 1-m or less). NDVI was a stronger predictor of aboveground
carbon biomass and tree basal area than GCC. NDVI showed a stronger decline with increasing
distance from the unburned edge into the burned forest. Our results show NDVI tended to be a
stronger predictor of some field-based measures and while GCC showed similar relationships with
the data, it was generally a weaker predictor of field-based measures for this region. Our findings
show distinguishable edge eﬀects and diﬀerentiation between burned and unburned forests several
decades post-fire, which corresponds to the relatively slow accumulation of biomass for this ecosystem
post-fire. These findings show the utility of UAV data for NDVI in this region as a tool for quantifying
and monitoring the post-fire vegetation dynamics in Cajander larch forests.

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

**Statistical Analysis**'

- 3.1_UAV-GCC-NDVI-Correlations
- 3.2_UAV-GCC-NDVI-Mean-SD
- 3.3_UAV-Biomass-Analysis
- 3.4_Field-UAV-BasalArea
- 3.5_UAV-EdgeEffect_Analysis
