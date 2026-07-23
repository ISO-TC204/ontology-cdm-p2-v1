# Information technology - City data model - Part 2: City level concepts - Code pattern

This ontology specifies the city-level concepts for the code pattern of the city data model. The Code Pattern provides a structure to address the challenge of value enumeration with a general approach. In city data there are many classes of things that are intended to be instantiated using a set list of values (e.g., classification systems), however these values may change based on application or context. 
        The Code Pattern introduces a generic set of classes and properties that can be used to extend such classes to define various classification systems in an integrated way. Instead of enumerating value sets for classes, values can be defined with an associated Code that specifies additional metadata about the value and its origins.

This pattern imports the following files:

- [https://w3id.org/citydata/part1/v1/OrganizationStructurePattern](https://w3id.org/citydata/part1/v1/OrganizationStructurePattern)
- [https://w3id.org/citydata/part2/v1/CorePattern](https://w3id.org/citydata/part2/v1/CorePattern)

This pattern consists of the following classes:

- [Code](Code.md)
- [Code Thing](CodeThing.md)
This module defines the following properties:

- [CodeDataProperty](../properties/CodeDataProperty.md)
- [CodeObjectProperty](../properties/CodeObjectProperty.md)
- [definedBy](../properties/definedBy.md)
- [hasCode](../properties/hasCode.md)
- [specification](../properties/specification.md)


The formal definition of this pattern is available in TURTLE Syntax in two files, the [core semantics](../CodePattern.ttl) and the SHACL [restrictions](../CodeSHACL.ttl).
