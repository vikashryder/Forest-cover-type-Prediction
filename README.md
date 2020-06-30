Forest Cover Type Prediction


### Data Set Information:

Predicting forest cover type from cartographic variables only (no remotely sensed data). The actual forest cover type for a given observation (30 x 30 meter cell) was determined from US Forest Service (USFS) Region 2 Resource Information System (RIS) data. Independent variables were derived from data originally obtained from US Geological Survey (USGS) and USFS data. Data is in raw form (not scaled) and contains binary (0 or 1) columns of data for qualitative independent variables (wilderness areas and soil types).

This study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. These areas represent forests with minimal human-caused disturbances, so that existing forest cover types are more a result of ecological processes rather than forest management practices.

Some background information for these four wilderness areas: Neota (area 2) probably has the highest mean elevational value of the 4 wilderness areas. Rawah (area 1) and Comanche Peak (area 3) would have a lower mean elevational value, while Cache la Poudre (area 4) would have the lowest mean elevational value.

As for primary major tree species in these areas, Neota would have spruce/fir (type 1), while Rawah and Comanche Peak would probably have lodgepole pine (type 2) as their primary species, followed by spruce/fir and aspen (type 5). Cache la Poudre would tend to have Ponderosa pine (type 3), Douglas-fir (type 6), and cottonwood/willow (type 4).

The Rawah and Comanche Peak areas would tend to be more typical of the overall dataset than either the Neota or Cache la Poudre, due to their assortment of tree species and range of predictive variable values (elevation, etc.) Cache la Poudre would probably be more unique than the others, due to its relatively low elevation range and species composition.


### Details Remarks:

	Data Set Characteristics	Multivariate
	Attribute Characteristics	Categorical, Integer
	Associated Tasks		Classification
	Number of Instances		581011
	Number of Attributes		54
	Missing Values			No
	Area				Life
	Date Donated			1998-08-01 00:00:00
	Number of Web Hits		258008


### Attribute Information:

Given is the attribute name, attribute type, the measurement unit and a brief description. The forest cover type is the classification problem. The order of this listing corresponds to the order of numerals along the rows of the database. 

In regards to the number of attributes, we have 12 measurements spread out over 54 columns of data. Ten are quantitative variables, four binary are wilderness areas, and 40 binary are soil type variables.

You can find more information about the data [here](https://archive.ics.uci.edu/ml/machine-learning-databases/covtype/covtype.info).

This dataset is part of the UCI Machine Learning Repository, and the original source can be found [here](https://archive.ics.uci.edu/ml/datasets/Covertype). The original database owners are Jock A. Blackard, Dr. Denis J. Dean, and Dr. Charles W. Anderson of the Remote Sensing and GIS Program at Colorado State University.

	The dataset has 54 features and 1 target variable `Cover_Type`.
	
	From the 54 features, 10 are numerical and 44 are categorical.
	
	From the categorical data 4 are of `Wilderness_Area` and 40 are of `Soil_Type`

### Categorical Data

With the informations from UCI, we know the correct names of all `Soil_Types` and `Wilderness_Areas`. See table below.

We will keep the current feature naming, but might take a closer look later if necessary.

### Target Variable

The target variable `Cover_Type` is of type integer and ranges from `1` and `7` and representes a type of tree, eg. Douglas-Fir.

	Spruce/Fir
	Lodgepole Pine
	Ponderosa Pine
	Cottonwood/Willow
	Aspen
	Douglas-fir
	Krummholz


**Problem Statement:**
* The purpose of this Project is to predict forest cover type from cartographic variables only.
* Given elevation, hydrology, soil type and Hillshade data can we predict what type of trees would be in a small patch of forest?
* Our project attempts to predict the predominant type of tree in sections of wooded area. 
* Understanding forest composition is a valuable aspect of managing the health and vitality of wilderness areas. Classifying cover type can help further research regarding forest fire susceptibility, the spread of the Mountain Pine Beetle infestation and de/reforestation concerns.
* In this report, we aim to predict forest cover type using cartographic data and a variety of classification algorithms.


**Business Uses:** 
1. Medical purpose to get ideas about type of Flora / Fauna in each Cover type.
2. Furniture factories to get ideas about type of Flora in each Cover type.
3. Government purpose - Areas can be used / Coverage in every Cover type.
4. Suitable Wildlife Sanctuary in every Cover type.
5. Cultivation / Non-Cultivation area in every Cover type.

Author @vikashryder