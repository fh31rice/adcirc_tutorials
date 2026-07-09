This section will give you some idea about how you can get the data sources used in ADCIRC, say for example, where to get the hurricane tracks, or manning's n value, or DEM etc.

1. **[NOAA Tides & Currents](https://tidesandcurrents.noaa.gov/)** — Water level observations, tide predictions, and current data from NOAA gauge stations, useful for storm surge validation.

2. **[NOAA Coastal Elevation Models](https://www.ncei.noaa.gov/products/coastal-elevation-models)** — high-resolution DEMs (including CUDEM and NCEI coastal relief models) for bathymetry and topography in mesh generation.

3. **[NOAA C-CAP High-Resolution Land Cover](https://coast.noaa.gov/digitalcoast/data/ccaphighres.html)** — high-resolution coastal land cover data used to assign Manning's n roughness values in ADCIRC fort.13

4. **[NOAA Historical Hurricane Tracks](https://coast.noaa.gov/hurricanes/#map=4/32/-80)** — interactive map of historical hurricane and tropical storm tracks, useful for storm selection and track visualization.

5. **[NHC ATCF Archive](https://ftp.nhc.noaa.gov/atcf/archive/)** — FTP archive of Automated Tropical Cyclone Forecasting (ATCF) best-track files for all storms, used for hurricane track input in ADCIRC.

6. **[ERA5 Single Levels — Copernicus](https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels?tab=download)** — global reanalysis wind, pressure, and surface fields at hourly resolution, used as background wind forcing in ADCIRC.

7. **[MetGet (Water Institute)](https://github.com/waterinstitute/MetGet)** — open-source tool for retrieving and formatting meteorological forcing data (GFS, NAM, HWRF, ERA5) into OWI-format wind files for ADCIRC simulations

8. **[OceanMesh2D](https://github.com/CHLNDDEV/OceanMesh2D)** — MATLAB-based coastal ocean mesh generation toolbox for creating high-quality unstructured triangular meshes with nested resolution zones, bathymetry interpolation, and floodplain meshing for ADCIRC. This github has many data already downloaded, so check there folders. Also, they have a zenodo folder, scroll down their github page and you will find that. They have data like SRTM, coastal shapefiles, roughness data sources etc.

9. **[GEBCO](https://www.gebco.net/)** — global bathymetric grid data, used for open-ocean and shelf bathymetry in ADCIRC mesh generation.

10. **[DesignSafe Published Data](https://www.designsafe-ci.org/data/browser/public/designsafe.storage.published)** — repository of publicly shared research datasets including ADCIRC mesh files, simulation outputs, and storm surge model results from published studies.

11. **[LSU Surge Climate Portal](https://surge.climate.lsu.edu/index.html)** — Louisiana State University portal providing storm surge data.

12.  **[CERA — Coastal Emergency Risks Assessment](https://cera.coastalrisk.live/)** — real-time and hindcast ADCIRC storm surge visualization portal, useful for comparing modeled water levels and wave heights against your own simulation outputs.