# Information technology - City data model - Part 2: City level concepts - City pattern

This ontology specifies the city-level concepts for the city pattern of the city data model. The City pattern captures basic information about the geospatial aspects of the city.  In particular it represents the different ways in which the city is administratively divided.

This pattern imports the following files:

- [https://w3id.org/citydata/part2/v1/LandUsePattern](https://w3id.org/citydata/part2/v1/LandUsePattern)

This pattern consists of the following classes:

- [City](City.md)
- [City Administrative Area](CityAdministrativeArea.md)
- [City Pattern Thing](CityPatternThing.md)
- [Jurisdictional Area](JurisdictionalArea.md)
This module defines the following properties:

- [administrativeArea](../properties/administrativeArea.md)
- [administrativeAreaOf](../properties/administrativeAreaOf.md)
- [CityPatternDataProperty](../properties/CityPatternDataProperty.md)
- [CityPatternObjectProperty](../properties/CityPatternObjectProperty.md)
- [legalName](../properties/legalName.md)
- [residentPopulation](../properties/residentPopulation.md)


The formal definition of this pattern is available in TURTLE Syntax in two files, the [core semantics](../CityPattern.ttl) and the SHACL [restrictions](../CitySHACL.ttl).
