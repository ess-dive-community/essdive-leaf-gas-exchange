## Guide to preparing supplementary metadata for leaf-level gas exchange data
Supplementary metadata tables should be provided to explain codes used in data tables used to describe samples and experimental variables. Supplementary metadata tables or text should also record additional experimental detail not recorded in the methodsMetadata template. 

Here are some typical examples of how to present these metadata. Tables should be included in data packages as .csv files.

### Species information example
**Metadata variable**|**Format**|**Description**|**Example**
-----|-----|-----|-----
speciesCode|Free text|Code used to identify species in data tables|JUOC
species |Free text|Full species name and subspecies if applicable|*Juniperus occidentalis*
genotype|Free text|Identified genotype or mutant| 
citation|Free text|Reference for species authority|Hook.

### Locations or plot details example
**Metadata variable**|**Format**|**Description**|**Example**
-----|-----|-----|-----
siteIdentifier|Free text|Plot or plant within this experiment for which position is being reported|Plot07
longitude|Decimal degrees|Longitude|-122.18877
latitude|Decimal degrees|Latitude|46.197905
elevation|Meters above sea level|Elevation of location|2155

### Additional metadata tables or text
The requirement for methods supplement tables or text documents will depend on the experimental setup. Where available and appropriate consider including the following information in a gas exchange data package: biome, ecosystem type, climate, local seasonality, timing of measurements relative to the growing season, data time zone and relationship with solar noon, environmental conditions at time of measurement, soil type, canopy exposure, canopy height and depth, terrain, aspect, seed provenance, genetic or cultivar details, pot size, leaf age classes, instrument configuration and measurement scripts.
