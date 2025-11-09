# Residence

![Residence Diagram](../diagrams/CityResident__Residence.dot.svg)

<a href="../../diagrams/CityResident__Residence.dot.svg">Open interactive Residence diagram</a>

## Formalization for Residence

| Property | Constraint |
|----------|------------|
| contact::hasAddress | max 1 owl::Thing |
| forCity | max 1 owl::Thing |
| hasHomeType | max 1 owl::Thing |
| hasResidentialRelationship | exactly 1 owl::Thing |
| subClassOf | CityResidentOntologyThing |
| time::hasTime | max 1 owl::Thing |

## Used by classes

| Class | Property |
|-------|----------|
| [City Resident (CityResident)](CityResident__CityResident.md) | hasResidence |

