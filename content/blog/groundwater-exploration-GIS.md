+++
date = '2025-09-05T13:41:04+01:00'
draft = false
title = 'Groundwater Exploration Using GIS'
author = "Oluwafemi Adeyemo"
+++

# ABSTRACT 

A GIS-based study was carried out to assess the groundwater potentials of Ondo West Local Government Area of Southwestern Nigeria. Primary data (Landsat 8 Operational Land Imager and Shuttle Radar Topography Mission) and secondary data (geological map, soil map, and precipitation data) were utilized, leveraging on the use of Analytic Hierarchical Process (AHP) for pairwise comparison within the factors (Lineament density, Soil porosity, Lithology, Slope, Aspect, Land use and land cover classification, drainage density and Elevation).  Results show that the areas with high groundwater potential are within the central and northern parts, while the southern parts have low groundwater potentials. Using multicriteria Decision Analysis (MCDA), a groundwater potential map was produced and classified into low, moderate and high groundwater potential regions constituting 10%, 62%, and 28% of the study area respectively. This study is useful in groundwater exploration to meet one of the United Nations' Strategic Development Goals (Goal Six: Clean water and sanitation).

# MATERIALS AND METHODS


In this study, the Analytic Hierarchy Process (AHP) was employed to identify and delineate groundwater potential zones within the Ondo West Local Government Area, leveraging multiple thematic layers and expert-based weightings. The conditioning factors include lithology, slope, aspect, precipitation, soil porosity, lineament density, land use/land cover and drainage density.


# Data


This study utilized remote sensing data from multiple sensors and orbital paths to accurately model each of the considered phenomena.
Shuttle Radar Topography Missions’ Digital Elevation Model (DEM) of 30-meter resolution was processed to delineate the topographic characteristics of the terrain. With the aid of the Hydrology tool and Surface tool in the Spatial Analyst Tool in ArcMap 10.8, the DEM was processed to extract the drainage network, Slope and Aspect of the study area. 
Landsat 8 OLI captured on the 9th of February, 2024, along path 190 and row 055 was processed to extract surface information of the study area, such as Land use/land cover characteristics. Principal Component Analysis (PCA), an image enhancement technique, was applied to the Landsat 8 imagery to aid the extraction of lineaments on the surface. Lineaments were extracted image using PCI Geomatica 2015, using the enhanced image as the major input and complementary lineaments were extracted from the hillshade generated from the DEM. The line density tool in the Spatial Analyst Tool in ArcMap 10.8 was used to generate the lineament density and drainage density of the study area. 
Soil data extracted from the Digital World Soil Map (DWSM) and precipitation data acquired from Climate Hazards Group InfraRed Precipitation with Stations (CHIRPS) with a resolution of 0.05° were used. Specifically, the annual precipitation data v2.0.2023 was used for the purpose of this analysis.
All thematic layers representing conditioning factors were reclassified to assign values that depict the contribution of each class to groundwater accumulation. 


# METHODOLOGY


Multi-Criteria Decision Analysis and Analytic Hierarchical Process.
A major advantage of GIS is the ability to integrate multiple data sources in the same environment for improved decision-making. Multi-Criteria Decision Analysis is crucial in mapping groundwater potential zones, taking into account the various groundwater accumulation conditioning factors. The relevance of each conditioning factor is compared relatively using the Analytic Hierarchy Process. A total of 8 thematic layers were considered in the study, which include aspect, slope, drainage density, geology, lineament density, soil porosity and land use/land cover. Thematic layers were reclassified, assigning high values to classes that contribute positively to groundwater accumulation and lower values to classes with low contribution to groundwater accumulation. Saaty’s scale was used in the relative pairwise comparison of the conditioning factors, assigning values such as 
1, 3, 5, 7, and 9 in order of increasing importance


# RESULT

The weighted overlay tool in ArcMap 10.8 was used to integrate various parameters, utilising weights derived from a pairwise comparison of the Analytical Hierarchical Process (AHP). The output map shows regions with high, medium and low groundwater potential. The South-Western region and central region of the Ondo West Local Government Area have high groundwater potential, while the North-East region has low groundwater, mainly due to the urban land use class. 

 
{{< figure
src="/Result1.png"
align=center
title="Figure 4.13 Groundwater Potential Map"
>}}

{{< figure
src="/Result2.png"
align=center
title="Figure 4.14 Groundwater Potential Map"
>}}

{{< figure
src="/GWPmap.jpg"
align=center
title="Figure 4.15 Groundwater Potential Map"
>}}

Groundwater Potential Map


