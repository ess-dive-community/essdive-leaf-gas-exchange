## Defined variables
This table shows variable names and units that should be used in data tables. Expected range values cover most plants for standard experimental conditions and may be used as a guide for quality checking.

**variableName**|**variableUnit**|**variableDescription**|**expectedValueRange**| 
-----|-----|-----|-----|-----
Instrument outputs| | |minimum|maximum
date|YYYY-MM-DD|Date of observation| | 
time|HH:MM:SS|Time of observation| | 
record|-|Observation record number| | 
area|cm²|Leaf area| | 
A|µmol m⁻² s⁻¹|Net CO2 exchange per leaf area|-20|120
Amax|µmol m⁻² s⁻¹|Highest rate of light and CO2 saturated A|-20|120
Asat |µmol m⁻² s⁻¹|Highest rate of light saturated A at ambient CO2 concentration|-20|120
Ci|µmol mol⁻¹|Intercellular CO2 concentration in air|0|5000
CO2r|µmol mol⁻¹|CO2 concentration in wet air entering chamber|0|5000
CO2s|µmol mol⁻¹|CO2 concentration in wet air inside chamber|0|5000
dCO2|µmol mol⁻¹|Sample minus reference CO2 concentration in air| | 
dH2O|mmol mol⁻¹|Sample minus reference H2O concentration in air| | 
E|mmol m⁻² s⁻¹|Transpiration rate of H2O per leaf area. Note that output units from some instruments are in mol and will require conversion.| | 
flow|µmol s⁻¹|Flow rate of air into chamber| | 
gbw|mmol m⁻² s⁻¹|Boundary layer conductance to water vapor per leaf area| | 
gsw|mmol m⁻² s⁻¹|Stomatal conductance to water vapor per leaf area|0|100
H2Or|mmol mol⁻¹|H2O concentration in air entering chamber| | 
H2Os|mmol mol⁻¹|H2O concentration in air inside chamber| | 
Patm|kPa|Atmospheric pressure|50|120
Qin|µmol m⁻²  s⁻¹|In-chamber photosynthetic flux density (PPFD) incident on the leaf, quanta per area|0|5000
Qout|µmol m⁻² s⁻¹|External photosynthetic flux density (PPFD), quanta per area|0|5000
RHr|%|Relative humidity of air entering the chamber|0|100
RHs|%|Relative humidity of air inside the chamber|0|100
Tair|°C|Air temperature inside the chamber|-20|70
Tleaf|°C|Leaf surface temperature|-20|70
VPDleaf|kPa|Leaf to air vapor pressure deficit |0|5
 | | | | 
