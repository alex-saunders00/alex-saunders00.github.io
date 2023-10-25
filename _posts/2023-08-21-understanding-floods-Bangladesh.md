---
layout: post
title: Understanding flood risk in Bangladesh through satellites and machine learning
categories: [Floods, Machine Learning, Bangladesh]
---

Mapping floods is important for response, relief, preparedness, planning and mitigation. Satellites offer a more direct approach to mapping floods (than other approaches such as physical inundation models), and through advancements in satellite sensors and algorithms, satellite estimates of flooding are increasing in temporal frequency, spatial resolution and accuracy. 

In collaboration with the Bangladesh Institute of Water and Flood Management and the Bangladesh Flood Forecasting and Warning Centre, and funded by the NASA New Investigator Program _“Understanding flood risk in human altered landscapes from cities to farms: inferences from satellites and machine learning”_ led by P.I. Dr Beth Tellman, we are working to map maximum inundated area and quantify flood risk across the whole of Bangladesh. Comprehensive flood risk quantification can help to improve flood resilient land use and infrastructure planning, and support insurance and climate risk financing efforts.


### Devastating flooding in Sylhet, northeastern Bangladesh in 2022

In the second year of this project, the northeast of Bangladesh was hit by extreme floods, described as worse than previous catastrophic floods in 1988 and 2004. As agencies responded with maps of flooded areas for emergency relief and response, this proved an opportunity to evaluate and compare commonly employed flood mapping techniques in the case of a single, large-scale flood event. 


![sylhet flooding image](../images/sylhet_large.png "Sylhet flooding")
_Source: Getty images_


Our findings - [published](https://ieeexplore.ieee.org/document/10283378) in the conference proceedings to the Institute of Electrical and Electronics Engineers (IEEE) International Geoscience and Remote Sensing Symposium (IGARSS 2023) - show that:

* A “local” non-machine learning (ML) algorithm and a “global” ML (pre-trained CNN) produced equally high accuracy, showing that ML generalized well to this specific flood event (though may have benefitted from having been trained on data from another flood in Bangladesh).

* The recently launched Global Flood monitoring tool, a global automated near-real time emergency mapping service from the European Union Copernicus programme, showed lower accuracy, which may be a trade-off for its global coverage and ready-to-use publicly available flood maps.

* A deep-learning multi-sensor fusion of MODIS and Sentinel-1 successfully overcame challenges of persistent cloud cover which hamper MODIS-only algorithms, which is encouraging for the use of sensor fusion approaches more broadly.

You can view the slides presented at IGARSS 2023 [here](https://drive.google.com/file/d/1WzTTe189PvqW6jx2WFvjMq3vR3rCYu3J/view?usp=sharing).

