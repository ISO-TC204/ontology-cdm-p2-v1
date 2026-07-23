# Information technology - City data model - Part 2: City level concepts - City resident pattern

This ontology specifies the city-level concepts for the city resident pattern of the city data model. As different cities have different definitions of who is that city's Resident, the City Resident Pattern must contain the properties required by each.  Central to all of the definitions is the concept of residing. Variously referred to as a home or domicile in which the resident spends significant amounts of time.  They may own it, rent it or just stay in it.  Legally, “reside means to dwell permanently or continuously. It expresses an idea that a person keeps or returns to a particular dwelling place as his fixed, settled, or legal abode. The meaning of reside implies a continuous arrangement” ; reside has both a temporal and spatial dimension. The city of Toronto's definition of a city resident includes the concept of owning property or owning or operating a business in the city. For Beijing, nationality is a unique aspect.

This pattern imports the following files:

- [https://w3id.org/citydata/part2/v1/BuildingPattern](https://w3id.org/citydata/part2/v1/BuildingPattern)
- [https://w3id.org/citydata/part2/v1/OrganizationPattern](https://w3id.org/citydata/part2/v1/OrganizationPattern)

This pattern consists of the following classes:

- [City Resident](CityResident.md)
- [City Resident Thing](CityResidentThing.md)
- [Controlled Entity](ControlledEntity.md)
- [Entity Operation](EntityOperation.md)
- [Entity Ownership](EntityOwnership.md)
- [Home Type](HomeType.md)
- [Residence](Residence.md)
- [Residential Relationship](ResidentialRelationship.md)
This module defines the following properties:

- [CityResidentDataProperty](../properties/CityResidentDataProperty.md)
- [CityResidentObjectProperty](../properties/CityResidentObjectProperty.md)
- [entity](../properties/entity.md)
- [forCity](../properties/forCity.md)
- [hasHomeType](../properties/hasHomeType.md)
- [hasResidence](../properties/hasResidence.md)
- [hasResidentialRelationship](../properties/hasResidentialRelationship.md)
- [operates](../properties/operates.md)
- [owns](../properties/owns.md)
- [percentOwnership](../properties/percentOwnership.md)
- [residentOf](../properties/residentOf.md)


The formal definition of this pattern is available in TURTLE Syntax in two files, the [core semantics](../CityResidentPattern.ttl) and the SHACL [restrictions](../CityResidentSHACL.ttl).
