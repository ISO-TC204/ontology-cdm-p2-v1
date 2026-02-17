![Draft for review only](/assets/img/draft_for_review.svg)

# Facility

![Facility Diagram](diagrams/Facility.dot.svg)

<a href="diagrams/Facility.dot.svg">Open interactive Facility diagram</a>

## Formalization for Facility

| Property | Constraint |
|----------|------------|
| cdm1:hasLocation | exactly 1 owl:Thing |
| subClassOf | InfrastructureElement |
| subClassOf | BuildingThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Building](Building.md) | buildingFacility |
| [Building Unit](BuildingUnit.md) | buildingFacility |

