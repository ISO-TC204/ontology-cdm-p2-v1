![Draft for review only](/assets/img/draft_for_review.svg)

# Bridge

NOTE: A Bridge is identified as such by a governing body.

![Bridge Diagram](diagrams/Bridge.dot.svg)

<a href="diagrams/Bridge.dot.svg">Open interactive Bridge diagram</a>

## Formalization for Bridge

| Property | Constraint |
|----------|------------|
| cdm1:hasProperPart | all BridgeSegment |
| subClassOf | InfrastructureElement |
| supports | all TravelledWaySegment |

