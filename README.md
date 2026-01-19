# Global analysis of everyday adaptation

This GitHub repository contains code for (Yücel et al., 2025), examining everyday adaptation to heatwaves at an international scale.

# Overview 
The steps presented in the repository are as follows:

|File                 |Description|
|---------------------|-----------|
|0.1_preprocess_temp/       |Pre-process temperature data to create daily maximum heat index|
|0.2_identify_heatwaves/       |Identify heatwaves from heat index, includes __detect_heatwaves.py based on code from Hobday et al. (2016)|
|0.3_identify_control_days/              |Implement control day algorithm|
|0.4_merge_mobility/      |Merge Google/Baidu mobility data and heatwave data across Brazil, China, France, India, Nigeria, Turkey, and United States|
|0.5_feature_eng/   |Construct social/physical then climatic/temperal variables for modelling, and create final data set|
|0.6_modeling/ |Use R2MlwiN (Zhang et al., 2016) to generate full models for each country|
|0.7_plotting/ |Concatenate final data sets, create marginal effects values, and make coefficient plots |
|data/ |Final data sets used in modelling for each country|


References:

> Yücel, S. G., Liang, Y., Wang, D. & Schwanen, T. (2025). Adapting everyday activities to summer heatwaves: A multi-country analysis of mobile phone location data.

> Hobday, A.J. et al. (2016), A hierarchical approach to defining marine heatwaves, Progress in Oceanography, 141, pp. 227-238. https://doi.org/10.1016/j.pocean.2015.12.014 

> Zhang, Z., Parker, R. M. A., Charlton, C. M. J., Leckie, G., & Browne, W. J. (2016). R2MLwiN: A Package to Run MLwiN from within R. Journal of Statistical Software, 72(10). https://doi.org/10.18637/jss.v072.i10

