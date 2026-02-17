![Draft for review only](/assets/img/draft_for_review.svg)

# Code Pattern

This ontology specifies the city-level concepts for the code pattern of the city data model. The Code Pattern provides a structure to address the challenge of value enumeration with a general approach. In city data there are many classes of things that are intended to be instantiated using a set list of values (e.g., classification systems), however these values may change based on application or context. 
        The Code Pattern introduces a generic set of classes and properties that can be used to extend such classes to define various classification systems in an integrated way. Instead of enumerating value sets for classes, values can be defined with an associated Code that specifies additional metadata about the value and its origins.

This pattern imports the following patterns:

- [Core](Core.md)
- Organization Structure Pattern

This pattern consists of the following classes:

- [Code](Code.md)
- [Code Thing](CodeThing.md)

The formal definition of this pattern is available in [OWL Syntax](CodePattern.owl).

