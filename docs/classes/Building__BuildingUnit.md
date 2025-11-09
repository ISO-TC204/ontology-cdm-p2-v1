# BuildingUnit

![BuildingUnit Diagram](../diagrams/Building__BuildingUnit.dot.svg)

<a href="../../diagrams/Building__BuildingUnit.dot.svg">Open interactive BuildingUnit diagram</a>

## Formalization for BuildingUnit

| Property | Constraint |
|----------|------------|
| buildingFacility | all Facility |
| change::existsAt | exactly 1 owl::Thing |
| contact::hasAddress | all contact::Address |
| floorToCeilingHeight | all cityUnits::Length |
| hasRent | all cityUnits::MonetaryValue |
| numberOfBedrooms | all xsd::nonNegativeInteger |
| numberOfRooms | all xsd::nonNegativeInteger |
| partwhole::hasValue | all cityUnits::MonetaryValue |
| subClassOf | BuildingOntologyThing |
| subClassOf | change::Manifestation |
| subClassOf | infrastructure::InfrastructureElement |
| unitInBuilding | exactly 1 owl::Thing |
| unitSize | all cityUnits::Area |

## Used by classes

| Class | Property |
|-------|----------|
| [Building (Building)](Building__Building.md) | hasBuildingUnit |

