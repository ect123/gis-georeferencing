---
layout: default
title: Hands On
nav_order: 3
has_children: true
---

# Georeferencing Overview

In this section you will georeference a historical map of Vancouver with QGIS. The map is one from UBC Library's physical collection. A high quality scan has already been made. This will be your **Source Layer**. You will also need a **Target Layer**, a geospatial data layer which will serve as reference for assigning locative information to the Source Layer. Download **and unzip** the workshop project folder, including the historical map and reference data below.   

[Download Data](){: .btn .btn-purple }
 
When georeferencing within a Geographic Information System (GIS) like QGIS, the basic workflow is as follows

1. Load Target Layer into GIS and set project coordinate reference system 
2. Load Source Layer as high resolution image (filetype .tiff) 
3. Match a handful of points on the Source Layer to those on the Target Layer, thus appending locative information to the Source Layer 

The points matched between the two layers are called **Ground Control Points (GCPs)**. When choosing a map to georeference (Source Layer) and a geospatial reference layer (Target Layer), it is important to ensure there are clear GCPs. GCPs may be physical geographic features, such as river bends, coastlines, or lake boundaries. GCPs may be infrastructural features such as the intersection of two roads or political boundaries or meridian lines. In any case, it is important to consider whether the geographic location of a potential GCP may have changed in the time since the historical map was rendered. These changes will matter more or less depending on the scale of the Source Layer. For instance, if the goal is to georeference a map of lower British Columbia, the exact bends of the Fraser River are less important than it's general location. The Fraser River could therefore be used as a reference to match the Source to Target Layer. 
 

Most likely your GCPs will be mix of features. 

Why we've chosen this map and what GCPs... 


