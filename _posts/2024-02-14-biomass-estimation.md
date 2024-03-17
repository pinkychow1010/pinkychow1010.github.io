---
title: Biomass Estimation using AI @ Ororatech
layout: post
category: project
sidebar-hide: true
---

## [Mapping Global Carbon Stock with CNNs](https://sites.google.com/view/intraurban/home)


<br>

<figure>
	<img src="{{ 'assets/images/biomass.jpg' | relative_url }}" alt="biomass"  width="800" />
</figure>

In June 2023, I contributed to a project at Ororatech within the ESA Natural Capital framework, where we utilized artificial intelligence to create a global model for mapping forest above-ground biomass. This model integrated Sentinel-2 and GEDI Level 4 data, enabling continuous estimation of carbon stock through near-real-time optical imagery. Leveraging over 2 million worldwide data samples, I developed algorithms for data ingestion, pipeline management, and an extensive framework for experimenting with various Convolutional Neural Network (CNN) model training options. Ancillary data, including digital elevation models and ESA WorldCover, were also incorporated. 

The resulting model exhibited state-of-the-art performance with relatively low bias for forests worldwide, though limitations were observed in tropical and subtropical moist forests. This project facilitated carbon monitoring despite constraints in field data availability.

<figure>
	<img src="{{ 'assets/images/biomass-workflow.jpg' | relative_url }}" alt="biomass"  width="800" />
  <figcaption>Project workflow</figcaption>
</figure>

<br>

<p float="left">
  <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="50" height="50">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/earth-europe.svg" width="50" height="50">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/python.svg" width="50" height="50">
</p>
