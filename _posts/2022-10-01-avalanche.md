---
title: Snow Avalanche Hazard Assessment @ Munich Re
layout: post
category: project
sidebar-hide: true
---

## Global Snow Avalanche Assessment


<span class="image left"><img src="{{ 'assets/images/input.jpg' | relative_url }}" alt="" /></span>

In this 8-month project, I independently developed a geospatial data product of snow avalanche hazards with global coverage from scratch. This baseline model considers long-term climate averages to assess avalanche hotspots, including estimating the mass flux extent.

<figure>
	<img src="{{ 'assets/images/pipeline.jpg' | relative_url }}" alt="workflow"  width="650" />
	<figcaption><b>Fig. Data pipeline for the hazard model</b></figcaption>
</figure>

<br>

The main challenges lie in the huge input quantity (0.5 TB) and the unscalability of the existing methodology, where global implementation is not feasible due to expensive computational requirements and climate assumptions. For resolution, the approach is modified and fully automated using a data pipeline. To do so, I have performed a detailed literature review on existing methodology and tecnical documentation for developing algorithms tailored to the business needs and resource constraints. The workflow is thoroughly tested, documented for continuous development and validated using very-high-resolution satellite imagery with over 1.8 million data points. The end product is a gridded global data layer with 30-meter spatial resolution, which is used on the in-house climate risk intelligence platform to provide hazard information for the customers' portfolios.

<figure>
	<img src="{{ 'assets/images/model.jpg' | relative_url }}" alt="modelvis"  width="800" />
	<figcaption><b>Fig. Data visualization example</b></figcaption>
</figure>

<br>

<p float="left">
  <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/microsoft.svg" width="50" height="50">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/python.svg" width="50" height="50">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/q.svg" width="50" height="50">
</p>