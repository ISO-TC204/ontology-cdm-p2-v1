# InfrastructureElement

![InfrastructureElement Diagram](../diagrams/Infrastructure__InfrastructureElement.dot.svg)

<a href="../../diagrams/Infrastructure__InfrastructureElement.dot.svg">Open interactive InfrastructureElement diagram</a>

## Formalization for InfrastructureElement

| Property | Constraint |
|----------|------------|
| contact::hasAddress | all contact::Address |
| genProp::hasDescription | all xsd::string |
| genProp::hasIdentifier | all xsd::string |
| genProp::hasName | all xsd::string |
| i72::hasValue | all cityUnits::MonetaryValue |
| partwhole::hasProperPart | all InfrastructureElement |
| spatialLoc::hasLocation | all spatialLoc::Location |
| subClassOf | InfrastructureOntologyThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Infrastructure Element (Infrastructure)](Infrastructure__InfrastructureElement.md) | partwhole::hasProperPart |

