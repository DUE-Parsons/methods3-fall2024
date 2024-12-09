---
layout: project-page
title: "Mapping Shade: Rethinking Climate Comfort in Upper Manhattan"
linkname: mapping-shade-rethinking-climate-comfort-in-upper-manhattan
author: "Aqdas Fatima"
tagline: "Mapping shade in Upper Manhattan to address gaps in public infrastructure and ensure equitable climate comfort amid rising heat."
location:
    - place: New York, NY, USA
project-link:
    - href: https://felt.com/map/Upper-Manhattan-Shade-Map-HehJhO3qQ2ODeyJq3FdBhC?loc=40.79763,-73.94249,15.03z
    - href:  https://felt.com/map/Facilities-in-Heat-Vulnerable-Areas-copy-9CguvE9CD9BSuCDACPsV9BzcjA?loc=40.7569,-73.8527,10.48z
tags:
    - tag: climate justice
    - tag:  shade
    - tag:  climate comfort
    - tag:  
thumbnail-path: img/mapping-shade-rethinking-climate-comfort-in-upper-manhattan/lVUkpjQ.jpeg
img-folder: ../../img/mapping-shade-rethinking-climate-comfort-in-upper-manhattan/
timestamp: undefined
---
## Introduction

New York City is increasingly experiencing climate change impacts—rising temperatures, more frequent heatwaves, unpredictable storms, and intensified flooding. These shifts are not just environmental but also deeply social, disproportionately affecting vulnerable populations

Public infrastructure must evolve to address these challenges. From cooling centers to shaded public spaces, climate-relief infrastructures ensure safety, health, and well-being. As climate change accelerates and urban heat intensifies, public infrastructure must adapt to ensure equitable access to climate resilience.

![]({{ page.img-folder }}RmfvPci.png)

This project focuses on reevaluating public amenities in New York City, particularly in Upper Manhattan—a neighborhood ranked highest on the Heat Vulnerability Index (HVI). While current resources and initiatives address heat mitigation through cooling centers, green spaces, and hydration stations, one critical aspect of urban comfort is often overlooked: shade.

By mapping the availability (or lack) of shaded areas, this project highlights gaps in existing urban infrastructure that exacerbate heat exposure for vulnerable populations. Through a spatial analysis of public spaces, tree cover, and shade structures, this project aims to provide actionable insights for planners and policymakers to create a more inclusive, climate-adaptive public environment.

Through this exercise, this initiative envisions a future where shade is recognized as a fundamental component of climate comfort, advocating for equitable distribution of cooling resources in an increasingly warming city.

## Preliminary Research

Preliminary research for this project involved a detailed review of existing climate resources and their spatial distribution across New York City. Key datasets analyzed included Cool It! NYC cooling sites, NYC green infrastructure, the NYC tree census, cooling centers, parks properties, water features, and community gardens. This process was carried out in order to understand and identify the gaps in current climate-related infrastructural provisions, and to assess their spatial distribution.

![]({{ page.img-folder }}6NVDSym.png)

As is evident in the map above, while park properties, community gardens, and water features are widely distributed across the city, cooling sites were concentrated in neighborhoods identified as most vulnerable to heat. However, many of these cooling sites were reported as broken or inactive, rendering them ineffective, as shown in the Felt map.
 
