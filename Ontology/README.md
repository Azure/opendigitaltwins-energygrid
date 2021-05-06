## Digital Twins Definition Language (DTDL) ontology for Energy Grid 

### Core 
 It contains the PowerSystemResource, ConductingEquipmen, and common collections of those entities shared by all applications. Most of the other packages have associations and generalizations that depend on the core package.

### Wire 
The wire package is an extension to the Core that provides model information detailing the electrical characteristics of transmission and distribution networks. This package is used by network applications, such as state estimation, load flow, and optimal power flow. 

### Generation 
It has information for unit commitment and economic dispatch of hydro and thermal generating units, load forecasting, automatic generation control, and unit modeling for training simulation. 

### Prosumer 
This folder has various entities related to consumer and DER in the prosumer folder. For examples, EquivalentLoad, UsagePoints, and MeterReading.