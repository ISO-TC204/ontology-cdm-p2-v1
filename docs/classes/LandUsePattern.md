# Information technology - City data model - Part 2: City level concepts - Land Use pattern

This ontology specifies the city-level concepts for the land use pattern of the city data model. The Land Use Pattern captures concepts related to land use and cover over time. Land Use Classifications provide a means of describing the land cover/use in a standard way. Various classification systems are used to identify types of land use. Currently, we include LBCS, CLUMP, and AAFC. The ontology reuses and extends the Land Based Classification Standards (LBCS) Ontology  presented by (Montenegro, Gomes, Urbano, and Duarte, 2011) for this purpose.

This pattern imports the following files:

- [https://w3id.org/citydata/part2/v1/CodePattern](https://w3id.org/citydata/part2/v1/CodePattern)

This pattern consists of the following classes:

- [Land Area](LandArea.md)
- [Land Use Classification](LandUseClassification.md)
- [Land Use Thing](LandUseThing.md)
This module defines the following properties:

- [hasArea](../properties/hasArea.md)
- [hasLandArea](../properties/hasLandArea.md)
- [hasPopulation](../properties/hasPopulation.md)
- [landUse](../properties/landUse.md)
- [LandUseObjectProperty](../properties/LandUseObjectProperty.md)


The formal definition of this pattern is available in TURTLE Syntax in two files, the [core semantics](../LandUsePattern.ttl) and the SHACL [restrictions](../LandUseSHACL.ttl).
