# Stormwater Runoff (inch)
## Summary
<!-- Add a one or two sentence to describe this indicator -->
Stormwater nutrient runoff algorithm is based on runoff depth for a 24 hr-10year event coupled with event mean concentrations (EMCs) of non point pollutants like Total Nitrogen (TKN), sediments (TSS and TDS) or Total Phosphorous. Runoff volume is estimated in GIS from empirical equations (ex.the curve number method), and fed by a series of raster data layers such as topography, land cover & management (detailed for regenerative practices), hydrologic soil groups, and a rainfall raster for a 24 hour, 10 year storm event (suggestion, to be discussed).  Final results are reported as: concentration (mg/l) 
## Details
<!-- Add a more detailed description about this indicator -->
Reccomended raster resolution for the input layers for runoff water depth is 10m for land cover (sentinel based), 30m for topography (srtm layers), and 30m for hydrologiic soil groups (30 m resol. is available for US, Puerto Rico and some other areas. When no such resolution is available, the 250m global HYSOG is recommended).

## Status
<!-- Choose one of the following Draft | Proposed | In Review | Production -->
- Draft: work in progress


## Revision History
v0.1 - initial draft

# Contributors
Your name

