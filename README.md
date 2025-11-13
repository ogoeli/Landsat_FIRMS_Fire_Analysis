# Landsat & FIRMS Fire Analysis with Google Earth Engine

This repository contains a Google Earth Engine (GEE) script for analyzing Landsat 8 imagery and FIRMS fire datasets. The script includes cloud masking, burn index calculation, thermal anomaly detection, and vectorization of fire-affected areas.

## Features

- **Cloud and Shadow Masking:** Uses the `QA_PIXEL` band of Landsat 8 to mask clouds, cloud shadows, and snow.
- **Burn Index (NBR):** Calculates the Normalized Burn Ratio to detect burned areas.
- **Thermal Anomaly Detection:** Identifies pixels exceeding a thermal threshold using Landsat Band 10.
- **FIRMS Fire Data Integration:** Filters FIRMS hotspots for the study area and generates vector layers.
- **Date Range Filtering:** Automatically calculates ±2 week periods for temporal analysis.
- **Visualization:** Adds layers to the Earth Engine map with custom palettes for NBR and thermal masks.
- **Export Capabilities:** Exports raster masks and vectorized fire areas as GeoTIFF or GeoJSON to Google Drive.
- **Feature Extraction:** Extracts Landsat band values for points or polygons in the study area.

