![Draft for review only](/assets/img/draft_for_review.svg)

# InfrastructureElement

![InfrastructureElement Diagram](diagrams/InfrastructureElement.dot.svg)

<a href="diagrams/InfrastructureElement.dot.svg">Open interactive InfrastructureElement diagram</a>

## Specializations of InfrastructureElement

| Class | Description |
|-------|-------------|
| [Bridge](Bridge.md) |  |
| [Bridge Segment](BridgeSegment.md) |  |
| [Building](Building.md) |  |
| [Building Unit](BuildingUnit.md) |  |
| [Facility](Facility.md) |  |
| [Rail Line](RailLine.md) |  |
| [Rail Link](RailLink.md) |  |
| [Rail Segment](RailSegment.md) |  |
| [Road](Road.md) |  |
| [Road Link](RoadLink.md) |  |
| [Road Segment](RoadSegment.md) |  |
| [Travelled Way](TravelledWay.md) |  |
| [Travelled Way Link](TravelledWayLink.md) |  |
| [Travelled Way Segment](TravelledWaySegment.md) |  |
| [Tunnel](Tunnel.md) |  |
| [Tunnel Segment](TunnelSegment.md) |  |

## Formalization for InfrastructureElement

| Property | Constraint |
|----------|------------|
| cdm1:hasDescription | all xsd:string |
| cdm1:hasIdentifier | all xsd:string |
| cdm1:hasLocation | all cdm1:Location |
| cdm1:hasName | all xsd:string |
| cdm1:hasProperPart | all InfrastructureElement |
| hasAddress | all Address |
| i72:hasValue | all cdm1:MonetaryValue |
| subClassOf | InfrastructureThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Infrastructure Element](InfrastructureElement.md) | cdm1:hasProperPart |

