## Prosumers 

### CustomerLoad
An EnergyConsumer is a generic user of energy - a  point of consumption on the power system model. 
According to IEC 61968-13, a MV  customer is a **CustomerLoad** and a LV customer is an **EquivalentLoad**.

### EquivalentLoad 
According to IEC 61970-301, an EnergyConsumer is a generic user of energy - a  point of consumption on the power system model. According to IEC 61968-13, a LV customer is an EquivalentLoad.
An EquivalentLoad has the attribute customerCount having its value greater than one to indicate the number of customers attached. The voltage level is specified by a voltage level that contains this EquivalentLoad.

### ElectricVehicle
An electric vehicle (EV) is a vehicle that uses one or more electric motors or traction motors for propulsion. An electric vehicle may be powered through a collector system by electricity from off-vehicle sources, or may be self-contained with a battery, solar panels, fuel cells or an electric generator to convert fuel to electricity. 

### MeterReading
Set of values obtained from the meter.

### UsagePoint
Logical or physical point in the network to which readings or events may be attributed. Used at the place where a physical or virtual meter may be located; however, it is not required that a meter be present.

### Distributed Energy Resource (DER)

To modeal a Distributed Energy Resource (DER) **CustomerLoad**, **SynchronousMachine** and **GeneratingUnit** can be used. When it consumes energy, the data will be taken from CustomerLoad. When it produces energy, data will come from SynchronousMachine and GeneratingUnit.

A DER can have two different contracts: Energy Consumption and Energy Generation. A DER can be a Voltage regulator. For a DER, we need to define its rated active Power and rated reactive Power. When P is positive, it is consuming energy. When P is negative, it acts as producing energy.