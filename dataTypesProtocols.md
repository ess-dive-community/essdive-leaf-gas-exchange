# Guide to data types and required protocol details 

---

## Data Type Content - Click on the Data Type you are using for more details

|data type       |
|:---------------|
|[Protocols for all data types](#protocols-for-all-data-types)|
|[Survey](#survey)| 
|[Response of photosynthesis to intercellular CO&#8322; concentration (ACi curves)](#response-of-photosynthesis-to-intercellular-co-concentration-aci-curves)|
|[Photosynthetic parameters derived from ACi curves](#photosynthetic-parameters-derived-from-ACi-curves) | 
|[Vcmax from one-point](#vcmax-from-one-point) | 
|[Response of photosynthesis to irradiance (AQ curves)](#response-of-photosynthesis-to-irradiance) | 
|[Photosynthetic parameters derived from AQ curves](#photosynthetic-parameters-derived-from-aq-curves) | 
|[Dark adapted respiration](#dark-adapted-respiration)|

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
|**requiredProtocols**    |Where relevant, methods used to determine environmental condition set points (air temperature, relative humidity, VPD, irradiance, CO&#8322; concentration). Measurement methods, including use of ambient or altered conditions, and how long leaf was in chamber prior to data collection. Indicate if reported values are single measurements or averaged values. |
|**references**           |Jarvis & Davies (1998), Rogers et al (2004), Halbritter et al (2020). |

### Response of photosynthesis to intercellular CO&#8322; concentration (ACi curves)
|data type                |Response of photosynthesis to intercellular CO&#8322; concentration (ACi curves)|
|:------------------------|:----------------------------------------------------|
|**summary**              |Sequential measurements on a the same leaf material of leaf gas exchange with varying CO&#8322; concentration.|
|**description**          |The response of photosynthesis to intercellular carbon dioxide concentration determined by measuring the response of photosynthesis to changes in chamber carbon dioxide concentrations at saturating irradiance and stable leaf temperature. Measurements are typically made after a stabilization period to achieve steady state gas exchange. An alternative approach where CO&#8322; concentration is adjusted rapidly after no period of stabilization can also be used for some species (RACiR).|
|**requiredProtocols**      |Time period of leaf acclimation to chamber conditions, and if steady state gas exchange was achieved. Irradiance used, if it is considered saturating and how saturating light levels were determined. Sequence and timing of CO&#8322; concentration changes.|
|**references**             |Long & Bernacchi (2003), Stinziano et al (2017)|

### Photosynthetic parameters derived from *ACi* curves
|data type                |Photosynthetic parameters derived from ACi curves |
|:------------------------|:----------------------------------------------------|
|**summary**              |Results of fitting photosynthetic CO&#8322; response curves to derive parameters, e.g. apparent *Vcmax, Jmax, TPU*|
|**description**          |Results of fitting *ACi* curves to a photosynthesis model to derive parameters, e.g. apparent *Vcmax, Jmax, TPU*. Apparent *Vcmax* is calculated based on *Ci* (rather than *Cc*) and assumes an infinite mesophyll conductance to CO&#8322;.|
|**requiredProtocols**    |Method for fitting data (provide reference or code repository). Include kineticConstants and their temperature dependency in methodsMetadata.|
|**references**           |Bernacchi et al. (2013), Collatz (1992), von Caemmerer (2000), Dubois et al (2007), Duursma et al (2015), Farquhar et al (1980), Gu et al. (2010), Sharkey et al (2007), Zhou et al (2019)|

### Vcmax from one-point
|data type                |Vcmax from one-point|
|:------------------------|:----------------------------------------------------|
|**summary**              |Apparent *Vcmax* calculated from *Asat* measurements using the one-point method|
|**description**          |Results of calculating apparent *Vcmax* from *Asat* measurements using the one-point method.|
|**requiredProtocols**    |See details for Survey. Include kineticConstants in methodsMetadata.|
|**references**           |De Kauwe (2017), Corrigendum (2017), also see Burnett (2019).|

### Response of photosynthesis to irradiance
|data type                |Response of photosynthesis to irradiance (*AQ* curves)|
|:------------------------|:----------------------------------------------------|
|**summary**              |Sequential measurements on the same leaf material of photosynthetic rate with varying irradiance|
|**description**          |The response of photosynthesis to irradiance determined by measuring the response of photosynthesis to changes in irradiance at constant leaf temperature and atmospheric CO&#8322; concentration. Response curves can be measured slowly to allow full stomatal acclimation to each new level of irradiance (> 15 minutes at each step) or rapidly when the response of stomata is not of interest. To estimate Rlight a high number of points at low irradiance are required.   |
|**requiredProtocols**    |Time period of leaf acclimation to chamber conditions, and if steady state gas exchange was achieved. Sequence and timing of irradiance changes. Use of incident or absorbed light. State value used for leaf absorptance, if assumed or measured, and method if measured. Indicate if reported values are single measurements or averaged values. |
|**references**           |Posada et al (2009), Verryckt et al (2020)|

### Photosynthetic parameters derived from *AQ* curves
|data type                |Photosynthetic parameters derived from *AQ* curves |
|:------------------------|:----------------------------------------------------|
|**summary**              |Results of fitting light response curves to derive parameters|
|**description**          |Results of fitting light response curves to a photosynthesis model to derive parameters, e.g. quantum yield of CO&#8322; fixation, light compensation point|
|**requiredProtocols**    |Method for fitting data (provide reference or code repository).|
|**references**           |Posada et al (2009)|

### Dark adapted respiration
|data type                |Dark adapted respiration|
|:------------------------|:----------------------------------------------------|
|**summary**              |Respiration rate of dark adapted leaf|
|**description**          |Respiration rate of dark adapted leaf|
|**requiredProtocols**    |Dark adaptation period. Time of measurement (day, night, pre-dawn). Measurement time period and number of data points used. Details of dark adaption, including which plant parts (leaf section, entire leaf, entire plant) and method (in cuvette, covered, at night). Flow rate used.|
|**references**           |Aspinwall et al (2016), Crous et al (2011)|


## References
Aspinwall MJ, Drake JE, Campany C, Varhammar A, Ghannoum O, Tissue DT, Reich PB, Tjoelker MG. (2016). Convergent acclimation of leaf photosynthesis and respiration to prevailing ambient temperatures under current and warmer climates in Eucalyptus tereticornis. New Phytologist, 212, 354-367.	

Bernacchi, C. J., Bagley, J. E., Serbin, S. P., Ruiz-Vera, U. M., Rosenthal, D. M., & Vanloocke, A. (2013). Modelling C3photosynthesis from the chloroplast to the ecosystem. In Plant, Cell & Environment (Vol. 36, Issue 9, pp. 1641–1657). https://doi.org/10.1111/pce.12118			

Burnett, A. C., Davidson, K. J., Serbin, S. P., & Rogers, A. (2019). The “one‐point method” for estimating maximum carboxylation capacity of photosynthesis: A cautionary tale. In Plant, Cell & Environment (Vol. 42, Issue 8, pp. 2472–2481). https://doi.org/10.1111/pce.13574	

Collatz GJ, Ribas-Carbo M, Berry JA (1992) Coupled photosynthesis - stomatal conductance model for leaves of C4 plants. Australian Journal of Plant Physiology, 19, 519-538.	

Corrigendum. (2017). The New Phytologist, 213(3), 1555.	

Crous, K. Y., Zaragoza-Castells, J., Löw, M., Ellsworth, D. S., Tissue, D. T., Tjoelker, M. G., Barton, C. V. M., Gimeno, T. E., & Atkin, O. K. (2011). Seasonal acclimation of leaf respiration in Eucalyptus saligna trees: impacts of elevated atmospheric CO&#8322;> and summer drought. In Global Change Biology (Vol. 17, Issue 4, pp. 1560–1576). https://doi.org/10.1111/j.1365-2486.2010.02325.x			

De Kauwe, M. G., Lin, Y.-S., Wright, I. J., Medlyn, B. E., Crous, K. Y., Ellsworth, D. S., Maire, V., Prentice, I. C., Atkin, O. K., Rogers, A., Niinemets, Ü., Serbin, S. P., Meir, P., Uddling, J., Togashi, H. F., Tarvainen, L., Weerasinghe, L. K., Evans, B. J., Ishida, F. Y., & Domingues, T. F. (2016). A test of the “one-point method” for estimating maximum carboxylation capacity from field-measured, light-saturated photosynthesis. The New Phytologist, 210(3), 1130–1144.			

Dubois, J.-J. B., Fiscus, E. L., Booker, F. L., Flowers, M. D., & Reid, C. D. (2007). Optimizing the statistical estimation of the parameters of the Farquhar-von Caemmerer-Berry model of photosynthesis. The New Phytologist, 176(2), 402–414.	

Farquhar, G. D., von Caemmerer, S., & Berry, J. A. (1980). A biochemical model of photosynthetic CO&#8322; assimilation in leaves of C3 species. In Planta (Vol. 149, Issue 1, pp. 78–90). https://doi.org/10.1007/bf00386231			

Gu, L., Pallardy, S. G., Tu, K., Law, B. E., & Wullschleger, S. D. (2010). Reliable estimation of biochemical parameters from C3 leaf photosynthesis-intercellular carbon dioxide response curves. In Plant, Cell & Environment (Vol. 33, Issue 11, pp. 1852–1874). https://doi.org/10.1111/j.1365-3040.2010.02192.x		

Halbritter, A., De Boeck, H., Vandvik, V., & Amy E. Eycott Sabine Reinsch David A. Robinson Sara Vicca Bernd Berauer Casper T. Christiansen Marc Estiarte José M. Grünzweig Ragnhild Gya Karin Hansen Anke Jentsch Hanna Lee Sune Linder John Marshall Josep Peñuelas Inger Kappel Schmidt E. (2020). The handbook for standardized field and laboratory measurements in terrestrial climate change experiments and observational studies (ClimEx). https://doi.org/10.5194/egusphere-egu2020-16136			

Jarvis, A. J., & Davies, W. J. (1998). The coupled response of stomatal conductance to photosynthesis and transpiration. In Journal of Experimental Botany (Vol. 49, Issue Special, pp. 399–406). https://doi.org/10.1093/jxb/49.special_issue.399		

Long, S. P., & Bernacchi, C. J. (2003). Gas exchange measurements, what can they tell us about the underlying limitations to photosynthesis? Procedures and sources of error. Journal of Experimental Botany, 54(392), 2393–2401.			

Posada, J. M., Lechowicz, M. J., & Kitajima, K. (2009). Optimal photosynthetic use of light by tropical tree crowns achieved by adjustment of individual leaf angles and nitrogen content. Annals of Botany, 103(5), 795–805.			

Rogers, A., Allen, D. J., Davey, P. A., Morgan, P. B., Ainsworth, E. A., Bernacchi, C. J., Cornic, G., Dermody, O., Dohleman, F. G., Heaton, E. A., Mahoney, J., Zhu, X.-G., Delucia, E. H., Ort, D. R., & Long, S. P. (2004). Leaf photosynthesis and carbohydrate dynamics of soybeans grown throughout their life-cycle under Free-Air Carbon dioxide Enrichment. Plant, Cell and Environment (Vol. 27, Issue 4, pp. 449–458). https://doi.org/10.1111/j.1365-3040.2004.01163.x			

Sharkey, T. D., Bernacchi, C. J., Farquhar, G. D., & Singsaas, E. L. (2007). Fitting photosynthetic carbon dioxide response curves for C3leaves. In Plant, Cell & Environment (Vol. 30, Issue 9, pp. 1035–1040). https://doi.org/10.1111/j.1365-3040.2007.01710.x		

Stinziano, J. R., Morgan, P. B., Lynch, D. J., Saathoff, A. J., McDermitt, D. K., and Hanson, D. T. (2017) The rapid A–Ci response: photosynthesis in the phenomic era. Plant Cell & Environment, 40: 1256– 1262. doi: 10.1111/pce.12911.			

Verryckt, LT, Ellsworth, DS, Vicca, S, et al. Can light‐saturated photosynthesis in lowland tropical forests be estimated by one light level?. Biotropica. 2020; 00: 1– 11. https://doi.org/10.1111/btp.12817			

Von Caemmerer, S. (2000). Biochemical models of leaf photosynthesis. Clayton: CSIRO Publishing.			
