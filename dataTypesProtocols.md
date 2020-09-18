# ESS-DIVE leaf gas exchange guide

---

## Data Type Content - Click on the Data Type you are using for more details

|data type       |
|:---------------|
|[Protocols for all data types](#Protocols-for-all-data-types)|
|[Survey](#survey)| 
|[Response of photosynthesis to intercellular CO2 concentration (ACi curves)](#Response-of-photosynthesis-to-intercellular-CO2-concentration)|
|[Photosynthetic parameters derived from ACi curves](#Photosynthetic-parameters-derived-from-ACi-curves) | 
|[Vcmax from one-point](#Vcmax-from-one-point) | 
|[Response of photosynthesis to irradiance (AQ curves)](#Response-of-photosynthesis-to-irradiance) | 
|[Photosynthetic parameters derived from AQ curves](#Photosynthetic-parameters-derived-from-AQ-curves) | 
|[Dark adapted respiration](#Dark-adapted-respiration)|

---

### Protocols for all data types
|data type                |Protocols for all data types|
|:------------------------|:----------------------------------------------------|
|**summary**              |measurementProtocols required for all data types|
|**description**          |The measurementProtocol elements listed in this row are required for all data types.|
|**requiredProtocols**    |The following should be included in the protocols for all data types. Stability criteria and minimum/maximum wait times. Leak testing and leak correction procedures. Handling of instrument bias and calibration. Details of instrument time used and UTC offset of location. Methods for calculating leaf temperature. Approach used if multiple leaves/leaflets/needles were in the chamber at the same time. |
|**references**           |NA|

### Survey
|data type                |Survey|
|:------------------------|:----------------------------------------------------|
|**summary**              |Single point measurement of leaf gas exchange.|
|**description**          |Survey measurements are typically a single measurement of the exchange of gases at a given point in time. Survey measurements can take many forms and be part of a sequence, e.g. measurement of gas exchange over a diurnal time course. Survey measurements might involve establishing chamber conditions that closely resemble ambient conditions and then taking a measurement as rapidly as possible after placing the leaf in the chamber. These type of measurements typically take less than 90 seconds and data are recorded as soon as the chamber has flushed. The goal is to measure prevailing gas fluxes. Alternatively, survey measurements can also be made under non-ambient conditions including under saturating irradiance and both saturating irradiance and saturating carbon dioxide concentration. Under some circumstances a survey measurement may include a period of stabilization to allow the leaf to acclimate to the chamber conditions set by the user.|
|**requiredProtocols**    |Where relevant, methods used to determine environmental condition set points (air temperature, relative humidity, VPD, irradiance, CO2 concentration). Measurement methods, including use of ambient or altered conditions, and how long leaf was in chamber prior to data collection. Indicate if reported values are single measurements or averaged values. |
|**references**           |Jarvis & Davies (1998), Rogers et al (2004), Halbritter et al (2020). |

### Response of photosynthesis to intercellular CO2 concentration
|data type                |Response of photosynthesis to intercellular CO2 concentration (ACi curves)|
|:------------------------|:----------------------------------------------------|
|**summary**              |A series of sequential measurements on a single leaf of leaf gas exchange with varying CO2 concentration.|
|**description**          |The response of photosynthesis to intercellular carbon dioxide concentration determined by measuring the response of photosynthesis to changes in chamber carbon dioxide concentrations at saturating irradiance and stable leaf temperature. Measurements are typically made after a stabilization period to achieve steady state gas exchange. An alternative approach where CO2 concentration is adjusted rapidly after no period of stabilization can also be used for some species (RACiR).|
|requiredProtocols**      |Time period of leaf acclimation to chamber conditions, and if steady state gas exchange was achieved. Irradiance used, if it is considered saturating and how saturating light levels were determined. Sequence and timing of CO2 concentration changes.|
|references**             |Long & Bernacchi (2003), Stinziano et al (2017)|

### Photosynthetic parameters derived from ACi curves
|data type                |Photosynthetic parameters derived from ACi curves |
|:------------------------|:----------------------------------------------------|
|**summary**              |Results of fitting photosynthetic CO2 response curves to derive parameters, e.g. apparent Vcmax, Jmax, TPU|
|**description**          |Results of fitting ACi curves to a photosynthesis model to derive parameters, e.g. apparent Vcmax, Jmax, TPU. Apparent Vcmax is calculated based on Ci (rather than Cc) and assumes an infinite mesophyll conductance to CO2.|
|**requiredProtocols**    |Method for fitting data (provide reference or code repository). Include kineticConstants and their temperature dependency in methodsMetadata.|
|**references**           |Bernacchi et al. (2013), Collatz (1992), von Caemmerer (2000), Dubois et al (2007), Duursma et al (2015), Farquhar et al (1980), Gu et al. (2010), Sharkey et al (2007), Zhou et al (2019)|

### Vcmax from one-point
|data type                |Vcmax from one-point|
|:------------------------|:----------------------------------------------------|
|**summary**              |Apparent Vcmax calculated from Asat measurements using the one-point method|
|**description**          |Results of calculating apparent Vcmax from Asat measurements using the one-point method.|
|**requiredProtocols**    |See details for Survey. Include kineticConstants in methodsMetadata.|
|**references**           |De Kauwe (2017), Corrigendum (2017), also see Burnett (2019).|

### Response of photosynthesis to irradiance
|data type                |Response of photosynthesis to irradiance (AQ curves)|
|:------------------------|:----------------------------------------------------|
|**summary**              |A series of sequential measurements on a single leaf of photosynthetic rate with varying irradiance|
|**description**          |The response of photosynthesis to irradiance determined by measuring the response of photosynthesis to changes in irradiance at constant leaf temperature and atmospheric CO2 concentration. Response curves can be measured slowly to allow full stomatal acclimation to each new level of irradiance (> 15 minutes at each step) or rapidly when the response of stomata is not of interest. To estimate Rlight a high number of points at low irradiance are required.   |
|**requiredProtocols**    |Time period of leaf acclimation to chamber conditions, and if steady state gas exchange was achieved. Sequence and timing of irradiance changes. Use of incident or absorbed light. State value used for leaf absorptance, if assumed or measured, and method if measured. Indicate if reported values are single measurements or averaged values. |
|**references**           |Posada et al (2009), Verryckt et al (2020)|

### Photosynthetic parameters derived from AQ curves
|data type                |Photosynthetic parameters derived from AQ curves |
|:------------------------|:----------------------------------------------------|
|**summary**              |Results of fitting AQ curves to derive parameters|
|**description**          |Results of fitting AQ curves to a photosynthesis model to derive parameters, e.g. quantum yield of CO2 fixation, light compensation point|
|**requiredProtocols**    |Method for fitting data (provide reference or code repository).|
|**references**           |Posada et al (2009)|

### Dark adapted respiration
|data type                |Dark adapted respiration|
|:------------------------|:----------------------------------------------------|
|**summary**              |Respiration rate of dark adapted leaf|
|**description**          |Respiration rate of dark adapted leaf|
|**requiredProtocols**    |Dark adaptation period. Time of measurement (day, night, pre-dawn). Measurement time period and number of data points used. Details of dark adaption, including which plant parts (leaf section, entire leaf, entire plant) and method (in cuvette, covered, at night). Flow rate used.|
|**references**           |Aspinwall et al (2016), Crous et al (2011)|
