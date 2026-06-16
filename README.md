# Satellite Image Classification Using Machine Learning

## Overview

This project focuses on the classification and analysis of Landsat 9 satellite imagery of the Jodhpur region, Rajasthan, India, using Geographic Information System (GIS) tools and Machine Learning techniques.

The workflow includes satellite data acquisition, image preprocessing, RGB composite generation, study area subsetting, vegetation analysis using NDVI (Normalized Difference Vegetation Index), and land-cover classification. The project is being developed as part of an internship focused on Remote Sensing, GIS, and Machine Learning applications.

---

## Objectives

* Download and process Landsat 9 satellite imagery.
* Generate RGB composite images for visual interpretation.
* Create and extract the Area of Interest (AOI).
* Perform study area subsetting using QGIS.
* Compute NDVI for vegetation analysis.
* Classify satellite imagery into major land-cover classes.
* Analyze spatial distribution of different land-cover features.
* Apply Machine Learning techniques for image classification.

---

## Study Area

**Location:** Jodhpur District, Rajasthan, India

The study area was selected due to the presence of diverse land-cover features including:

* Built-up Areas
* Vegetation
* Water Bodies
* Mining Areas
* Barren Land

These features make the region suitable for remote sensing and image classification studies.

---

## Dataset

**Satellite:** Landsat 9 OLI/TIRS

**Source:** USGS Earth Explorer

**Spatial Resolution:** 30 m

**Coordinate Reference System (CRS):**
WGS 84 / UTM Zone 43N (EPSG:32643)

---

## Software and Tools Used

### GIS Software

* QGIS

### Programming Language

* Python

### Python Libraries

* NumPy
* Pandas
* Matplotlib
* Rasterio
* GDAL
* Scikit-learn

### Data Source

* USGS Earth Explorer

---

## Project Workflow

1. Selection of Study Area
2. Downloading Landsat 9 Satellite Data
3. Data Organization and Preprocessing
4. Loading Raster Data into QGIS
5. RGB Composite Generation
6. Area of Interest (AOI) Creation
7. Study Area Subsetting
8. NDVI Computation
9. Image Classification
10. Result Analysis and Interpretation

---

## Project Structure

```text
satellite-image-classification-ml
│
├── Raw Data
│   ├── Landsat 9 March 2025
│   └── Landsat 9 October 2025
│
├── QGIS Project
│   ├── RGB Composite
│   ├── Subset Data
│   └── Jodhpur_Project.qgz
│
├── NDVI
│
├── Classification
│
├── Python
│   ├── Scripts
│   └── Outputs
│
└── Report

```

### Folder Description

| Folder         | Description                                                                     |
| -------------- | ------------------------------------------------------------------------------- |
| Raw Data       | Contains downloaded Landsat 9 satellite imagery used for analysis.              |
| QGIS Project   | Stores QGIS project files, RGB composites, and study area subsets.              |
| NDVI           | Contains NDVI calculations, outputs, and vegetation analysis results.           |
| Classification | Stores image classification datasets and classification outputs.                |
| Python         | Contains Python scripts and generated outputs used for processing and analysis. |
| Report         | Contains internship report chapters and final project documentation.            |


---

## Expected Outputs

* RGB Composite Image
* Area of Interest (AOI)
* Study Area Subset
* NDVI Map
* Classified Land-Cover Map
* Statistical Analysis of Land-Cover Classes

---

## Land-Cover Classes

The study focuses on identifying and classifying:

* Built-up Area
* Vegetation
* Water Bodies
* Mining Area
* Barren Land

---

## Future Work

* Advanced Machine Learning Classification
* Accuracy Assessment
* Change Detection Analysis
* Deep Learning-based Remote Sensing Applications
* Multi-temporal Satellite Image Analysis

---

## Author

**Mohit Gaur**

B.E. Information Technology
MBM University, Jodhpur

---

## License

This project is intended for educational, research, and internship purposes.
