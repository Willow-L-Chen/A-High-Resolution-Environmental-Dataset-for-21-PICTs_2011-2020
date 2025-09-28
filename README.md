# High-Resolution Climate and Vegetation Index Dataset for 21 Pacific Island Countries and Territories Derived from ERA5 and MODIS (2011-2020)

This dataset provides comprehensive weekly climate and vegetation data for 21 Pacific Island Countries and Territories (PICTs) spanning from 2011 to 2020. The dataset was specifically designed to support environmental and health research in small island developing states.

Spatial Coverage:
21 Pacific Island Countries and Territories including American Samoa, Cook Islands, Fiji, French Polynesia, Guam, Kiribati, Marshall Islands, Micronesia, Nauru, New Caledonia, Niue, Northern Mariana Islands, Palau, Papua New Guinea, Pitcairn Islands, Samoa, Solomon Islands, Tonga, Tuvalu, Vanuatu, and Wallis & Futuna.

Temporal Coverage:
Weekly data from 2011 to 2020 (52 weeks per year, 10 years total)

Data Variables:
- Temperature metrics: mean, maximum, and minimum weekly temperatures (°C)
- Precipitation data: average, total, minimum, and maximum weekly precipitation (mm)
- Vegetation indices: 8-day and processed NDVI values
- Land cover information

Data Sources and Processing:
- Climate data extracted from ECMWF ERA5 Daily Aggregates dataset via Google Earth Engine
- Vegetation data from MODIS MOD09A1.061 Terra Surface Reflectance 8-Day Global 500m
- City coordinates from Basic World Cities Database (v1.77)
- 1000m buffer zones applied around populated city centroids
- Population-weighted aggregation for each country
- NDVI data processed using Harmonic Analysis of Time Series (HANTS) smoothing algorithm

Applications:
This dataset is particularly valuable for:
- Climate change impact assessment in Pacific islands
- Environmental health research
- Epidemiological studies
- Agricultural and ecological modeling
- Climate trend analysis for small island developing states

File Format:
Excel format (.xlsx) with structured weekly time series data

Quality Assurance:
Data processed using established remote sensing and climatological methods with appropriate spatial and temporal aggregation for the unique geographic characteristics of Pacific Island nations.

CITATION:
Chen-Cao LW. High-Resolution Climate and Vegetation Index Dataset for 21 Pacific Island Countries and Territories Derived from ERA5 and MODIS (2011-2020). Zenodo; 2025. 
