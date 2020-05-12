---
layout: post
title:  "Glacier area delimiting"
date:   2020-05-12 
categories: [QGIS] [SEMI-AUTOMATIC CLASSIFICATION PLUGIN]
slug: "glacier"
---
One of my favorite memories while studying at UNIGIS was learning about remote sensing, its methods and its tools. While doing my degree, years ago, I barely studied this field, so I was gratefully surprised when I had the opportunity of learning all I could. A project related to this subject was the delimitation of the Maladeta Glacier in the summer of 2016, using [Landsat 8] imagery.

Making use of the Semi-Automatic Classification Plugin in QGIS, developed by the amazing [Luca Congedo],  I was able to identify the pixels in the image that represented the presence of snow, throught the Normalized Difference Snow Index (NDSI).

![NDSI](/static/projects/glaciar1.png){:class="img-responsive"}
 
After taking some ROIs, I got the spectral signature of the snow, water, soil, and vegetation, the last step before getting the whole classification of the image.

![Classification](/static/projects/p3.png){:class="img-responsive"}

[Landsat 8]: https://earthexplorer.usgs.gov/
[Luca Congedo]: https://fromgistors.blogspot.com/p/semi-automatic-classification-plugin.html


