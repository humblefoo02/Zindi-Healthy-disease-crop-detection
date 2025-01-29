# Zindi-Healthy-disease-crop-detection

zindi competition for cecking weather crop is deseased or healthy

Variable definations


FarmID
Description: Unique identifier of the farm.
Data Schema: Text

Crop
Description: Name of the crop corresponding to this observation.
Data Schema: Text

State
Description: Name of the state in which the farm is located.
Data Schema: Text

District
Description: Name of the district in which the farm is located.
Data Schema: Text

Sub-District
Description: Name of the sub-district or mandal in which the farm is located.
Data Schema: Text

SDate
Description: Sowing date of the crop, described in YYYY-MM-DD format, e.g., '2020-11-05'.
Data Schema: Text

HDate
Description: Harvest date of the crop, described in YYYY-MM-DD format, e.g., '2020-11-05'.
Data Schema: Text

CropCoveredArea
Description: Estimated percentage of the surface area covered with crop biomass.
Data Schema: Number
Unit Text: Percent

CHeight
Description: Height of the crop.
Data Schema: Number
Unit Text: Feet (ft)

CNext
Description: Name of the crop to be cultivated in the next season.
Data Schema: Text

CLast
Description: Name of the crop cultivated in the previous season.
Data Schema: Text

CTransp
Description: Condition or status of crop transpiration for the current observation.
Data Schema: Text

IrriType
Description: Type of irrigation method used, such as drip, sprinkler, surface, etc.
Data Schema: Text

IrriSource
Description: Source of irrigation, e.g., canal, borewell, rainfall, etc.
Data Schema: Text

IrriCount
Description: Total number of times the farm has been irrigated.
Data Schema: Number
Unit Text: Dimensionless

WaterCov
Description: Estimated percentage of the area covered with water due to irrigation.
Data Schema: Number
Unit Text: Percent

ExpYield
Description: Expected yield from the cultivated farm.
Data Schema: Number
Unit Text: Hundred weight (UK) per acre

Season
Description: Season in which the crop is cultivated.
Data Schema: Text

geometry
Description: Physical coordinates or spatial geometry of the farm location.
Data Schema: MultiPolygon

