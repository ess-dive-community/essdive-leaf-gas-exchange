# Leaf-level Gas Exchange Methods Metadata Guide

This page provides guidelines and expectations for completion of the methods metadata template. Note that while defined vocabulary terms are suggested, most variables may be complete with free text entries if required.

The main purpose of this metadata collection will be to aid data search with some common discriminators. It is not meant to be a substitute for a complete experimental description. Additional information should be included as methods supplements tables, or in a methods text file. 


---  
## Methods Metadata Content - Click links below for more details

`*` indicate required content

[dataType*](#datatype) | 
[additionalDataIncluded*](#additionaldataincluded) | 
[instrumentOutputStatus*](#instrumentoutputstatus)

---

[photosyntheticPathway*](#photosyntheticpathway) | 
[plantType*](#planttype) | 
[leafType*](#leaftype) | 
[requiredProtocols*](#requiredprotocols)

---

[mesophyllConductanceType](#mesophyllconductancetype) | 
[leafStatus*](#leafstatus) | 
[leafAreaBasis*](#leafareabasis) 

---

[leafAreaMethod*](#leafareamethod)  | 
[kineticConstants](#kineticconstants) | 
[growthEnvironment*](#growthenvironment) 

---

[experimentalManipulation*](#experimentalmanipulation)  | 
[plantAge*](#plantage) | 
[leafAge*](#leafage)

---

[canopyPosition*](#canopyposition) | 
[canopyHeight*](#canopyheight) | 
[lightExposure*](#lightexposure)

---

### dataTypes
|**Metadata Element**|dataType|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required Recommended Optional**|`required`|
|**Description**|Enter data type described by this methods metadata file. Refer to data types in documentation for definitions. |
|**Format**|Controlled vocabulary or free text|
|**Additional Instructions**||
|**Controlled vocabulary terms**|Refer to data types table for list.|

### additionalDataIncluded
|**Metadata Element**|additionalDataIncluded|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required Recommended Optional**|`required`|
|**Description**|Indicate if additional data collected in-line during gas exchange is included. e.g. fluorescence, isotopic discrimination|
|**Format**|Controlled vocabulary|
|**Additional Instructions**||
|**Controlled vocabulary terms**|yes; no|

### instrumentOutputStatus
|**Metadata Element**|instrumentOutputStatus|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required Recommended Optional**|`required`|
|**Description**|Indicate the highest quality status of complete instrument output included in the data package. Multiple versions may be included. |
|**Format**|Controlled vocabulary|
|**Additional Instructions**|0 = data not available. 1 = direct instrument download, minimal quality control. 2 = complete quality control, files are verified to only contain valid data, or, invalid data is flagged. Measurement values are reasonable and within expected range. Area corrections are made where required. Time and dates verified as correct. User input errors corrected. |
|**Controlled vocabulary terms**|0; 1; 2|

---

### photosyntheticPathway
|**Metadata Element**|photosyntheticPathway|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Photosynthetic pathway of measured plants.|
|**Format**|Controlled vocabulary or free text|
|**Additional instructions**|List all that apply, use a semi-colon to delimit multiple terms.|
|Controlled vocabulary terms|C3; C4; CAM|

### plantType
|**Metadata Element**|planttType|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Describe the plant type(s) measured.|
|**Format**|Controlled vocabulary or free text|
|**Additional instructions**|List all that apply, use a semi-colon to delimit multiple terms.|
|Controlled vocabulary terms|C3; C4; CAM|

### leafType
|**Metadata Element**|leafType|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Describe the leaf type(s) measured.|
|**Format**|Controlled vocabulary or free text|
|**Additional instructions**|List all that apply, use a semi-colon to delimit multiple terms.|
|Controlled vocabulary terms|broadleaf; graminoid; needleleaf; phyllode|

### requiredProtocols
|**Metadata Element**|requiredProtocols|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Details of measurement protocols. Refer to requiredProtocols for each data type for required protocol information. Can cite reference or other source if this information is recorded elsewhere. |
|**Format**|Free text|
|**Additional instructions**||
|**Controlled vocabulary terms**||

---

### mesophyllConductanceType
|**Metadata Element**|mesophyllConductanceType|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`optional`|
|**Description**|Describe assumption or measurement of mesophyll conductance. Infinite mesophyll conductance assumes intercellular CO<sub>2</sub> concentration (C<sub>i</sub>) is equal to the CO<sub>2</sub> concentration at the site of carboxylation inside the chloroplast (C<sub>c</sub>).|
|**Format**|Controlled vocabulary|
|**Additional instructions**||
|**Controlled vocabulary terms**|assumed infinite; measured|

### leafStatus
|**Metadata Element**|leafStatus|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Describe the leaf status during gas exchange measurement.|
|**Format**|Controlled vocabulary or free text|
|**Additional instructions**|List all that apply, use a semi-colon to delimit multiple terms.|
|**Controlled vocabulary terms**|attached leaf; attached leaf on excised branch; excised leaf|

### leafAreaBasis
|**Metadata Element**|leafAreaBasis|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Describe the basis for measurement of leaf area. The default is "one-sided leaf area" which is typical for regular leaf types but there are several other alternatives, including in rare circumstances the use of mass or volume.|
|**Format**|Controlled vocabulary or free text|
|**Additional instructions**|List all that apply, use a semi-colon to delimit multiple terms.|
|**Controlled vocabulary terms**|one-sided area; hemi-surface area; projected area; total area; dry mass; volume|

---

### leafAreaMethod
|**Metadata Element**|leafAreaMethod|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Describe the methods used for measurement of leaf area. |
|**Format**|Controlled vocabulary or free text|
|**Additional instructions**|List all that apply, use a semi-colon to delimit multiple terms.|
|**Controlled vocabulary terms**|single leaf fills chamber of known area; multiple leaves fill chamber of known area; geometrically determined; calculated using imaging software; measured using leaf area meter|

### kineticConstants
|**Metadata Element**|kineticConstants|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`optional`|
|**Description**|Citations and values for kinetic constants, and their temperature dependance. |
|**Format**|Free text|
|**Additional instructions**||
|**Controlled vocabulary terms**||

### growthEnvironment
|**Metadata Element**|growthEnvironment|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Describe the plant growth environment. Provide details in Methods.|
|**Format**|Controlled vocabulary or free text|
|**Additional instructions**|List all that apply, use a semi-colon to delimit multiple terms.|
|**Controlled vocabulary terms**|natural in ground; cultivated in ground; potted; glasshouse; controlled environment chamber; other chamber type; hydroponic|

---

### experimentalManipulation
|**Metadata Element**|experimentalManipulation|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Indicate if any samples were subject to a manipulation. For naturally grown plants, or cultivated plants with standard fertilizer and pesticide application across all samples, select "none". Provide further treatment details in methodsSupplements tables. |
|**Format**|Controlled vocabulary or free text|
|**Additional instructions**|List all that apply, use a semi-colon to delimit multiple terms.|
|**Controlled vocabulary terms**|none; atmosphere; genetic; growth media; pesticide; light; nutrients; salinity; soil modification; source-sink; temperature; water availability|

### plantAge
|**Metadata Element**|plantAge|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Age in appropriate units (days, months, years) or relative age category (e.g. seedling, germling, sapling, mature) or other classification relevant to experiment. |
|**Format**|Controlled vocabulary or free text|
|**Additional instructions**|List all that apply, use a semi-colon to delimit multiple terms. Include a methods supplements table if required.|
|**Controlled vocabulary terms**|unknown; seedling; germling; sapling; mature|

### leafAge
|**Metadata Element**|leafAge|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Age in appropriate units (days, months, years) or relative age category (e.g. young, mature, old) or other classification (e.g. most recent fully expanded, physiologically mature leaf; LPI classification). |
|**Format**|Controlled vocabulary or free text|
|**Additional instructions**|List all that apply, use a semi-colon to delimit multiple terms. Include a methods supplements table if required.|
|**Controlled vocabulary terms**|young; mature; old; unknown; multiple ages|

---

### canopyPosition
|**Metadata Element**|canopyPosition|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Position of leaf samples within canopy. |
|**Format**|Controlled vocabulary or free text|
|**Additional instructions**|List all that apply, use a semi-colon to delimit multiple terms.|
|**Controlled vocabulary terms**|top of canopy; within canopy|

### canopyHeight
|**Metadata Element**|canopyHeight|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Sample canopy position and canopy height or LAI recorded.|
|**Format**|Controlled vocabulary|
|**Additional instructions**|If yes, provide details in metadata supplements and/or data tables.|
|**Controlled vocabulary terms**|yes; no|

### lightExposure
|**Metadata Element**|lightExposure|
|:----------------------------------------------------|:----------------------------------------------------|
|**Required, Recommended, or Optional**|`required`|
|**Description**|Light environment of leaf samples. |
|**Format**|Controlled vocabulary or free text|
|**Additional instructions**|List all that apply, use a semi-colon to delimit multiple terms.|
|**Controlled vocabulary terms**|sunlit; shade|
