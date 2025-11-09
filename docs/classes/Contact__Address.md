# Address

![Address Diagram](../diagrams/Contact__Address.dot.svg)

<a href="../../diagrams/Contact__Address.dot.svg">Open interactive Address diagram</a>

## Specializations of Address

| Class | Description |
|-------|-------------|
| [Cottage Address](Contact__Cottage Address.md) |  |
| [Home Address](Contact__Home Address.md) |  |
| [Work Address](Contact__Work Address.md) |  |

## Formalization for Address

| Property | Constraint |
|----------|------------|
| hasAddressType | all AddressType |
| hasBuilding | max 1 owl::Thing |
| hasCity | max 1 owl::Thing |
| hasCitySection | max 1 owl::Thing |
| hasCountry | max 1 owl::Thing |
| hasPostalBox | max 1 owl::Thing |
| hasPostalCode | max 1 owl::Thing |
| hasProvince | max 1 owl::Thing |
| hasStreet | max 1 owl::Thing |
| hasStreetDirection | max 1 owl::Thing |
| hasStreetNumber | max 1 owl::Thing |
| hasStreetType | max 1 owl::Thing |
| hasUnitNumber | max 1 owl::Thing |
| maxStreetNumber | max 1 owl::Thing |
| minStreetNumber | max 1 owl::Thing |
| spatialLoc::hasLocation | max 1 owl::Thing |
| subClassOf | ContactThing |
| wgs84::lat | max 1 owl::Thing |
| wgs84::long | max 1 owl::Thing |

