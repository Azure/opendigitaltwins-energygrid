# GeneratingUnit 

A single or set of synchronous machines for converting mechanical power into alternating-current power. For example, individual machines within a set may be defined for scheduling purposes while a single control signal is derived for the set. In this case there would be a GeneratingUnit for each member of the set and an additional GeneratingUnit corresponding to the set.

In most distribution networks, embedded generation is not intended to supply all load and can only operate while there is also a transmission source of supply. Thus embedded generators should be modeled as generators and not as an equivalent source. The output of an embedded generator may be specified by a curve and it may be specified as a P,Q schedule or a P,V schedule[5].

Note that in the case of a P,Q generator it is also acceptable to model it simply as a negative load, Connectivity Nodes and Terminals.

Connectivity Nodes and Terminal classes of the CIM topological model are used to describe the connectivity model. GeneratingUnit.initalMW is used to represent normal Active power (P).