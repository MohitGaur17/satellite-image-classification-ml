# Satellite Image Classification Using Machine Learning Techniques

## Overview

This project focuses on the classification and analysis of Landsat 9 satellite imagery of the Jodhpur region, Rajasthan, India, using Geographic Information System (GIS) tools and machine learning techniques.

The workflow includes satellite data acquisition, image preprocessing, RGB composite generation, study area subsetting, vegetation analysis using NDVI (Normalized Difference Vegetation Index), and land-cover classification. The project is being developed as part of an internship focused on remote sensing, GIS, and machine learning applications.

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

**Raw Data Download :** [Download Here](https://drive.google.com/drive/folders/15g_Pc1WvXukniYDe2-pWzDZiFauS3iKF?usp=sharing)

**Spatial Resolution:** 30 m

**Coordinate Reference System (CRS):**
WGS 84 / UTM Zone 43N (EPSG:32643)

---

## Software and Tools Used

### GIS Software

* QGIS

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
Satellite Image Classification Using Machine Learning Techniques
├── README.md
├── Python/
├── QGIS Project/
│   ├── AOI/
│   ├── Classification/
│   │   ├── Accuracy_Assessment/
│   │   ├── Classification_Output/
│   │   ├── Classifier/
│   │   ├── Spectral_Signatures/
│   │   ├── Training_Data/
│   │   └── Validation_Data/
│   ├── NDVI/
│   ├── RGB Composite/
│   └── Subset Data/
├── Raw Data/
└── Report/
```

### Folder Description

| Folder         | Description                                                                     |
| -------------- | ------------------------------------------------------------------------------- |
| Raw Data       | Contains the original Landsat 9 source data used for the project.              |
| QGIS Project   | Stores the QGIS project, AOI, RGB composites, NDVI results, and subsets.       |
| Classification | Contains training, validation, classifier, and classification output assets.   |
| Python         | Reserved for Python scripts and processing utilities.                          |
| Report         | Contains the internship report chapters and supporting documentation.          |


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
* Other Area / Barren Land

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