Calculated parameters| | | | 
AsatG|µmol m⁻² s⁻¹|Maximum rate of gross CO2 assimilation derived from the light response curve. Equivalent to total of CO2 assimilation and CO2 release.| | 
CE|mol m⁻² s⁻¹|Maximum carboxylation efficiency, based on an empirical determination of the initial slope of an A-Ci curve| | 
CiCa|-|Ratio of intercellular CO2 to sample chamber CO2| | 
CO2comp|µmol mol⁻¹|CO2 compensation point| | 
gm|mol m⁻² s⁻¹|Mesophyll conductance to CO2 per leaf area| | 
J|µmol m⁻² s⁻¹|Rate of electron transport per leaf area at measurement temperature calculated assuming infinite mesophyll conductance for a given irradiance e.g. J1800. Or at reference temperature e.g., J1800,25|0|600
Jmax|µmol m⁻² s⁻¹|Maximum rate of electron transport per leaf area at measurement temperature calculated assuming infinite mesophyll conductance and saturating light|0|600
Jmax25|µmol m⁻² s⁻¹|Maximum rate of electron transport per leaf area, at the reference temperature 25 degrees Celcius calculated assuming infinite mesophyll conductance and saturating light|0|600
LCP|µmol m⁻²  s⁻¹|Light compensation point. The lowest photosynthetic photon flux density at which positive net CO2 assimilation is observed| | 
LSP|µmol m⁻²  s⁻¹|Light saturation point. The irradiance at which further increases in irradiance level do not increase net CO2 assimilation rate.| | 
PhiCO2a|mol mol⁻¹|Maximum quantum yield of CO2 assimilation based on absorbed irradiance| | 
PhiCO2i|mol mol⁻¹|Maximum quantum yield of CO2 assimilation based on incident irradiance| | 
PhiJa|mol mol⁻¹|Maximum quantum yield of electron transport based on arbsorbed irradiance| | 
PhiJi|mol mol⁻¹|Maximum quantum yield of electron transport based on incident irradiance| | 
Rdark|µmol m⁻² s⁻¹|CO2 release from the leaf in the dark, at measurement temperature, reported as a positive value| | 
Rdark25|µmol m⁻² s⁻¹|CO2 release from the leaf in the dark, at the reference temperature of 25 degrees Celcius, reported as a positive value| | 
Rday|µmol m⁻² s⁻¹|CO2 release from the leaf in the light, reported as a positive value| | 
Rday25|µmol m⁻² s⁻¹|CO2 release from the leaf in the light, at the reference temperature of 25 degrees Celcius, reported as a positive value.| | 
Theta|-|Empirical convexity parameter derived from the non-rectangular hyperbolic model of the light response curve| | 
TPU|µmol m⁻² s⁻¹|Triose phosphate utilization rate per leaf area at measurement temperature| | 
TPU25|µmol m⁻² s⁻¹|Triose phosphate utilization rate per leaf area at the reference temperature 25 degrees Celcius| | 
Vcmax|µmol m⁻² s⁻¹|Maximum rate of carboxylation at measurement temperature, calculated assuming infinite mesophyll conductance, i.e. apparent Vcmax|0|500
Vcmax25|µmol m⁻² s⁻¹|Maximum rate of carboxylation, at the reference temperature 25 degrees Celcius, calculated assuming infinite mesophyl conductance, i.e. apparent Vcmax|0|500
Vpmax|µmol m⁻² s⁻¹|Phosphoenolpyruvate (PEP) saturated PEP carboxylation at measurement temperature| | 
WUEi|µmol mol⁻¹|Intrinsic water use efficiency. Net CO2 exchange per leaf area divided by stomatal conductance to water vapor per leaf area| | 
 | | | | 
Constants| | | | 
Alpha|-|Leaf absorptance of visible radiation (400-730 nm)|0|1
EaGammaStar|kJ mol⁻¹|Activation energy associated with the temperature response of gammaStar| | 
EaKc|kJ mol⁻¹|Activation energy associated with the temperature response of Kc| | 
EaKo|kJ mol⁻¹|Activation energy associated with the temperature response of Ko| | 
EaVcmax|kJ mol⁻¹|Activation energy associated with the temperature response of Vcmax| | 
EaVomax|kJ mol⁻¹|Activation energy associated with the temperature response of Vomax, the maximum rate of oxygenation| | 
f|-|Fraction of light absorbed by photosystem II that is not used for photochemistry| | 
gammaStar25|µmol mol⁻¹|CO2 compensation point in the absence of non-photorespiratory CO2 release at the reference temperature of 25 degrees Celcius| | 
Kc25|µmol mol⁻¹|Michaelis constant for CO2 concentration in air at the reference temperature of 25 degrees Celcius| | 
Ko25|mmol mol⁻¹|Michaelis constant for O2 concentration in air at the reference temperature of 25 degrees Celcius| | 
Oi|mmol mol⁻¹|Intercellular O2 concentration in air (default 210 unless experimentally manipulated)| | 
Tau25|-|CO2:O2 specificity ratio at a reference temperature of 25 degrees Celcius| | 
TauQ10|-|Q10 temperature response parameter used to scale Tau25 | | 
