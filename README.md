Overview

This project develops a set of spatially explicit socio-demographic indices to analyze vulnerability, inequality, and urban transformation patterns.
It integrates census, infrastructure, and open spatial datasets to produce composite indicators at the local scale, supporting ecological and territorial planning.

The notebook socio_demographic_composite_index.ipynb implements data preprocessing, dimensionality reduction (PCA/EFA), and visualization of index results.

Objectives

Build composite indices for multidimensional poverty, affluence/accessibility, and family vulnerability.

Identify spatial patterns of social exclusion and urban transition.

Provide quantitative inputs for ecological infrastructure and risk adaptation planning.

Data sources

Nepal Census (2011, 2021) – National Statistics Office

OpenStreetMap (OSM) – Infrastructure and services

Google Earth Engine layers – Land cover, vegetation, hydrology

Local administrative boundaries – Kathmandu Valley municipalities

Methods

Data harmonization: merging demographic, economic, and infrastructural datasets.

Variable selection and standardization.

Exploratory Factor Analysis (EFA) to identify latent dimensions.

Principal Component Analysis (PCA) to compute variable weights.

Index aggregation and normalization.

Spatial visualization in QGIS and Python
