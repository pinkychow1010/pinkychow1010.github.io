---
title: Fusing Satellite Data 🧱
layout: post
category: project
sidebar-hide: true
---

## DLR contract: Landsat - MODIS Data Fusion

This project is a work contract with DLR, which aims to gain additional information about surface water dynamics from satellite imagery by fusing Landsat and MODIS data.

To enhance the data product resolution, one way is to combine satellite imagery from high-temporal and spatial resolution using data fusion. This prototyping work utilizes the R package ImageFusion to implement multiple algorithms, namely STARFM, ESTARFM and FIT-FC, for fusing MODIS daily product and Landsat imagery. An automated workflow is developed in Python to transform HDF files directly to fused GeoTIFF imagery, including all the necessary pre-processing (eg. interpolation and reprojection) and transformation steps. It aims to evaluate the performance of algorithms in terms of run time and accuracy. The results indicate ESTARFM as the optimal algorithm, which achieves a high accuray of 96.6%.

<figure>
	<img src="{{ 'assets/images/fusion.png' | relative_url }}" alt="data-fusion"  width="800" />
	<figcaption>Data before and after data fusion using ESTARFM</figcaption>
</figure>