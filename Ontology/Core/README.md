## Core Package

Contains the core PowerSystemResource and ConductingEquipment entities shared by all applications plus common collections of those entities. Not all applications require all the Core entities.  This package does not depend on any other package except the Domain package, but most of the other packages have associations and generalizations that depend on it.

### ACDCTerminal
An electrical connection point (AC or DC) to a piece of conducting equipment. Terminals are connected at physical connection points called connectivity nodes.

### BaseVoltage
Defines a system base voltage which is referenced.

### Bay
A collection of power system resources (within a given substation) including conducting equipment, protection relays, measurements, and telemetry.  A bay typically represents a physical grouping related to modularization of equipment.

### ConductingEquipment
The parts of the AC power system that are designed to carry current or that are conductively connected through terminals.

### Equipment
The parts of a power system that are physical devices, electronic or mechanical.

### EquipmentContainer
A modeling construct to provide a root class for containing equipment.

### Location 
The class **Location** is used to define the absolute position of assets. The place, scene, or point of something where someone or something has been, is, and/or will be at a given moment in time. It can be defined with one or more position points (coordinates) in a given coordinate system.

### Substation
A collection of equipment for purposes other than generation or utilization, through which electric energy in bulk is passed for the purposes of switching or modifying its characteristics.

### Terminals
An AC electrical connection point to a piece of conducting equipment. Terminals are connected at physical connection points called connectivity nodes.

### VoltageLevel
A collection of equipment at one common system voltage forming a switchgear. The equipment typically consists of breakers, busbars, instrumentation, control, regulation and protection devices as well as assemblies of all these.
