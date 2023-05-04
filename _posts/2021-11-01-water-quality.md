---
title: Water Quality 💧
layout: post
category: project
sidebar-hide: true
---

## Water Quality Assessment based on MODIS daily product

This project is a work contract with the DLR, in which I explored the potential of MODIS in evaluating global inland water quality. Despite extensive research, many developed spectral indices fails to retrieve water quality information consistently beyond local scale due to atmospheric influences. This prototyping project aims to fill this gap and to evaluate the potential of a global assessment using MODIS imagery. 

It tests documented research approaches using Google Earth Engine and examines water quality in two dimensions: turbidity and eutrophication. Results are validated globally, as well as in Tai Lake, China, where field data from the research stations are available. The output of this project is a decision tree classifier, where water pixels are classified into 5 classes in each dimension.

<figure>
	<img src="{{ 'assets/images/water-quality.jpg' | relative_url }}" alt="water"  width="1000" />
	<figcaption>Evaluating Water Quality in Tai Lake</figcaption>
</figure>