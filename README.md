# Awesome-Geospatial-Intelligence

## Top Geospatial Intelligence Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Satellite Imagery Analysis, Geospatial Analytics, Mapping & Earth Observation*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Geospatial Intelligence**. These tools help analysts, urban planners, and developers process satellite imagery, perform spatial analysis, build interactive maps, and extract actionable insights from geospatial data.

**Examples** include Picterra, Esri ArcGIS Online, CARTO, Felt, Nearmap, Mapbox, UP42, Orbital Insight, Descartes Labs, and Safe Software FME Cloud (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom geospatial pipelines, and transparent Earth observation workflows — ideal for organizations that need full control over sensitive spatial data without per-seat licensing or vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Picterra](https://picterra.ch/)**  
  Geospatial AI platform for detecting objects and changes in satellite and aerial imagery. No-code model training for use cases like infrastructure monitoring, agriculture, and environmental analysis.

- **[Esri ArcGIS Online](https://www.esri.com/en-us/arcgis/products/arcgis-online/overview)**  
  Cloud-based mapping and analysis platform within the Esri ecosystem. Provides smart mapping, spatial analytics, dashboards, and story maps with extensive data integration capabilities .

- **[CARTO](https://carto.com/)**  
  Cloud-native geospatial analytics platform built on modern data warehouses. Provides SQL-driven analysis, location data services, and embedded map visualization with deep spatial statistics (Getis-Ord, Moran's I, kriging) .

- **[Felt](https://felt.com/)**  
  Collaborative mapping platform designed for teams. Focuses on ease of use with real-time collaboration, simple styling defaults, and shareable maps rather than chaptered story maps .

- **[Nearmap](https://www.nearmap.com/)**  
  Aerial imagery provider with high-resolution capture (4cm in some areas). Offers frequently updated imagery for major settlements, primarily in Australia, New Zealand, and North America .

- **[Mapbox](https://www.mapbox.com/)**  
  Mapping and location platform providing APIs, SDKs, and design tools for custom maps. Widely used for embedding interactive maps in web and mobile applications .

- **[UP42](https://up42.com/)**  
  Geospatial marketplace and developer platform. Provides access to satellite and aerial imagery from multiple providers with APIs for processing and analysis .

- **[Orbital Insight](https://orbitalinsight.com/)**  
  Geospatial analytics platform using AI to analyze satellite and aerial imagery at scale. Focuses on economic activity monitoring, supply chain intelligence, and infrastructure tracking.

- **[Descartes Labs](https://descarteslabs.com/)**  
  Geospatial analytics platform combining satellite imagery with machine learning for agriculture, forestry, and environmental monitoring.

- **[Safe Software FME Cloud](https://www.safe.com/fme/fme-cloud/)**  
  Cloud-based spatial ETL platform for data transformation and integration. Handles 400+ formats with visual workflow builder, widely used for CAD-to-GIS and format translation pipelines .

## Open-Source GitHub Projects

- **[QGIS](https://github.com/qgis/QGIS)**  
  The leading open-source desktop GIS. Full spatial statistics toolbox, richest rendering and labeling engine, extensive plugin ecosystem (thousands of Python plugins), and full print layout composer with atlas support. Imports QGIS .qgs/.qgz projects and exports OGC SLD, QML, and Mapbox GL JSON. The de facto standard for open-source GIS work .

- **[GeoLibre](https://github.com/opengeos/GeoLibre)**  
  Modern open-source GIS workspace with AI-powered natural-language assistant that turns plain English into auditable, undoable operations. Features AI Segmentation (SamGeo/SAM 3), in-browser ONNX/YOLO object detection, built-in story map builder, dashboards with cross-filtering, and full Jupyter anywidget integration for two-way project sync. Imports ArcGIS Pro .aprx and QGIS .qgz projects .

- **[Dekart](https://github.com/dekart-xyz/dekart)**  
  Self-hosted backend for Kepler.gl positioning as open-source alternative to CARTO and Felt. Connects to Postgres, BigQuery, Snowflake, and Wherobots with SQL connectors. Features MCP integration enabling Claude/Codex agents to build maps from data, SSO support (Google OAuth, Keycloak, AWS Cognito), and single Docker container deployment with zero configuration using SQLite .

- **[Brew GIS](https://github.com/zbyte64/brewgis)**  
  Docker-based GIS workspace for urban planners and data scientists. Built on Django 6.0 with PostGIS, MapLibre GL JS, and integrated dbt analytics pipeline (40 models, 17 macros). Features scenario comparison, built forms (building/place types), Census/LEHD/OSM data import, and MCP server for AI assistant integration .

- **[JupyterGIS](https://github.com/opengeos/jupytergis)**  
  Open-source web-GIS bringing interactive geospatial workflows to Jupyter. Interleaves code and visualization with real-time collaborative editing via CRDT (ydoc). Can run on Kubernetes backends or as static WebAssembly site with no backend. Bundled in Pangeo and GeoJupyter initiatives. Supports coediting with LLM-based AI agents .

- **[TerraScout AI](https://github.com/gilgameshisthekingofuruk-wq/terrascout-ai)**  
  Comprehensive open-source geospatial intelligence platform with 314+ modules covering analysis/AI (76 modules), earth science (40), environment (75), people/society (58), infrastructure (25), disasters/risk (22), and space tracking (12). Features AI scoring engine, anomaly detection, change detector, flood/wildfire models, and real-time global dashboards .

- **[GDAL/OGR](https://github.com/OSGeo/gdal)**  
  The foundational geospatial data translation library. Reads and writes 200+ spatial formats (ogr2ogr for vectors, gdal_translate/gdalwarp for rasters). Underlying engine in QGIS, ArcGIS Pro, and most desktop GIS tools. Essential replacement for FME's format translation capabilities .

- **[PDAL](https://github.com/PDAL/PDAL)**  
  Point Data Abstraction Library for point cloud and LiDAR processing. JSON pipeline format with Python bindings. Handles LAS/LAZ conversion, ground classification (SMRF filter), thinning, tiling, colorization, and intensity normalization. The open-source equivalent of FME's point cloud transformers .

- **[MapLibre GL JS](https://github.com/maplibre/maplibre-gl-js)**  
  Open-source fork of Mapbox GL JS under BSD license. Eliminates API token requirements and costs. Full support for interactive maps, draggable markers, and vector tile rendering. Part of broader MapLibre ecosystem including Martin (vector tile server from PostGIS/PMTiles) and MapLibre Native for iOS/Android/desktop .

- **[Photon](https://github.com/komoot/photon)**  
  Free geocoding service using OpenStreetMap data. No API key required (fair-use rate limits). Returns GeoJSON with coordinates as [lon, lat]. Drop-in replacement for Mapbox Geocoding SDK .

- **[PostGIS](https://github.com/postgis/postgis)**  
  Spatial database extender for PostgreSQL. OGC-compliant spatial functions including ST_Buffer, ST_Intersects, ST_Area, ST_Union, and ST_Transform. Enables SQL-based geospatial transformations faster and more auditable than sequence of GDAL calls .

- **[GeoNetwork](https://github.com/geonetwork/core-geonetwork)**  
  GPL-licensed catalog application for spatial information management. Organizes and facilitates access to cartography, spatial databases, and metadata through a single entry point. Based on open standards, supports decentralized data from multiple repositories. Funded by FAO, WFP, UNEP, and UN-OCHA .

- **[OpenLayers](https://github.com/openlayers/openlayers)**  
  BSD-licensed JavaScript library for displaying maps in any modern browser. Uses standard methods (WMS, WFS) for accessing cartographic data. Can combine information from different servers and work with GML data .

### Additional Strong Open-Source Options

- **Desktop GIS**: **QGIS** (richest ecosystem), **GeoLibre** (modern AI-integrated), **Brew GIS** (urban planning focus).
- **Web Mapping Backends**: **Dekart** (Kepler.gl backend), **Martin** (vector tiles), **Tipg** (OGC Features API).
- **Earth Observation Processing**: **Sen2Like** (Sentinel-2 harmonization), **eo-learn** (Earth observation processing chains), **openEO** (interoperable EO cloud processing).
- **Point Clouds & LiDAR**: **PDAL** (pipeline-based processing), **GeoTile** (raster tiling), **GeoTrellis** (point cloud OGC server).
- **Imagery & Street-Level**: **Panoramax** (federated street-level imagery, 23M+ photos, 225k+ km covered) .
- **Map Rendering**: **MapLibre GL JS** (interactive web maps), **OpenFreeMap** (free tile provider, no API key) .

**Frameworks for building custom systems**: Combine **QGIS** or **GeoLibre** for desktop analysis, **Dekart** or **Brew GIS** for web-based workspaces, **GDAL/OGR** for format translation, **PDAL** for point cloud processing, and **PostGIS** for spatial queries. Add **MapLibre GL JS** for rendering and **Photon** for geocoding.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Geospatial intelligence platforms handle sensitive location and imagery data; ensure compliance with privacy regulations and imagery licensing terms.
- Open-source geospatial stacks require significant operational investment in data pipelines, tile servers, and storage infrastructure.

---

**Made for GIS analysts, remote sensing scientists, urban planners, and geospatial developers.**
Let's make geospatial intelligence more open, interoperable, and accessible.