# DISCUSSION
The groundwater potential assessment conducted in Ondo West Local Government has a very significant in community development and resource management. The use of Remote sensing and GIS techniques has proven to be very effective in estimating the potential of regions, provided parameters that contribute to groundwater accumulation using multi-criteria decision analysis (MCDA). A groundwater potential map was created using a weighted overlay approach, generating an Analytic Hierarchical Process (AHP).
The distribution of groundwater potential zone, namely high, moderate and low, is 30.86% (291.467326 sq km), 64.37% (607.932525 sq. km) and 4.77% (45.011091 sq. km) respectively. Regions with low groundwater potential are associated with the urban land use class where different human activities such as cementation of the soil surface, and deforestation in process urbanization expose the soil to leaching and in return reduce the water holding capacity of the soil, excessive exploration of groundwater resources due to domestic and industrial needs will affect the accumulation and penetration of water into the soil.
 
![Figure 4.13 Groundwater Potential Map](GWPchart.jpg)
Figure 4.20: Distribution of Groundwater Potential Zones 

The low Groundwater potential zone also receives relatively lower rainfall than the other regions in the Ondo West Local Government Area. Regions with Moderate groundwater potential are the largest in the study area, taking 64.37% and are mainly located in the central region of the Local Government Area, receiving relatively higher rainfall than the Urban areas and covered by vegetation with higher lineament density and lower drainage density in comparison to the urban region. The region with high groundwater potential receives more precipitation than other regions and is covered by vegetation with very low drainage density and low elevation. These factors enhance groundwater accumulation and penetration of water into the groundwater systems.

# 5.0 SUMMARY AND CONCLUSION

# 5.1 Summary of Findings

There are a lot of findings discovered during the process of undertaking this project. Here are the significant findings;
i.	Understanding of the Terrain in Ondo West Local Government Area: This project has helped understand the terrain of the study area from the general distribution of rock outcrops, elevation variance across regions in the study area to more complex terrain specific analysis such as flow direction, flow accumulation, drainage system, stream order and drainage density of the area. 
ii.	Identification of Land Use and Land Cover classes and climatic conditions of regions within the study area: Some of the most influential parameters considered for the generation of groundwater potential maps include the Land use and land cover classification layer and precipitation data. This uncovers the relative distribution of rainfall and land uses, which greatly influence groundwater accumulation. 
iii.	Distribution of groundwater potential: The result obtained from this analysis has shown that a very large portion of the basement complex area has moderate to high groundwater potential. Regions with low groundwater potential are classified as urban areas and receive relatively lower amounts of rainfall annually. 


# 5.2 CONCLUSION

This groundwater potential assessment of Ondo West Local Government Area, utilising remote sensing data and GIS analysis, has provided valuable insights into the spatial distribution of groundwater resources in the region. By integrating multiple parameters, including land use/land cover (LULC), precipitation, soil characteristics and porosity, lineament density, and drainage density, we have developed a comprehensive understanding of the factors influencing groundwater occurrence and availability.
The Multi-Criteria Decision Analysis (MCDA) approach, coupled with the Analytic Hierarchy Process (AHP) for pairwise comparison, allowed for a systematic and objective evaluation of the relative importance of each parameter. This methodology enabled us to produce a groundwater potential map that classifies the study area into zones of low, moderate, and high groundwater potential.
The results reveal spatial variations in groundwater potential across Ondo West LGA, with distinct areas of high, moderate, and low potential identified. These findings have significant implications for water resource management, agricultural planning, and urban development in the region. Areas of high groundwater potential should be prioritised for sustainable groundwater exploitation, while areas of low potential may require alternative water supply strategies or more careful management of existing resources.
It is important to note that while this assessment provides a valuable overview of groundwater potential, site-specific investigations, including geophysical surveys and borehole data, should be conducted to verify the findings before any major groundwater development projects are undertaken. Additionally, regular monitoring and updating of this assessment will be crucial to account for changes in land use, climate, and other dynamic factors that may influence groundwater potential over time.
This study demonstrates the effectiveness of integrating remote sensing and GIS techniques with multi-criteria decision analysis for groundwater potential mapping. The methodology employed here can be adapted and applied to other regions, contributing to more informed and sustainable groundwater management practices.
Future research could focus on incorporating additional parameters, such as groundwater quality data, to further refine the assessment. Moreover, the integration of this groundwater potential map with socio-economic data could provide valuable insights for policymakers and planners in addressing water security challenges in Ondo West LGA and beyond.
In conclusion, this groundwater potential assessment serves as a crucial tool for sustainable water resource management in Ondo West LGA, providing a scientific basis for decision-making in water supply planning, agricultural development, and environmental conservation efforts.

