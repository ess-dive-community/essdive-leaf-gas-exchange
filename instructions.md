# Leaf-level gas exchange reporting format instructions

A data package containing leaf-level gas exchange data must include, at a minimum: 

1. Assemble the data table, using the defined [variableNames and variableUnits](docs/definedVariables.md). If the data is a described [data type](dataTypesProtocols.md) under this format, then the data table must include the [required variables](docs/requiredVariables.md) for that data type. Data tables may also include additional variables, and indicators of uncertainty if appropropriate. 

2. Collate the full instrument output files, and assess the quality control level. Note that there is no requirement to edit column headers in full instrument output files to standard variable names.  

3. Fill in the [Methods metadata template](templates/methodsMetadataTemplate.xlsx), ensuring that [required protocols](dataTypesProtocols.md) for each data type are described. See our [methods metadata guide](methodsMetadataGuide.md) for descriptions and instructions for each metadata field. Save as csv file type. A separate methods metadata file should be created for each data type included in the data package. 

4. Fill in the [Instrument details template](templates/instrumentDetailsTemplate.xlsx) and save as csv file type.

5. Prepare methods supplements tables to define codes used to capture sample characteristics in the data tables. See our [supplement metadata guide](docs/supplementaryMetadataGuide.md) for guidance. Save each file as csv file type.

## Additional information
Inclusion of additional related datasets with gas exchange data is encouraged. This can include measurements made inline, such as fluorescence or isotopic measurements, or subsequent analysis of chemical composition or physical properties. Related data should be linked by using common sample identifiers. 

Defined variables should be used where available. For variables not yet covered by this reporting format documentation, data contributors should use machine readable variable names that are in common use. 

We will continue to work with the ESS community to improve data and metadata reporting formats for leaf-level gas exchange data. Please [contribute](contribute.md) by submitting issues, using our issue templates, or contact ess-dive-support@lbl.gov to provide any feedback on the process of formatting data, specific metadata fields or controlled vocabulary terms.

## Example data package
Here is an example data package that follows these reporting format guidelines.

Rogers, Alistair, Kim Ely, Shawn Serbin. 2019. Leaf Photosynthetic Parameters: Quantum Yield, Convexity, Respiration, Gross CO2 Assimilation Rate and Raw Gas Exchange Data, Barrow, Alaska, 2016. *Next Generation Ecosystem Experiments Arctic Data Collection*, Oak Ridge National Laboratory, U.S. Department of Energy, Oak Ridge, Tennessee, USA. [doi.org/10.5440/1482338](https://doi.org/10.5440/1482338).
#
