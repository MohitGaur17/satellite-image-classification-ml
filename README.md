# Satellite Image Classification Using Machine Learning Techniques

![QGIS](https://img.shields.io/badge/QGIS-3.40-green)
![Landsat 9](https://img.shields.io/badge/Landsat-9-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Remote Sensing](https://img.shields.io/badge/Remote-Sensing-success)
![Python](https://img.shields.io/badge/Python-In%20Progress-yellow)

## Overview

This project focuses on land-cover classification and analysis of Landsat 9 satellite imagery for the Jodhpur region, Rajasthan, India, using Geographic Information System (GIS) techniques and Machine Learning algorithms.

The workflow covers the complete remote sensing pipeline including satellite data acquisition, preprocessing, Area of Interest (AOI) extraction, NDVI generation, supervised and unsupervised image classification, accuracy assessment, post-processing, and comparative analysis using the Semi-Automatic Classification Plugin (SCP) in QGIS.

The project is being developed as part of a research internship on Remote Sensing, GIS, and Machine Learning.


## Objectives

- Download and preprocess Landsat 9 satellite imagery.
- Generate True Color and False Color Composite images.
- Create the Area of Interest (AOI).
- Perform study area subsetting.
- Generate NDVI for vegetation analysis.
- Perform supervised land-cover classification.
- Perform unsupervised land-cover classification.
- Evaluate classification accuracy.
- Compare different machine learning algorithms.
- Generate land-cover statistics and thematic maps.


## Study Area

**Location:** Jodhpur District, Rajasthan, India

The study area contains diverse land-cover types including:

- Built-up Area
- Vegetation
- Water Bodies
- Mining Area
- Other Area / Barren Land

The diversity of these land-cover classes makes the region suitable for supervised and unsupervised image classification.


## Dataset

**Satellite**

- Landsat 9 OLI/TIRS

**Source**

- USGS Earth Explorer

**Raw Data**

https://drive.google.com/drive/folders/15g_Pc1WvXukniYDe2-pWzDZiFauS3iKF?usp=sharing

**Spatial Resolution**

30 m

**Coordinate Reference System**

WGS 84 / UTM Zone 43N (EPSG:32643)


## Software & Tools

### GIS

- QGIS
- Semi-Automatic Classification Plugin (SCP)

### Data Source

- USGS Earth Explorer


## Machine Learning Techniques Used

### Supervised Classification

- Maximum Likelihood Classification
- Random Forest Classification

### Unsupervised Classification

- K-Means Clustering


## Project Workflow

1. Landsat 9 Data Download
2. Data Organization
3. RGB Composite Generation
4. False Color Composite Generation
5. AOI Creation
6. Study Area Subsetting
7. NDVI Computation
8. ROI Collection
9. Maximum Likelihood Classification
10. Random Forest Classification
11. K-Means Clustering
12. Accuracy Assessment
13. Sieve Filtering
14. Classification Report Generation
15. Classification to Vector Conversion
16. Cross Classification
17. Comparative Analysis


## Project Structure

```text
Satellite Image Classification Using Machine Learning Techniques
│
├── README.md
├── Python/
│
├── QGIS Project/
│   ├── Jodhpur_Project.qgz
│   ├── AOI/
│   ├── Classification/
│   │   ├── Accuracy_Assessment/
│   │   ├── Classification_Output/
│   │   │   ├── CrossClassification/
│   │   │   ├── KMeans/
│   │   │   ├── MaximumLikelihood/
│   │   │   └── RandomForest/
│   │   ├── Classifier/
│   │   ├── PCA/
│   │   ├── Spectral_Signatures/
│   │   ├── Training_Data/
│   │   └── Validation_Data/
│   │
│   ├── NDVI/
│   ├── RGB Composite/
│   └── Subset Data/
│
├── Raw Data/
└── Report/
```

## Implemented Outputs

- True Color Composite (RGB)
- False Color Composite (FCC)
- Area of Interest (AOI)
- Study Area Subset
- NDVI Map
- Maximum Likelihood Classification
- Random Forest Classification
- K-Means Classification
- Accuracy Assessment
- Confusion Matrix
- Kappa Coefficient
- Classification Reports
- Sieve Filtered Classification
- Classification to Vector
- Cross Classification


## Land-Cover Classes

The classified map contains five land-cover classes:

| Class ID | Land-Cover Class |
|----------|------------------|
| 1 | Built-up Area |
| 2 | Vegetation |
| 3 | Water Bodies |
| 4 | Mining Area |
| 5 | Other Area / Barren Land |


## Classification Techniques Comparison

| Method | Type |
|---------|------|
| Maximum Likelihood | Supervised |
| Random Forest | Supervised Machine Learning |
| K-Means | Unsupervised Machine Learning |


## Repository Status

### Completed

- Landsat Data Download
- RGB & False Color Composite
- AOI Generation
- Study Area Subsetting
- NDVI Generation
- ROI Creation
- Maximum Likelihood Classification
- Random Forest Classification
- K-Means Clustering
- Accuracy Assessment
- Classification Report
- Sieve Filtering
- Classification to Vector
- Cross Classification

### In Progress

- Python Implementation
- Comparative Analysis (QGIS vs Python)
- Final Report


## Author

**Mohit Gaur**
B.E. Information Technology
MBM University, Jodhpur


## License

This project is intended for educational, research, and internship purposes.