[https://felt.com/map/Facilities-in-Heat-Vulnerable-Areas-copy-9CguvE9CD9BSuCDACPsV9BzcjA?loc=40.7315,-73.8499,10.83z](https://felt.com/map/Facilities-in-Heat-Vulnerable-Areas-copy-9CguvE9CD9BSuCDACPsV9BzcjA?loc=40.7315,-73.8499,10.83z)

Another important insight was that no available dataset exists for cooling centers, as the locations of these are released in the event of a heatwave. One map is available online, however the source data is not openly accessible (see: [https://finder.nyc.gov/coolingcenters/locations](https://finder.nyc.gov/coolingcenters/locations))

This finding necessitated a deeper investigation into the adequacy and reliability of cooling infrastructure. To understand the disparities further, the project examined how these resources align with socioeconomic indicators such as median household income and the presence of BIPOC (Black, Indigenous, and People of Color) populations.

![]({{ page.img-folder }}9W1Or7t.png)

![]({{ page.img-folder }}SdUc1FN.png)

As is shown in the maps above, neighborhoods with the lowest Median Household Income and the highest percentage of BIPOC populations overlap with the zipcodes that are ranked highest on the heat vulnerability index. Therefore, the evaluation of these resources raises two important questions:

What is the functionality of these resources?
What resources are missing?

For the purposes of this project, I focus on the second question, and in particular, look at one resource that is not recorded in any heat-management resources: built shade.

Here, I emphasize that shade is more than just a feature of urban landscapes—it is a vital civic resource, a marker of inequality, and a fundamental requirement for public health in an era of rising temperatures. As cities experience increasing heatwaves and the urban heat island effect exacerbates these conditions, access to shade becomes essential for protecting public health, particularly for vulnerable populations such as children, the elderly, and those with preexisting health conditions. Shade offers immediate thermal comfort, reduces heat-related illnesses, and lowers reliance on energy-intensive cooling systems like air conditioning, which many marginalized communities cannot afford.

At the same time, the distribution of shade—or lack thereof—reveals deep inequalities. Tree-lined streets, shaded parks, and well-designed urban canopies are often concentrated in wealthier areas, while underserved neighborhoods, often home to BIPOC communities, are left exposed to harsh sunlight and extreme heat. This disparity underscores how shade acts as an index of systemic inequality, pointing to broader issues of environmental injustice and urban neglect.


## Methodology

In order to respond to the gap identified in the preliminary research, this project focused on developing and analyzing a shade dataset in NYC. This research was conducted in upper Manhattan, more specifically East Harlem, because it is among the neighborhoods ranked highest on the heat vulnerability  index. In addition, this site was chosen because of ease of access, as the research process required frequent field visits. Below is a map establishing the context of upper Manhattan, focusing on resources associated with climate comfort.

![]({{ page.img-folder }}YbliPoJ.png)

An additional reason for selecting East Harlem specifically was that it was among the neighborhoods in Upper Manhattan with the least amount of tree coverage, according to the NYC tree census. This is demonstrated by the map below.

![]({{ page.img-folder }}21j6GkK.png)

The methodology for this project involved using feldpapers to create a base map of the area, serving as a canvas for annotating shading structures during field visits. These visits involved systematically identifying and documenting shading points, focusing on built (awnings, pergolas, bus shelters) structures. The locations were georeferenced using QGIS, which enabled precise spatial analysis. A custom dataset was developed to capture detailed attributes of each shading point, including type, material, condition, accessibility, ownership (public/private), permanence (temporary/permanent), and the presence of amenities like seating. High-resolution images were also collected to provide a visual record. In addition, tree canopy data from NYC OpenData was used to conduct a combined analysis of shade accessibility. 

## Analysis

The results of this process can be observed at the following interactive map:

[https://felt.com/map/Upper-Manhattan-Shade-Map-HehJhO3qQ2ODeyJq3FdBhC?loc=40.79811,-73.9316,14.51z](https://felt.com/map/Upper-Manhattan-Shade-Map-HehJhO3qQ2ODeyJq3FdBhC?loc=40.79811,-73.9316,14.51z)

This map explores the various shading structures that are observable across East Manhattan. Each point also gives information regarding of the shading structures such as their accessibility, ownership, materiality and more. Each map is also linked to an image of the observable structures. These points are superimposed over tree canopy coverage in upper Manhattan.

In addition, the  types and characteristics of shade in East Harlem can be explored using the donut chart below:

[https://classy-gaufre-aa27a6.netlify.app/](https://classy-gaufre-aa27a6.netlify.app/)

The visualization of this dataset reveals some curious findings. In particular, more than 50% of shade observable in East Harlem is categorized as scaffolding, which is neither intentional nor permanent. In addition, less than 30% of shading structures include seating. It is thus evident that street shade is not a resource that is intentionally considered or provided, rather, it is something that comes as a consequence of other built structures.

## Conclusion

The key suggestion from observable findings through this exercise is the need to create intentional shaded spaces in upper Manhattan, particularly East Harlem. Below is a map of vacant lots in the area that could be used for such purposes to alleviate impacts of rising temperatures in the city, particularly in heat vulnerable neighborhoods.

![]({{ page.img-folder }}UnyUReJ.png)

It would be useful, in addition to this, to create a buffered map of natural and built shade to identify vulnerable spots and identify vacant lots within those neighborhoods. That will be the direction this project continues in.


### Limitations & Next Steps

It is important to note that due to time and resource constraints, this project was conducted with several limitations. Firstly, this research was conducted during the winter months, which presented certain limitations in capturing the full spectrum of shading dynamics. Seasonal constraints restricted the exploration of ad-hoc shading structures such as umbrellas, market stalls, and temporary canopies, which are typically more prevalent during warmer months. Additionally, the study could not observe the occupancy patterns of shaded structures, leaving gaps in understanding their usage and social significance. The estimation of street area covered by shade relied on observational methods, which may introduce inaccuracies due to the absence of real-time solar positioning and shadow mapping. Time and resource constraints also limited the scope of data collection, resulting in a smaller sample size and reducing the ability to conduct repeated visits or longitudinal observations. Despite these challenges, the research provides a foundational understanding of shading infrastructure in East Harlem, offering valuable insights for future studies.

In order to expand the scope of this project, I imagine several future steps and directions that could be taken. For example, a comparative case study can be conducted between areas with varying rankings on the Heat Vulnerability Index (HVI) and differing demographic profiles to better understand how socioeconomic factors influence access to shade. Another comparative case study could examine the presence and utilization of ad-hoc shade structures across summer and winter months, capturing seasonal dynamics that were previously unobservable.

To improve spatial accuracy, I would also like to extend this project by tracing built shade coverage using lines and polygons, providing a more precise representation of shaded areas.

Additionally, the project could benefit from a crowd-sourced online component for the map, enabling community members to contribute real-time updates on shading structures, their condition, and usage patterns.

These steps will enhance the project’s depth and scalability, fostering community engagement and creating a more comprehensive resource for climate adaptation.
