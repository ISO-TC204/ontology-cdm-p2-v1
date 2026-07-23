# Information technology - City data model - Part 2: City level concepts - Building Pattern

This ontology specifies the city-level concepts for the building pattern of the city data model. A Building is a structure with some location in the urban system. The location of the Building in space may change due to construction, but the Parcel/Lot of land it is located on cannot. There may be many different types (subclasses) of buildings, such as House, Apartment Building, Office Building, and so on.

This pattern imports the following files:

- [https://w3id.org/citydata/part2/v1/InfrastructurePattern](https://w3id.org/citydata/part2/v1/InfrastructurePattern)

This pattern consists of the following classes:

- [Area Ratio](AreaRatio.md)
- [Building](Building.md)
- [Building Thing](BuildingThing.md)
- [Building Unit](BuildingUnit.md)
- [Building Use](BuildingUse.md)
- [Construction Status](ConstructionStatus.md)
- [Facility](Facility.md)
- [Year](Year.md)
This module defines the following properties:

- [BuildingDataProperty](../properties/BuildingDataProperty.md)
- [buildingFacility](../properties/buildingFacility.md)
- [BuildingObjectProperty](../properties/BuildingObjectProperty.md)
- [builtAccordingToConstructionCode](../properties/builtAccordingToConstructionCode.md)
- [floorAreaRatio](../properties/floorAreaRatio.md)
- [floorToCeilingHeight](../properties/floorToCeilingHeight.md)
- [hasBuildingFloorArea](../properties/hasBuildingFloorArea.md)
- [hasBuildingFootprintArea](../properties/hasBuildingFootprintArea.md)
- [hasBuildingHeight](../properties/hasBuildingHeight.md)
- [hasBuildingUnit](../properties/hasBuildingUnit.md)
- [hasConstructionStatus](../properties/hasConstructionStatus.md)
- [hasRent](../properties/hasRent.md)
- [hasUnitSize](../properties/hasUnitSize.md)
- [numAboveGroundFloors](../properties/numAboveGroundFloors.md)
- [numberOfBedrooms](../properties/numberOfBedrooms.md)
- [numberOfRooms](../properties/numberOfRooms.md)
- [numBuildingUnits](../properties/numBuildingUnits.md)
- [numFloors](../properties/numFloors.md)
- [propertyRegistrationID](../properties/propertyRegistrationID.md)
- [unitInBuilding](../properties/unitInBuilding.md)
- [use](../properties/use.md)
- [windowToWallRatio](../properties/windowToWallRatio.md)
- [yearOfConstruction](../properties/yearOfConstruction.md)


The formal definition of this pattern is available in TURTLE Syntax in two files, the [core semantics](../BuildingPattern.ttl) and the SHACL [restrictions](../BuildingSHACL.ttl).
