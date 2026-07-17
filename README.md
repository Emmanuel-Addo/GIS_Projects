# GIS & Geospatial Projects

Welcome to the **GIS & Geospatial Projects** repository! This project showcases spatial analysis configurations, desktop GIS map documents, spatial analysis datasets, and WebGIS prototypes.

---

## Repository Structure & Components

This repository is divided into two primary areas: **Desktop GIS / Spatial Analysis** and **WebGIS / Interactive Map Prototypes**.

### 1. Desktop GIS & Spatial Analysis
This project uses Esri ArcGIS suite for spatial analysis and map publication. Key files include:
*   **Map Documents (`.mxd`)**:
    *   `Bivarite_mapping.mxd`: Configuration and layout for bivariate mapping visualization.
    *   `angggggggggggggggg.mxd`: Large-scale spatial analysis layout.
*   **Climate Spatial Analysis Data** (located in the [climate/](file:///c:/Users/use/Desktop/ADDO/climate) directory):
    *   `climate/CENTRAL_FEATURE_CLIMATE_POINTS.*`: Identifies the central feature of climate observations.
    *   `climate/CLIMATE_DIRECTIONAL_DISTRIBUTION.*`: Defines the directional trend (Standard Deviational Ellipse) of climate factors.
    *   `climate/CLIMATE_MEAN_CENTER.*`: Measures the average coordinate of climate events.
    *   `climate/CLIMATE_MEDIAN_CENTER.*`: Measures the median center of climate events.
    *   `climate/CLIMATE_STANDARD_DISTANCE.*`: Represents standard distance dispersion.
*   **Geospatial Vector Datasets**:
    *   Various Shapefiles (`data.*`, `north.*`, `pp.*`) and subdirectory datasets (`HI/p2.*`) containing spatial geometries and attribute tables.
    *   `New File Geodatabase.gdb/`: Structured Esri File Geodatabase for spatial data storage.

### 2. WebGIS & Interactive Map Prototypes
Interactive web-based geospatial visualizations designed with standard web technologies:
*   **GeoVision GIS Consult** (`webgis/`):
    *   [webgis/index.html](file:///c:/Users/use/Desktop/ADDO/webgis/index.html) & [webgis/NEW.HTML](file:///c:/Users/use/Desktop/ADDO/webgis/NEW.HTML): Interactive portal interface for utilities mapping, disease outbreak tracking, and urban planning support.
*   **Morton WebGIS** (`Morton WebGIS/`):
    *   `mORTON.HTML`: Web application showcasing targeted location-based GIS layouts.

---

## Technologies & Tools Used

*   **GIS Softwares**: Esri ArcGIS Desktop (ArcMap/ArcCatalog), Spatial Statistics tools, Mapping and Visualization toolset.
*   **Formats**: Shapefiles (`.shp`, `.dbf`, `.shx`, `.prj`), Map Documents (`.mxd`), Geodatabases (`.gdb`).
*   **Web Technologies**: HTML5, CSS3, Vanilla JavaScript (including DOM manipulation and responsive layouts).

---

## How to Explore the Projects

### Desktop GIS
1. Ensure you have **Esri ArcGIS Desktop** (ArcMap) installed.
2. Double-click either `Bivarite_mapping.mxd` or `angggggggggggggggg.mxd` to open the map layouts.
3. Ensure the data sources are relative to local shapefiles (relink datasets to layers if required).

### WebGIS Prototypes
1. Open the [webgis/NEW.HTML](file:///c:/Users/use/Desktop/ADDO/webgis/NEW.HTML) file directly in any modern web browser to interact with the GeoVision GIS portal mockup.
2. Navigate through the services and interactive project features.
