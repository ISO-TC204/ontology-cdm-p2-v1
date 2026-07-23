# Information technology - City data model - Part 2: City level concepts - Transport Infrastructure pattern

This ontology specifies the city-level concepts for the transport infrastructure pattern of the city data model. The Transportation Infrastructure pattern defines the concepts that are relevant in describing the physical transportation infrastructure and their characteristics. This includes the concepts of a Road, Bridge, and Tunnel. The Infrastructure Pattern is reused here, as these transportation structures are all defined as types of (subclasses) Infrastructure Elements.

This pattern imports the following files:

- [https://w3id.org/citydata/part2/v1/InfrastructurePattern](https://w3id.org/citydata/part2/v1/InfrastructurePattern)

This pattern consists of the following classes:

- [Bridge](Bridge.md)
- [Bridge Segment](BridgeSegment.md)
- [Rail Line](RailLine.md)
- [Rail Link](RailLink.md)
- [Rail Segment](RailSegment.md)
- [Road](Road.md)
- [Road Link](RoadLink.md)
- [Road Network Type](RoadNetworkType.md)
- [Road Segment](RoadSegment.md)
- [Transport Infrastructure Thing](TransportInfrastructureThing.md)
- [Travelled Way](TravelledWay.md)
- [Travelled Way Link](TravelledWayLink.md)
- [Travelled Way Segment](TravelledWaySegment.md)
- [Tunnel](Tunnel.md)
- [Tunnel Segment](TunnelSegment.md)
This module defines the following properties:

- [networkType](../properties/networkType.md)
- [supports](../properties/supports.md)
- [TransportInfrastructureObjectProperty](../properties/TransportInfrastructureObjectProperty.md)


The formal definition of this pattern is available in TURTLE Syntax in two files, the [core semantics](../TransportInfrastructurePattern.ttl) and the SHACL [restrictions](../TransportInfrastructureSHACL.ttl).
