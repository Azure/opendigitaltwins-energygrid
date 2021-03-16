# Distributed Energy Resource (DER)

For a Distributed Energy Resource (DER), we generate **CustomerLoad**, **SynchronousMachine** and **GeneratingUnit** to model it. When it consumes energy, we take data from CustomerLoad. When it produces energy, we take data from SynchronousMachine and GeneratingUnit.

A DER can have two different contracts: Energy Consumption and Energy Generation. A DER can be a Voltage regulator. For a DER, we need to define its rated active Power and rated reactive Power. When P is positive, it is consuming energy. When P is negative, it acts as producing energy.


