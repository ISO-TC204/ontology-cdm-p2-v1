![Draft for review only](/assets/img/draft_for_review.svg)

# Residence

![Residence Diagram](diagrams/Residence.dot.svg)

<a href="diagrams/Residence.dot.svg">Open interactive Residence diagram</a>

## Formalization for Residence

| Property | Constraint |
|----------|------------|
| forCity | max 1 owl:Thing |
| hasAddress | max 1 owl:Thing |
| hasHomeType | max 1 owl:Thing |
| hasResidentialRelationship | exactly 1 owl:Thing |
| subClassOf | CityResidentThing |
| time:hasTime | max 1 owl:Thing |

## Used by classes

| Class | Property |
|-------|----------|
| [City Resident](CityResident.md) | hasResidence |

