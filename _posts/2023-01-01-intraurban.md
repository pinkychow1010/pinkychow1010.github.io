---
title: Climate Risk Assessment 🏙️
layout: post
category: project
sidebar-hide: true
---

## [World Bank: Climate Risk Assessment in Urban Pakistan](https://sites.google.com/view/intraurban/home)

<br>

<figure>
	<img src="{{ 'assets/images/night.jpg' | relative_url }}" alt="snowcover"  width="800" />
</figure>

As of May 2023, I am appointed to a short-term position as a climate risk consultant in the World Bank, working under the Poverty Reduction and Equity Group for Pakistan. Our team works on the Pakistan Country Climate and Development Report (CCDR), posting the need for detailed analysis of national climate risk using earth observation data and the humanity dataset. 

My project in the team is to automate existing analysis workflow using cloud computing, providing scalability for other regions. Hence, I independently developed algorithms using Google Earth Engine Javascript API to create an interactive dashboard for intraurban analysis. Those analysis tasks reveal societal and environmental changes, as well as climate-related hazards population encounters, such as the urban heat island effect, deforestation, and recent urbanization. 

The huge advantage of cloud computing is that users do not need any powerful machine to conduct the very computationally expensive EO analysis, such as modelling land surface temperature changes or vegetation dynamics in the last decades. The entire data processing workflow is performed on-the-fly, providing flexibility for users to study the desired regions. Apart from performing data analysis, a data explorer tool is also available for users to export analysis-ready spatial data layers for GIS applications in multiple data formats.

<figure>
	<img src="{{ 'assets/images/app.jpg' | relative_url }}" alt="snowcover"  width="800" />
	<figcaption><b>Fig. Example app interface for intraurban analysis</b></figcaption>
</figure>

<br>

The app has been published on a [Google site](https://sites.google.com/view/intraurban/home) and the code is available on [GitHub](https://github.com/pinkychow1010/wb-pak-intraurban).